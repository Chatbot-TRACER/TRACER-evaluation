# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **10 functionalities** discovered across **0 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📄 Uncategorized** (10 functions)
- *`Provide Information About Arucas Campaign`*: "Provides information about the 'Regálate Arucas' campaign, including details...
- *Prompt For Information About Services*: The chatbot prompts the user for more specific questions regarding the inform...
- *Prompt For Information About Services*: The chatbot prompts the user for specific questions regarding the services th...
- *Provide Service Information Link*: The chatbot provides a link to the specific information about the environment...
- *`Provide Information About Arucas Services`*: "Provides detailed information regarding the socioeconomic development servic...
- *...and 5 more functions*

## 🗂️ Functionality Details

### 📄 Uncategorized (10 functions)

#### 🔧 `Provide Information About Arucas Campaign`

**Description:** "Provides information about the 'Regálate Arucas' campaign, including details about its raffles and directs the user to the official website for further information."

**Parameters:** None

**Outputs:**
- `campaign_information`: Information and official website link to access all information about the 'Regálate Arucas' campaign and its raffles.

---

#### 🔧 Prompt For Information About Services

**Description:** The chatbot prompts the user for more specific questions regarding the information they seek about Arucas.

**Parameters:** None

**Outputs:** None

**Child Functions:**
- `Prompt For Information About Services`: The chatbot prompts the user for specific questions regarding the services they want to learn about.

---

#### 🔧 Prompt For Information About Services

**Description:** The chatbot prompts the user for specific questions regarding the services they want to learn about.

**Parameters:** None

**Outputs:**
- `service_information_link`: URL to detailed service information for 'Alumbrado' service

---

#### 🔧 Provide Service Information Link

**Description:** The chatbot provides a link to the specific information about the environmental services offered by the Ayuntamiento of Arucas.

**Parameters:** None

**Outputs:**
- `link_to_environment_service`: URL for service details.

---

#### 🔧 `Provide Information About Arucas Services`

**Description:** "Provides detailed information regarding the socioeconomic development services available in Arucas, covering various categories such as business census, news, training, orientation, and job offers."

**Parameters:** None

**Outputs:**
- `services_summary`: Information includes business census, news, training, orientation, and job offers.
- `access_link`: Link to the Office of Local Development's website.

---

#### 🔧 `Provide Contact Information For Library`

**Description:** "Supplies the contact details (phone number and email address) for the Library of Arucas."

**Parameters:** None

**Outputs:**
- `library_contact_info`: Contact phone number and email address for the Library of Arucas, including phone number 928633461.

---

#### 🔧 Provide Cultural Activity Information Link

**Description:** "Provides a link to access detailed information about cultural activities in Arucas."

**Parameters:** None

**Outputs:**
- `cultural_activity_link`: A URL providing detailed information about cultural activities in Arucas and access to the service of Culture.

---

#### 🔧 `Provide Transparency Link`

**Description:** "Supplies a link to the transparency information portal of the Ayuntamiento de Arucas in response to a user request."

**Parameters:** None

**Outputs:**
- `transparency_link`: URL to the Ayuntamiento de Arucas transparency portal, available at https://arucas.sedelectronica.es/transparency.

---

#### 🔧 `Provide Initial Information On Tramites`

**Description:** "Supplies detailed instructions on how to initiate the process for a prior work communication request, encompassing information on physical locations, online submission options, documentation requirements, and payment details."

**Parameters:** None

**Outputs:**
- `physical_location`: Office de Atención Ciudadana at C/Alcalde Suárez Franchy n° 11, including its address.
- `appointment_request_methods`: Options to request an appointment (electronically via service or by phone) and phone number for appointment scheduling.
- `documentation_requirements`: Minimum documentation needed for requests, including details for communication requests.
- `tax_information`: Details regarding the ICIO payment, including percentage of the construction budget and payment methods.
- `electronic_procedure_advice`: Recommendations for using Google Chrome for electronic submissions and electronic requests.
- `contact_info_virtual_office`: Phone number for clarification on ICIO payment procedure.

---

#### 🔧 `Provide Previous Communication Documentation Requirements`

**Description:** "The chatbot provides requirements for submitting documentation related to previous communications, including necessary steps and payment information."

**Parameters:** None

**Outputs:**
- `required_documentation_summary`: Documentation required generally includes the model of Communication Previa and detailed descriptions of the intended work.
- `payment_information`: Information regarding the ICIO and payment methods.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
¿Disculpa?
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 636 |
| Successful Calls | 636 |
| Failed Calls | 0 |
| Total Tokens | 658,280 |
| Estimated Cost | $0.4160 USD |
| Execution Time | 00:13:02 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 571,473 | 5,617 | 577,090 | $0.3564 |
| Analysis | 75,135 | 6,055 | 81,190 | $0.0596 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

