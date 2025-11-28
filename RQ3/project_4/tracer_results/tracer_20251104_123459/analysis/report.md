# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **11 functionalities** discovered across **10 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Chatbot Meta** (1 functions)
- *Provide General Assistance Context*: Introduces the chatbot as part of the municipal citizen service team and prom...

**📂 Civil Registry Information** (1 functions)
- *Provide Civil Registry Contact Info*: Provides the user with the location and contact information for the Civil Reg...

**📂 Contact Information** (2 functions)
- *Provide Contact Information*: Provides detailed information on how to contact Social Services and schedule ...
- *Direct User To Contact*: Informs the user that specific information is unavailable and directs them to...

**📂 Employment Information** (1 functions)
- *Provide Job Opportunities Info*: The chatbot informs the user about job opportunities and how to access job po...

**📂 General Information** (1 functions)
- *Provide Information On Events*: Provides information about the services available at the Ayuntamiento de Moró...

**📂 Government Information** (1 functions)
- *Provide Government Information*: Shares information about the municipal government, including details on polit...

**📂 Marriage Information** (1 functions)
- *Provide Civil Marriage Initiation Info*: Provides instructions and necessary contacts for initiating a civil marriage,...

**📂 Online Services** (1 functions)
- *Access Electronic Office*: Prompts the user to access the Sede Electrónica of the Ayuntamiento by provid...

**📂 Support Services** (1 functions)
- *Suggest Resources For Tax Payment Help*: Suggests resources and services for individuals facing financial difficulties...

**📂 Tax Information** (1 functions)
- *Provide Tax Payment Deadlines*: Provides information on the deadlines for paying municipal taxes.

## 🗂️ Functionality Details

### 📂 Chatbot Meta (1 functions)

#### 🔧 Provide General Assistance Context

**Description:** Introduces the chatbot as part of the municipal citizen service team and prompts the user to indicate their needs for assistance.

**Parameters:** None

**Outputs:** None

---


### 📂 Civil Registry Information (1 functions)

#### 🔧 Provide Civil Registry Contact Info

**Description:** Provides the user with the location and contact information for the Civil Registry or Registro Civil office.

**Parameters:** None

**Outputs:**
- `civil_registry_contact`: Address and contact numbers for the Civil Registry.

---


### 📂 Contact Information (2 functions)

#### 🔧 Provide Contact Information

**Description:** Provides detailed information on how to contact Social Services and schedule appointments with the Ayuntamiento, including service hours and available contact methods.

**Parameters:** None

**Outputs:**
- `contact_methods`: Information on how to get in touch with Social Services, including options for in-person visits, phone calls, and online appointments with relevant links.

---

#### 🔧 Direct User To Contact

**Description:** Informs the user that specific information is unavailable and directs them to an alternate contact method for further assistance.

**Parameters:** None

**Outputs:**
- `contact_info`: WhatsApp contact number provided for further queries on youth programs.

---


### 📂 Employment Information (1 functions)

#### 🔧 Provide Job Opportunities Info

**Description:** The chatbot informs the user about job opportunities and how to access job postings and application details.

**Parameters:** None

**Outputs:**
- `job_opportunities_info`: General information about job offers, including where to find them and application requirements.

---


### 📂 General Information (1 functions)

#### 🔧 Provide Information On Events

**Description:** Provides information about the services available at the Ayuntamiento de Morón de la Frontera but does not directly answer questions about specific events.

**Parameters:** None

**Outputs:** None

---


### 📂 Government Information (1 functions)

#### 🔧 Provide Government Information

**Description:** Shares information about the municipal government, including details on political parties and representation in the local governing body.

**Parameters:** None

**Outputs:**
- `municipal_government_info`: Information about the political parties, representation in the local government, and governing bodies.
- `available_buttons`: Includes options to access more information about the municipal corporation.
- `municipal_structure_link`: URL to details of the municipal corporation.

---


### 📂 Marriage Information (1 functions)

#### 🔧 Provide Civil Marriage Initiation Info

**Description:** Provides instructions and necessary contacts for initiating a civil marriage, including steps for registration and arrangements for the ceremony.

**Parameters:** None

**Outputs:**
- `civil_marriage_process`: Steps for filing marriage at the Civil Registry and contacting the municipal office for ceremony arrangements, including phone details.

---


### 📂 Online Services (1 functions)

#### 🔧 Access Electronic Office

**Description:** Prompts the user to access the Sede Electrónica of the Ayuntamiento by providing a link.

**Parameters:** None

**Outputs:**
- `electronic_office_link`: URL link to the Sede Electrónica for scheduling appointments and the Sede Electrónica of the Ayuntamiento.

---


### 📂 Support Services (1 functions)

#### 🔧 Suggest Resources For Tax Payment Help

**Description:** Suggests resources and services for individuals facing financial difficulties regarding tax payments, including providing information and contact details for relevant governmental organizations and social services.

**Parameters:** None

**Outputs:**
- `service_contact_info`: Information on available services such as contacting the Servicio Andaluz de Empleo (SAE) and guidance related to Social Services assistance.

---


### 📂 Tax Information (1 functions)

#### 🔧 Provide Tax Payment Deadlines

**Description:** Provides information on the deadlines for paying municipal taxes.

**Parameters:** None

**Outputs:**
- `tax_payment_deadlines`: Dates for the payment of municipal taxes and tax payment periods based on type.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Me temo que no tengo la información para poder responder a su pregunta. Por favor, hágala por WhatsApp al número 744 48 12 52. Gracias.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 722 |
| Successful Calls | 722 |
| Failed Calls | 0 |
| Total Tokens | 675,420 |
| Estimated Cost | $0.4409 USD |
| Execution Time | 00:41:36 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 566,120 | 11,541 | 577,661 | $0.3674 |
| Analysis | 89,503 | 8,256 | 97,759 | $0.0735 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

