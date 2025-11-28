# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **20 functionalities** discovered across **4 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Account & Access** (7 functions)
- *Prompt For Password Change*: Guides the user through the steps to change their password if they have forgo...
- *Remind Password Change Frequency*: The chatbot reminds the user to change their password periodically to avoid a...
- *Provide Moodle Access Information*: Explains the requirements for accessing Moodle, including the need for an ins...
- *List Available Buttons*: Presents a list of buttons available for the user to click on for further ass...
- *Provide User Id Retrieval Support*: Guides the user on how to retrieve their student ID (ID-UAM) if forgotten, in...
- *...and 2 more functions*

**📂 Contact Information** (2 functions)
- *Provide Contact Information*: Provides users with various methods to contact the Centro de Atención a Usuar...
- *Suggest Contact For Support*: Suggests the user contact the Oficina de Atención al Estudiante for issues re...

**📂 General Information** (7 functions)
- *Provide Faq Link*: The chatbot directs the user to the frequently asked questions section regard...
- *Provide Initial Information*: The chatbot provides initial instructions on how to obtain help with UAM virt...
- *Provide Information On Nia Obtainment*: The chatbot details the process of obtaining an academic identification numbe...
- *Provide Welcome Day Info*: The chatbot provides information about the Welcome Day event and its relevanc...
- *Provide Future Students Info*: The chatbot presents information aimed at future students, including availabl...
- *...and 2 more functions*

**📂 Service Information** (4 functions)
- *Provide Service Catalogue Reference*: Directs the user to the service catalogue offered by the Centre for User Atte...
- *Provide Service Information*: The chatbot provides information about obtaining accounts for external users ...
- *Prompt For Service Detail Type*: Prompts the user to specify the type of detail they would like about integrat...
- *Present Available Service Options*: Offers links to resources and services related to ID-UAM, including obtaining...

## 🗂️ Functionality Details

### 📂 Account & Access (7 functions)

#### 🔧 Prompt For Password Change

**Description:** Guides the user through the steps to change their password if they have forgotten it, including obtaining any necessary codes.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Remind Password Change Frequency

**Description:** The chatbot reminds the user to change their password periodically to avoid account locking.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Moodle Access Information

**Description:** Explains the requirements for accessing Moodle, including the need for an institutional account and outlines the available environments.

**Parameters:** None

**Outputs:**
- `access_requirements`: Information regarding the necessity of holding an institutional account to access Moodle.
- `available_environments`: Details on the two Moodle environments: Grado/Postgrado and Formación.

---

#### 🔧 List Available Buttons

**Description:** Presents a list of buttons available for the user to click on for further assistance related to Moodle access.

**Parameters:** None

**Outputs:**
- `button_texts`: Descriptions of the available buttons related to Moodle access issues.

---

#### 🔧 Provide User Id Retrieval Support

**Description:** Guides the user on how to retrieve their student ID (ID-UAM) if forgotten, including options for further assistance through the CAU.

**Parameters:** None

**Outputs:**
- `contact_information`: Email and options for CAU assistance, including retrieving an ID.
- `activation_code_retrieval`: Instructions for obtaining an activation code.
- `password_management`: Steps for changing the password and suggestions for periodic password changes.

---

#### 🔧 Provide Password Setup Information

**Description:** Provides information and steps for setting up a password for the first time after user registration, including instructions for obtaining an activation code and establishing the password.

**Parameters:** None

**Outputs:**
- `password_setup_link`: URL for password establishment steps.

---

#### 🔧 Provide Activation Code Instructions

**Description:** Instructs the user on how to obtain or generate an activation code for changing their password.

**Parameters:** None

**Outputs:** None

---


### 📂 Contact Information (2 functions)

#### 🔧 Provide Contact Information

**Description:** Provides users with various methods to contact the Centro de Atención a Usuarios (CAU) for assistance, including email, phone number, physical address, and operational hours.

**Parameters:** None

**Outputs:**
- `contact_info`: Contact details for CAU support, including email, phone number, and physical address.
- `operational_hours`: Standard operational hours for assistance, which are Monday to Friday, excluding holidays, from 9:00h to 17:30h, and details on operational hours during suspension.
- `faqs_link`: Link to frequently asked questions.
- `services_catalog_link`: Link to the catalog of services offered.
- `contact_methods`: Methods to contact CAU via email, phone, or in person.

---

#### 🔧 Suggest Contact For Support

**Description:** Suggests the user contact the Oficina de Atención al Estudiante for issues related to virtual platforms at UAM.

**Parameters:** None

**Outputs:** None

---


### 📂 General Information (7 functions)

#### 🔧 Provide Faq Link

**Description:** The chatbot directs the user to the frequently asked questions section regarding the CAU.

**Parameters:** None

**Outputs:**
- `FAQ_resource`: Link or reference to the frequently asked questions for user assistance

---

#### 🔧 Provide Initial Information

**Description:** The chatbot provides initial instructions on how to obtain help with UAM virtual platforms and Moodle functionalities.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Information On Nia Obtainment

**Description:** The chatbot details the process of obtaining an academic identification number (NIA) for new students.

**Parameters:** None

**Outputs:**
- `nia_obtainment_info`: Information on obtaining a NIA and related account access steps.

---

#### 🔧 Provide Welcome Day Info

**Description:** The chatbot provides information about the Welcome Day event and its relevance for new students.

**Parameters:** None

**Outputs:**
- `welcome_day_link`: URL with details about the Welcome Day.

---

#### 🔧 Provide Future Students Info

**Description:** The chatbot presents information aimed at future students, including available courses and degrees.

**Parameters:** None

**Outputs:**
- `future_students_link`: URL with resources for prospective students.

---

#### 🔧 Provide Admission To Grados Info

**Description:** The chatbot provides information related to the admission process for degrees (grados) at UAM.

**Parameters:** None

**Outputs:**
- `admission_to_grados_link`: URL with details about admission processes.

---

#### 🔧 Provide Waitlist Info

**Description:** The chatbot provides information about the waitlist processes for degree admissions.

**Parameters:** None

**Outputs:**
- `waitlist_info_link`: URL with details regarding admission waitlists.

---


### 📂 Service Information (4 functions)

#### 🔧 Provide Service Catalogue Reference

**Description:** Directs the user to the service catalogue offered by the Centre for User Attention (CAU) and provides contact information and service hours for further inquiries.

**Parameters:** None

**Outputs:**
- `contact_methods`: Various ways to contact the CAU, including email, phone, and in-person.
- `service_hours`: Information about the operational hours for contacting the CAU.
- `service_catalogue`: Reference to the catalogue of services offered by the CAU.

---

#### 🔧 Provide Service Information

**Description:** The chatbot provides information about obtaining accounts for external users and integrated services in the ID-UAM system.

**Parameters:** None

**Outputs:**
- `available_services_list`: Obtaining a student account for first enrollment

---

#### 🔧 Prompt For Service Detail Type

**Description:** Prompts the user to specify the type of detail they would like about integrated services, including options for features or pricing.

**Parameters:**
- `detail_requested`: Represents whether the user wants to know about features or pricing of the services. *Options: `features`, `pricing`*

**Outputs:** None

---

#### 🔧 Present Available Service Options

**Description:** Offers links to resources and services related to ID-UAM, including obtaining identifiers, account setup, and password change procedures.

**Parameters:** None

**Outputs:**
- `available_service_options`: Links to services include identifier retrieval, integrated services, steps for obtaining student and staff accounts, service information, and password change procedures.
- `support_contact`: Support contact details for issues related to account setup.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
¿Puedes preguntármelo de otra forma? o, si lo prefieres, puedes consultar nuestro\ncatálogo de servicios\n.\nRespondo a preguntas dirigidas al\nCentro de Atención a Usuarios del servicio de Tecnologías de la Información.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 1,059 |
| Successful Calls | 1,059 |
| Failed Calls | 0 |
| Total Tokens | 1,225,835 |
| Estimated Cost | $0.8031 USD |
| Execution Time | 00:25:08 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 896,124 | 14,426 | 910,550 | $0.5723 |
| Analysis | 292,162 | 23,123 | 315,285 | $0.2308 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

