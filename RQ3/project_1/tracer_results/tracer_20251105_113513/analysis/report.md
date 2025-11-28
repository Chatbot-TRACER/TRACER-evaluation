# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **10 functionalities** discovered across **9 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Customer Support** (1 functions)
- *Present Assistance Queries*: Presents a list of available queries or assistance options the chatbot can pr...

**📂 External Resources** (1 functions)
- *Guide To Additional Information*: The chatbot informs the user that it is a customer service channel and offers...

**📂 Navigation Assistance** (1 functions)
- *Prompt For Station Selection*: Requests the user to specify the name of their current station for navigation...

**📂 Network Information** (1 functions)
- *Provide Current Network Status*: Informs the user about the current status of the transport network, including...

**📂 Purchase Information** (1 functions)
- *Provide Multi Card Purchase Information*: The chatbot provides information on purchasing the Multi Card, including its ...

**📂 Tourist Information** (1 functions)
- *Provide Tourist Title Info*: Gives detailed information about the Título Turístico, including its duration...

**📂 Train Information** (2 functions)
- *Present Train Line Options*: Presents the available train or metro lines at a specified station for the us...
- *Present Upcoming Trains Info*: Presents information about the next upcoming trains at a specified station, i...

**📂 User Authentication** (1 functions)
- *Prompt For Privacy Policy Acceptance*: Requests the user to accept the privacy policy before proceeding with assista...

**📂 User Preferences** (1 functions)
- *Prompt For Language Selection*: The chatbot asks the user to select their preferred language for communication.

## 🗂️ Functionality Details

### 📂 Customer Support (1 functions)

#### 🔧 Present Assistance Queries

**Description:** Presents a list of available queries or assistance options the chatbot can provide for user inquiries, allowing the user to select their desired option.

**Parameters:** None

**Outputs:**
- `assistance_options`: Options for assistance including checking next trains, recommending fares, transport card information, directions to stations, checking network status, installation status, and other inquiries.

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

**Child Functions:**
- `Provide Current Network Status`: Informs the user about the current status of the transport network, including details of incidents affecting specific lines and the operational status of all transport lines.
- `Prompt For Station Selection`: Requests the user to specify the name of their current station for navigation assistance and relevant information.

---


### 📂 External Resources (1 functions)

#### 🔧 Guide To Additional Information

**Description:** The chatbot informs the user that it is a customer service channel and offers a link to the main website for additional information.

**Parameters:** None

**Outputs:**
- `external_resource_link`: www.metromadrid.es

---


### 📂 Navigation Assistance (1 functions)

#### 🔧 Prompt For Station Selection

**Description:** Requests the user to specify the name of their current station for navigation assistance and relevant information.

**Parameters:**
- `station_name`: Represents the name of the user's current station or location for directions.

**Outputs:** None

**Parent Functions:** `Present Assistance Queries`

**Child Functions:**
- `Present Train Line Options`: Presents the available train or metro lines at a specified station for the user to choose from.

---


### 📂 Network Information (1 functions)

#### 🔧 Provide Current Network Status

**Description:** Informs the user about the current status of the transport network, including details of incidents affecting specific lines and the operational status of all transport lines.

**Parameters:** None

**Outputs:**
- `network_incidents`: Details of current incidents affecting specific transport lines, including ongoing network incidents and the operational status of affected services.
- `operational_status`: Confirmation of operational status for the rest of the transport lines.

**Parent Functions:** `Present Assistance Queries`

---


### 📂 Purchase Information (1 functions)

#### 🔧 Provide Multi Card Purchase Information

**Description:** The chatbot provides information on purchasing the Multi Card, including its cost and where to buy it.

**Parameters:** None

**Outputs:**
- `purchase_info`: The Multi Card costs 2.50 euros and can be bought at metro stations' automatic machines or authorized sales points.

---


### 📂 Tourist Information (1 functions)

#### 🔧 Provide Tourist Title Info

**Description:** Gives detailed information about the Título Turístico, including its duration options and applicable zones.

**Parameters:** None

**Outputs:**
- `title_validity`: Description of the validity periods for the Título Turístico
- `title_age_options`: Descriptions of the normal and infant titles available based on user age
- `title_zone_applicability`: Information on how the title applies to different zones

---


### 📂 Train Information (2 functions)

#### 🔧 Present Train Line Options

**Description:** Presents the available train or metro lines at a specified station for the user to choose from.

**Parameters:**
- `station_name`: The name of the station whose line options are being inquired about.

**Outputs:**
- `available_train_lines`: List of available train lines at the specified station, including help for Line 1, Line 2, Line 3, Line 4, Line 5, and Line 10.
- `connection_details`: Details about connections available at the station.

**Parent Functions:** `Prompt For Station Selection`

**Child Functions:**
- `Present Upcoming Trains Info`: Presents information about the next upcoming trains at a specified station, including line numbers, directions, and arrival times.

---

#### 🔧 Present Upcoming Trains Info

**Description:** Presents information about the next upcoming trains at a specified station, including line numbers, directions, and arrival times.

**Parameters:**
- `station_name`: The name of the station provided by the user where upcoming trains are to be checked.
- `selected_line`: The specific metro line the user wants to check for upcoming trains. *Options: `LINE_10`, `LINE_4`, `LINE_5`, `all_lines`*

**Outputs:**
- `upcoming_trains`: Details of the next trains arriving at the station, including line numbers, directions, arrival times, and waiting times.

**Parent Functions:** `Present Train Line Options`

---


### 📂 User Authentication (1 functions)

#### 🔧 Prompt For Privacy Policy Acceptance

**Description:** Requests the user to accept the privacy policy before proceeding with assistance.

**Parameters:**
- `privacy_acceptance`: User's acceptance of the privacy policy. *Options: `Acepto`, `No acepto`*

**Outputs:** None

**Child Functions:**
- `Present Assistance Queries`: Presents a list of available queries or assistance options the chatbot can provide for user inquiries, allowing the user to select their desired option.

---


### 📂 User Preferences (1 functions)

#### 🔧 Prompt For Language Selection

**Description:** The chatbot asks the user to select their preferred language for communication.

**Parameters:**
- `language_option`: The user's preferred language for communication. *Options: `Español`, `Inglés`*

**Outputs:**
- `language_options`: English, Spanish

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Este canal está habilitado para ofrecer información de servicio y atención al cliente de Metro de Madrid. Para otros asuntos, por favor, consulta nuestra web oficial: 🌐 www.metromadrid.es ¿Puedo ayudarte en algo más? 👇
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 1,403 |
| Successful Calls | 1,403 |
| Failed Calls | 0 |
| Total Tokens | 1,276,129 |
| Estimated Cost | $0.8714 USD |
| Execution Time | 01:50:21 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 981,408 | 28,975 | 1,010,383 | $0.6584 |
| Analysis | 235,978 | 29,768 | 265,746 | $0.2130 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

