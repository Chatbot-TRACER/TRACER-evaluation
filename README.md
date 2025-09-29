# TRACER Evaluation Results

This repository contains the evaluation results for the [TRACER](https://github.com/Chatbot-TRACER/TRACER) tool.


## Experimental Design

### Research Questions

**RQ1: Is TRACER effective in discovering chatbot functionality?**
- Evaluated through coverage metrics during profile generation (TRACER) and profile execution (Sensei)
- Metrics: Module, Input, Value, and Question coverage

**RQ2: How effective are the generated profiles at detecting errors?**
- Evaluated through mutation testing
- Metrics: Mutation score, killed vs. alive mutants

**RQ3: How accurately does TRACER model the functionalities of real-world, deployed chatbots?**
- Evaluated by measuring precision on deployed chatbots.
- Metrics: Precision

### Taskyto Chatbots

| Chatbot | Modules | YAML LoC | Python LoC | Domain |
|---------|---------|----------|------------|---------|
| Bike-shop | 3 | 65 | 0 | Bike repair appointments & maintenance |
| Photography | 5 | 140 | 14 | Photography shop services & pricing |
| Pizza-order | 10 | 282 | 58 | Pizza ordering with customization |
| Veterinary | 3 | 71 | 0 | Veterinary appointments & inquiries |

### Experimental Parameters

- **Repetitions**: 3 executions per chatbot for RQ1
- **TRACER Settings**: 20 conversations, 12 turns per conversation
- **LLM Configuration**:
  - TRACER: Google Gemini 2.0 Flash (temperature: 1.0)
  - Sensei: OpenAI GPT-4o-mini (variable temperature per profile)
  - Taskyto: OpenAI GPT-4o-mini (temperature: 0.0)

## Directory Structure (Per Chatbot)

### Root Level Files

The root directory contains aggregated results for both TRACER and Sensei executions across all chatbots. The Sensei execution results are often referred to as "profiles" in the context of this evaluation since Sensei executes the generated profiles, while TRACER generates them.

The `{chatbot}_aggregate_profile_coverage.json` contains the merged coverage logs of Taskyto, the chatbot we are testing, so if in one conversation the log has that we activated the `order_pizza` module with the input `pizza_type` and the value `carbonara`, then in another conversation we activated the same module with the same input but with `marinara`, both will be merged into the same coverage log, thus, allowing us to calculate the coverage metrics.

The ones that are called aggregated are called like this because they merged the coverage of the three executions of TRACER and Sensei, thus, allowing us to have a single file with the coverage metrics of all the executions.

```bash
{chatbot}/
├── {chatbot}_aggregate_profile_coverage.json
├── {chatbot}_aggregate_profile_report.json
├── {chatbot}_aggregate_profile_report.txt
├── {chatbot}_aggregate_tracer_coverage.json
├── {chatbot}_aggregate_tracer_report.json
├── {chatbot}_aggregate_tracer_report.txt
├── 📁 execution_1/
├── 📁 execution_2/
├── 📁 execution_3/
└── 📁 mutants/
```

### Execution Directory Structure

Each execution directory contains results from a specific run of the TRACER with the indicated parameters, then the generated profiles are executed by Sensei. It is important to note that the previous part was aggregated, meaning that it contains the results of all the executions, while this part is not aggregated, it contains the results of a single execution of TRACER and Sensei.

The structure is as follows:

```bash
execution_X/
├── 📁 profile_coverage/     # Coverage achieved by generated profiles
├── 📁 profile_logs/         # Raw execution logs from Taskyto during Sensei execution
├── 📁 profiles/             # Generated user profiles (YAML format)
├── 📁 sensei_output/        # Profile execution results
│   ├── 📁 conversation_outputs/  # Individual conversation transcripts
│   └── 📁 reports/              # Execution statistics and cost reports
├── 📁 tracer_coverage/      # Coverage achieved by TRACER exploration
├── 📁 tracer_logs/          # Raw execution logs from Taskyto during TRACER execution
└── workflow_graph.pdf       # Visual representation of discovered workflow
```

### Mutation Testing Structure

The `mutants/` directory contains the results of mutation testing, where various faults were injected into the chatbot modules to evaluate the effectiveness of the generated profiles in detecting errors. Each mutant directory corresponds to a specific mutation.

```bash
mutants/
├── 📁 ChangeRephrase_X/
├── 📁 DeleteDataFromResponse_X/
├── 📁 DeleteEnumDataValue_X/
...
```

Each mutant directory contains:

```bash
MutationType_X/
├── 📁 execution_1/
├── 📁 execution_2/
└── 📁 execution_3/
```

## Key File Types

### Coverage Files

- `*_coverage.json`: Merged logs from the aforementioned Taskyto logs from multiple conversations in a single file.
- `*_report.json`: Report file summarizing coverage metrics in JSON format (for future API integration)
- `*_report.txt`: Human-readable summaries

### TRACER Functionality Graph

- `workflow_graph.pdf`: Visual representation of the discovered functionalities of the chatbot, showing functionalities, parameters outputs, and their relationships.

### Profile Files

- `profiles/*.yaml`: TRACER's generated user profiles for Sensei.

### Conversation Outputs

- `execution_X/sensei_output/conversation_outputs/[Profile Name]/[Timestamp]/`: Individual conversation transcripts
- Files numbered sequentially (0_, 1_, 2_, etc.) representing conversation instances

### Reports

- `__cost_reports__/*.csv`: API usage and cost tracking
- `__stats_reports__/*.yml`: Execution statistics and performance metrics

## Results Summary

### RQ1: Coverage Results

TRACER achieved high coverage across all chatbots, with profile execution (Sensei) generally achieving equal or higher coverage than exploration alone. This was expected since TRACER might find a functionality (e.g., ordering a pizza) and will create profiles to order all the possible pizzas, but TRACER itself will not order all the pizzas, thus, the profile execution will achieve higher coverage.

These results can be found in the `*_aggregate_tracer_report.txt` and `*_aggregate_profile_report.txt` files for each chatbot.

For each individual execution, the coverage metrics can be found in the `execution_X/tracer_coverage/` and `execution_X/profile_coverage/` directories, respectively.

| Chatbot | Statistic | Tool | Module | Input | Value | Question |
|---------|-----------|------|--------|--------|--------|----------|
| **Bike-shop** | Median | TRACER | 100% | 85.71% | 83.33% | 75% |
| | | Sensei | 100% | 71.43% | 50.00% | 50% |
| | Aggregate | TRACER | 100% | 85.71% | 83.33% | 75% |
| | | Sensei | 100% | 85.71% | 83.33% | 50% |
| **Photography** | Median | TRACER | 100% | 73.33% | 64.71% | 20% |
| | | Sensei | 100% | 80.00% | 58.82% | 40% |
| | Aggregate | TRACER | 100% | 73.33% | 76.47% | 20% |
| | | Sensei | 100% | 93.33% | 94.12% | 80% |
| **Pizza-shop** | Median | TRACER | 83.33% | 67.86% | 27.38% | 100% |
| | | Sensei | 100% | 96.43% | 69.05% | 100% |
| | Aggregate | TRACER | 100% | 100.00% | 48.81% | 100% |
| | | Sensei | 100% | 100.00% | 90.48% | 100% |
| **Veterinary** | Median | TRACER | 100% | 50.00% | 44.44% | 20% |
| | | Sensei | 100% | 62.50% | 44.44% | 40% |
| | Aggregate | TRACER | 100% | 62.50% | 55.56% | 40% |
| | | Sensei | 100% | 87.50% | 77.78% | 80% |


### RQ2: Mutation Testing Results

Overall mutation score of 84.6% across all chatbots, demonstrating the effectiveness of generated profiles in detecting injected faults. Individual chatbot results:

- Bike-shop: 91%
- Photography: 76.9%
- Pizza-order: 75%
- Veterinary: 91.7%

### RQ3: Accuracy of Modeling Deployed Chatbot

For this experiment we run TRACER against real-world deployed chatbots and measured the preicision of the functionalities inferred.
This was achieved by manually checking that the functionalities were valid (i.e., the chatbot really offered them),
and by checking that there were no duplicates.

| Chatbot         | # Func. (TRACER) | TP (Verified) | FP (Incorrect/Duplicate) | Precision (%) |
| --------------- | ---------------- | ------------- | ------------------------ | ------------- |
| Ada-UAM         | 22               | 22            | 0                        | 100.0         |
| Gallo de Morón  | 29               | 27            | 2                        | 93.1          |
| Madrid te Cuida | 91               | 88            | 3                        | 96.7          |
| Gestri          | 27               | 27            | 0                        | 100.0         |
| Arucas          | 41               | 37            | 4                        | 90.2          |
| **Total**       | **210**          | **201**       | **9**                    | **96.0**      |

Out of all the False Positives (FP) only one was due to a hallucinated functionality, the rest were semantic duplicates.
