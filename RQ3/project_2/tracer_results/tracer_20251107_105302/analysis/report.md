# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **15 functionalities** discovered across **3 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Account & Access** (10 functions)
- *Present Moodle Access Information*: Provides information about the requirements for accessing Moodle and the type...
- *Prompt For Password Change*: Guides the user on the procedure to change their ID-UAM account password when...
- *Present Identification Retrieval Options*: Informs the user about methods to retrieve their ID-UAM identifier, including...
- *Present Id Uam Services Overview*: Provides an overview of the services integrated into the ID-UAM system, inclu...
- *Prompt For Password Setup*: Instructs users on how to establish a password for their account for the firs...
- *...and 5 more functions*

**📂 Chatbot Meta** (2 functions)
- *Prompt For Reformulated Question*: The chatbot asks the user to reformulate their question in other words or sug...
- *Prompt For Service Ticket Submission*: The chatbot advises the user to open a ticket at the CAU for queries related ...

**📂 General Information** (3 functions)
- *Provide Virtual Platform Contact Info*: Provides the contact information for the Office of Student Services regarding...
- *Provide Contact Information For Support*: Provides users with comprehensive contact information for user support, inclu...
- *Repeat Contact Information For Cau*: The chatbot repeats the detailed contact information for the CAU upon user re...

## 🗂️ Functionality Details

### 📂 Account & Access (10 functions)

#### 🔧 Present Moodle Access Information

**Description:** Provides information about the requirements for accessing Moodle and the types of environments available.

**Parameters:** None

**Outputs:**
- `moodle_access_requirements`: Information regarding the necessity of having a UAM institutional account (ID UAM).
- `moodle_environment_types`: Types of Moodle environments including Grado, Postgrado, and Formación.

---

#### 🔧 Prompt For Password Change

**Description:** Guides the user on the procedure to change their ID-UAM account password when they have forgotten their credentials, providing necessary steps according to the user's status.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Present Identification Retrieval Options

**Description:** Informs the user about methods to retrieve their ID-UAM identifier, including searching by DNI or contacting the support center.

**Parameters:** None

**Outputs:**
- `retrieval_methods`: Options for recovering ID-UAM identifier include searching by DNI and contacting CAU (support).

---

#### 🔧 Present Id Uam Services Overview

**Description:** Provides an overview of the services integrated into the ID-UAM system, including account creation steps for different user types and details on obtaining accounts.

**Parameters:** None

**Outputs:**
- `service_account_information`: Information on services available for obtaining accounts, including steps for enrollment for new and existing students, staff, as well as non-UAM researchers, guests, and collaborators.
- `existing_student_information`: Information and details specifically for students who have already enrolled.

---

#### 🔧 Prompt For Password Setup

**Description:** Instructs users on how to establish a password for their account for the first time, including steps for obtaining a user identifier and activation code.

**Parameters:** None

**Outputs:**
- `account_creation_steps`: Steps for obtaining an ID-UAM account, including information about welcome messages and activation codes for creating a password.
- `user_support_contact_info`: Contact details for user support (CAU).

---

#### 🔧 Remind Password Change Frequency

**Description:** Reminds the user to change their password periodically to avoid account blocking.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Present Service Type Options

**Description:** Provides information about the services integrated into the ID-UAM system, including available options for account creation and other services.

**Parameters:** None

**Outputs:**
- `available_services`: Provides a list of services including account creation for students, account setup for new faculty and students, and integrated services in ID-UAM.

---

#### 🔧 List Available Services

**Description:** Lists the main types of services offered under ID-UAM for students and staff.

**Parameters:** None

**Outputs:**
- `available_services_list`: Services include account creation for first enrollment, accounts for students who have formalized their enrollment, and other account types for non-UAM researchers and collaborators.

---

#### 🔧 Provide First Time Enrollment Account Details

**Description:** Outlines details regarding obtaining a student account for first-time enrollment, including the need for a NIA and steps to generate a password or contact support if issues arise.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Password Reset Instructions

**Description:** Provides detailed instructions for resetting the ID-UAM account password, including obtaining and using an activation code.

**Parameters:** None

**Outputs:**
- `account_instructions`: Instructions for obtaining account details for first-time registration and guidance for existing students, personnel, and other account inquiries along with contact details for assistance.

---


### 📂 Chatbot Meta (2 functions)

#### 🔧 Prompt For Reformulated Question

**Description:** The chatbot asks the user to reformulate their question in other words or suggests consulting a catalog of services.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Service Ticket Submission

**Description:** The chatbot advises the user to open a ticket at the CAU for queries related to IT services, detailing how to do so.

**Parameters:** None

**Outputs:** None

---


### 📂 General Information (3 functions)

#### 🔧 Provide Virtual Platform Contact Info

**Description:** Provides the contact information for the Office of Student Services regarding inquiries about virtual platforms.

**Parameters:** None

**Outputs:**
- `email_contact`: Email address for contact.
- `phone_contact`: Phone number for contact.
- `physical_location`: Address of the Office of Student Services.
- `service_hours`: Hours of operation for the service.
- `faqs_link`: Link to frequently asked questions regarding the service.
- `services_catalog_link`: Link to the catalog of services offered.

---

#### 🔧 Provide Contact Information For Support

**Description:** Provides users with comprehensive contact information for user support, including email, phone, and physical location, along with operational hours and relevant links for further assistance.

**Parameters:** None

**Outputs:**
- `contact_information`: Email: cau@uam.es; Phone: 914974029; Physical address: Escuela Politécnica Superior, Edificio B, Calle Francisco Tomás y Valiente n° 11, Campus Cantoblanco, 28049 Madrid.
- `support_hours`: Support hours are Monday to Friday, 9:00h to 17:30h (except holidays), with reduced hours during UAM labor suspension periods: Monday to Friday, 9:00h to 14:00h.
- `faq_link`: Link to the frequently asked questions.
- `services_catalog_link`: Link to the services catalog.

---

#### 🔧 Repeat Contact Information For Cau

**Description:** The chatbot repeats the detailed contact information for the CAU upon user request regarding service catalogs.

**Parameters:** None

**Outputs:**
- `contact_methods`: Email, phone, and physical address of CAU
- `operational_hours`: Detailed hours of operation for CAU services

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
| Total LLM Calls | 886 |
| Successful Calls | 886 |
| Failed Calls | 0 |
| Total Tokens | 1,204,777 |
| Estimated Cost | $0.7702 USD |
| Execution Time | 00:55:38 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 979,392 | 12,223 | 991,615 | $0.6170 |
| Analysis | 199,088 | 14,074 | 213,162 | $0.1532 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

