# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **16 functionalities** discovered across **3 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Account & Access** (3 functions)
- *Prompt For Password Change*: Provides step-by-step instructions for changing the password, including obtai...
- *Prompt For First Time Password Setup*: Guides the user through the process of establishing their password for the fi...
- *Provide Account And Services Information*: Offers comprehensive details about account setup options and integrated servi...

**📂 General Information** (11 functions)
- *List Frequently Asked Questions*: The chatbot indicates the availability of frequently asked questions related ...
- *Provide Service Catalog And Contact Info*: Offers users access to the service catalog of the Centro de Atención a Usuari...
- *Provide Student Support Service Info*: Provides information about available student counseling and support services ...
- *Provide Information On Virtual Platforms*: Provides information about contacting the Oficina de Atención al Estudiante f...
- *Provide University Information*: Provides general information about the Universidad Autónoma de Madrid, coveri...
- *...and 6 more functions*

**📂 Network & Connectivity** (2 functions)
- *Present Vpn Setup Options*: Offers options and links for installing and configuring VPN for remote access...
- *Provide Vpn Installation Guide*: Provides detailed instructions for installing and configuring the GlobalProte...

## 🗂️ Functionality Details

### 📂 Account & Access (3 functions)

#### 🔧 Prompt For Password Change

**Description:** Provides step-by-step instructions for changing the password, including obtaining an activation code if necessary.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For First Time Password Setup

**Description:** Guides the user through the process of establishing their password for the first time, including necessary steps and requirements.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Account And Services Information

**Description:** Offers comprehensive details about account setup options and integrated services within ID-UAM for students, staff, and external users.

**Parameters:** None

**Outputs:**
- `services_description`: Details the services available through ID-UAM, such as account creation and support options for new students and staff.

---


### 📂 General Information (11 functions)

#### 🔧 List Frequently Asked Questions

**Description:** The chatbot indicates the availability of frequently asked questions related to the CAU.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Service Catalog And Contact Info

**Description:** Offers users access to the service catalog of the Centro de Atención a Usuarios along with contact details, operating hours, and links to frequently asked questions.

**Parameters:** None

**Outputs:**
- `email_contact`: Email contact for Centro de Atención a Usuarios at cau@uam.es for inquiries.
- `phone_contact`: Phone contact at 914974029 for Centro de Atención a Usuarios inquiries.
- `physical_address`: Physical address at Escuela Politécnica Superior, Edificio B, Calle Francisco Tomás y Valiente n° 11, Campus Cantoblanco, 28049 Madrid for in-person contact.
- `operating_hours`: Regular operating hours from Monday to Friday, 9:00h to 17:30h (excluding holidays) and reduced hours from Monday to Friday, 9:00h to 14:00h during non-working periods.
- `service_catalog_link`: Consult the CATÁLOGO DE SERVICIOS OFRECIDOS, including the link to the catalog of IT services.
- `faq_link`: Link to frequently asked questions (preguntas frecuentes) regarding Centro de Atención a Usuarios.

---

#### 🔧 Provide Student Support Service Info

**Description:** Provides information about available student counseling and support services offered at the university, including the Centro de Psicología Aplicada and other related units.

**Parameters:** None

**Outputs:**
- `service_details`: Information about the Centro de Psicología Aplicada (CPA) and associated services, including details on student support and consultations.

---

#### 🔧 Provide Information On Virtual Platforms

**Description:** Provides information about contacting the Oficina de Atención al Estudiante for inquiries related to virtual platforms and directs the user to relevant resources.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide University Information

**Description:** Provides general information about the Universidad Autónoma de Madrid, covering its commitment to student education and details on available programs and faculties.

**Parameters:** None

**Outputs:**
- `university_offerings`: An overview of the university's offerings, including degrees, programs available, and the university's commitment to student training.

---

#### 🔧 Present Options For Future Students

**Description:** Lists options and relevant links for future students considering the university.

**Parameters:** None

**Outputs:**
- `future_student_options`: Includes links for DÍA DE BIENVENIDA, Grados Universitarios, and Vida Universitaria.

---

#### 🔧 Provide Préstamo Info

**Description:** Informs the user about the availability and process for borrowing laptops from the university libraries.

**Parameters:** None

**Outputs:**
- `préstamo_info`: Details on where and how to access laptop loans.

---

#### 🔧 Provide Library Access Info

**Description:** Provides information on accessing library resources and necessary user identification for accessing services.

**Parameters:** None

**Outputs:**
- `library_access_info`: Guidelines on accessing library resources remotely, including the requirement for VPN.

---

#### 🔧 Present Faculty And Programs Overview

**Description:** Presents an overview of the faculties and schools available at the university along with information on programs and degrees offered.

**Parameters:** None

**Outputs:**
- `available_faculties_overview`: Overview of faculties and educational programs offered at the university.

---

#### 🔧 Provide Admission And Registration Info

**Description:** Informs the user about the registration process and directs them to the appropriate school's or faculty's official webpage for detailed information.

**Parameters:** None

**Outputs:**
- `admission_info`: General information on the admission process and registration for programs.

---

#### 🔧 Guide On Moodle Access

**Description:** Informs the user about the need for an institutional account to access Moodle and outlines the different Moodle environments available.

**Parameters:** None

**Outputs:**
- `moodle_environment_options`: Describes the different Moodle environments available, including Grado, Postgrado, and Formación.

---


### 📂 Network & Connectivity (2 functions)

#### 🔧 Present Vpn Setup Options

**Description:** Offers options and links for installing and configuring VPN for remote access to university services.

**Parameters:** None

**Outputs:**
- `vpn_setup_options`: Lists different guides available for setting up VPN on various operating systems.

---

#### 🔧 Provide Vpn Installation Guide

**Description:** Provides detailed instructions for installing and configuring the GlobalProtect VPN client based on the user's device operating system.

**Parameters:**
- `selected_os`: Represents the operating system the user will use for VPN installation. *Options: `Windows`, `MacOS`, `IOS`, `Android`, `Linux`*

**Outputs:**
- `installation_guides`: Links to specific installation guides for each operating system.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
¿Me puedes repetir la pregunta con otras palabras? o, si lo prefieres, puedes consultar nuestro\ncatálogo de servicios\n.\nRespondo a preguntas dirigidas al\nCentro de Atención a Usuarios del servicio de Tecnologías de la Información.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 900 |
| Successful Calls | 900 |
| Failed Calls | 0 |
| Total Tokens | 1,029,602 |
| Estimated Cost | $0.6698 USD |
| Execution Time | 00:54:36 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 784,997 | 13,782 | 798,779 | $0.5041 |
| Analysis | 215,702 | 15,121 | 230,823 | $0.1657 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

