# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **12 functionalities** discovered across **2 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Account & Access** (5 functions)
- *Prompt For Password Change*: Guides the user through options and steps to change their account password, i...
- *Provide Password Change Instructions*: Provides detailed instructions for changing the password and acquiring the ac...
- *Prompt For Identifier Recovery*: Prompts the user for assistance in recovering their identifier if they have f...
- *Prompt For Password Setup*: Prompts the user with guidelines and steps to establish a password for the fi...
- *List Services Integrated In Id Uam*: Lists and describes the services available under the ID-UAM system for studen...

**📂 General Information** (7 functions)
- *Provide Contact Information*: The chatbot provides the contact information for the Centro de Atención a Usu...
- *Prompt For Services Catalog Access*: Prompts the user to access the catalog of services offered by CAU.
- *Prompt For Frequently Asked Questions Info*: Prompts the user to consult frequently asked questions about CAU services, pr...
- *Provide Initial Information On Virtual Platforms*: Provides information on where to find help regarding UAM's virtual platforms ...
- *Prompt For Moodle Access Issue*: Asks the user for clarification on the specific access issue related to Moodle.
- *...and 2 more functions*

## 🗂️ Functionality Details

### 📂 Account & Access (5 functions)

#### 🔧 Prompt For Password Change

**Description:** Guides the user through options and steps to change their account password, including instructions for those who have forgotten their user ID or possess a valid activation code.

**Parameters:** None

**Outputs:**
- `password_change_instructions`: Instructions on obtaining an activation code and changing the password, including steps to generate and use the activation code based on user status.
- `contact_information`: Details for contacting the CAU for further assistance, including email and phone number for user support.
- `password_change_reminder`: Reminder to change the password periodically.

---

#### 🔧 Provide Password Change Instructions

**Description:** Provides detailed instructions for changing the password and acquiring the activation code for the user's account.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Identifier Recovery

**Description:** Prompts the user for assistance in recovering their identifier if they have forgotten it, including providing further instructions.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Password Setup

**Description:** Prompts the user with guidelines and steps to establish a password for the first time during student enrollment or personnel incorporation, including contact information for support.

**Parameters:** None

**Outputs:**
- `password_establishment`: Steps to establish a password for first-time enrollment or for existing students.
- `contact_information`: Email and contact number for user support (CAU).

---

#### 🔧 List Services Integrated In Id Uam

**Description:** Lists and describes the services available under the ID-UAM system for students and personnel, including account creation, account information, and related assistance.

**Parameters:** None

**Outputs:**
- `account_services`: Services related to user accounts, including account creation for new students, obtaining accounts for already enrolled students, password recovery, activation codes, and access for staff and other personnel. This also includes information on obtaining accounts for students, staff, non-UAM personnel, or external collaborators.
- `contact_information`: Details on how to contact CAU for further assistance, including email and contact number for user support.

---


### 📂 General Information (7 functions)

#### 🔧 Provide Contact Information

**Description:** The chatbot provides the contact information for the Centro de Atención a Usuarios (CAU) upon request, including email, phone, physical address, service hours, and relevant links.

**Parameters:** None

**Outputs:**
- `contact_email`: Email address for CAU.
- `contact_phone`: Phone number for CAU.
- `contact_address`: Physical address of CAU.
- `service_hours`: Normal and special operating hours for CAU.
- `frequently_asked_questions_link`: Link to frequently asked questions.
- `services_catalog_link`: Link to the catalog of services provided.

---

#### 🔧 Prompt For Services Catalog Access

**Description:** Prompts the user to access the catalog of services offered by CAU.

**Parameters:** None

**Outputs:**
- `services_catalog_link`: Link to the catalog of services provided

---

#### 🔧 Prompt For Frequently Asked Questions Info

**Description:** Prompts the user to consult frequently asked questions about CAU services, providing relevant contact information and easy access to FAQs.

**Parameters:** None

**Outputs:**
- `contact_information`: Contact methods including email, phone number, and physical address for CAU.
- `service_hours`: Details on operational hours for CAU services.
- `faq_links`: Links to frequently asked questions and the catalog of services offered by CAU.

---

#### 🔧 Provide Initial Information On Virtual Platforms

**Description:** Provides information on where to find help regarding UAM's virtual platforms and Moodle.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Moodle Access Issue

**Description:** Asks the user for clarification on the specific access issue related to Moodle.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Moodle Access Requirements

**Description:** Provides information about the requirements needed to access Moodle, including the need for an institutional account and details about the available Moodle environments.

**Parameters:** None

**Outputs:**
- `access_requirements`: Information about needing an institutional account and details about Moodle environments.

---

#### 🔧 Prompt For Services Integrated In Id Uam

**Description:** Provides links and information about the services integrated into ID-UAM, prompting users to explore further.

**Parameters:** None

**Outputs:**
- `services_list`: Services offered include obtaining student accounts for initial enrollment, accounts for existing students and new UAM staff, and various other types of accounts, along with links to information about integrated services available through ID-UAM.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Por favor, ¿me lo puedes decir con otras palabras? o, si lo prefieres, puedes consultar nuestro catálogo de servicios. Respondo a preguntas dirigidas al Centro de Atención a Usuarios del servicio de Tecnologías de la Información.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 884 |
| Successful Calls | 884 |
| Failed Calls | 0 |
| Total Tokens | 1,214,874 |
| Estimated Cost | $0.7741 USD |
| Execution Time | 00:54:21 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 944,718 | 13,386 | 958,104 | $0.5990 |
| Analysis | 245,086 | 11,684 | 256,770 | $0.1751 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

