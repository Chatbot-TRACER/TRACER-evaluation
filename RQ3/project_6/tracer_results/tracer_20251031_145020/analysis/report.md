# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **11 functionalities** discovered across **4 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Access Information** (2 functions)
- *Provide Access Instructions To Virtual Tax Office*: Provides instructions on how to access the Virtual Tax Office and includes a ...
- *Present Office Location Information*: Presents information about various offices of the Tax Management Service, inc...

**📂 Chatbot Meta** (2 functions)
- *Prompt For Reframed Inquiry*: Asks the user to rephrase their question for better understanding.
- *Provide Main Functions Overview*: Outlines the primary services and support the chatbot offers regarding tax ma...

**📂 Payment Information** (4 functions)
- *Provide Payment Methods*: Provides detailed options for paying receipts, including various methods and ...
- *Provide Tax Payment Information*: Informs users about tax payment schedules, methods, and how to access them th...
- *Provide Fraccionamiento Information*: Informs users about the possibility of requesting a split payment for amounts...
- *Provide Tax Payment Methods*: Informs the user of the available methods for paying taxes and provides detai...

**📂 Tax Information** (3 functions)
- *Provide Fiscal Calendar Information*: Provides information about accessing the fiscal calendar and resources relate...
- *Present Tax Calendar Link*: Provides a link to the tax calendar page in the Virtual Tax Office for furthe...
- *Provide Tax Information*: Informs the user about the types of tributes or taxes managed by the Diputaci...

## 🗂️ Functionality Details

### 📂 Access Information (2 functions)

#### 🔧 Provide Access Instructions To Virtual Tax Office

**Description:** Provides instructions on how to access the Virtual Tax Office and includes a clickable link for the user.

**Parameters:** None

**Outputs:**
- `access_link`: Clickable link to the Virtual Tax Office.

---

#### 🔧 Present Office Location Information

**Description:** Presents information about various offices of the Tax Management Service, including their hours of operation and a clickable link for further details.

**Parameters:** None

**Outputs:**
- `office_location_details`: Information about the different offices, their locations, and hours of operation.
- `office_location_link`: URL to the office location details.

---


### 📂 Chatbot Meta (2 functions)

#### 🔧 Prompt For Reframed Inquiry

**Description:** Asks the user to rephrase their question for better understanding.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Main Functions Overview

**Description:** Outlines the primary services and support the chatbot offers regarding tax management inquiries.

**Parameters:** None

**Outputs:** None

---


### 📂 Payment Information (4 functions)

#### 🔧 Provide Payment Methods

**Description:** Provides detailed options for paying receipts, including various methods and collaborating entities.

**Parameters:** None

**Outputs:**
- `payment_methods`: A detailed overview of available payment methods, including collaborating entities, Correos Pay, electronic headquarters options with card or BIZUM, and bank domiciliation within SEPA.

---

#### 🔧 Provide Tax Payment Information

**Description:** Informs users about tax payment schedules, methods, and how to access them through the Virtual Tax Office, along with providing assistance contact information.

**Parameters:** None

**Outputs:**
- `tax_payment_schedule_info`: Information on when to pay taxes and rates, including details for accessing tax payment schedules through the Virtual Tax Office, payment methods, and contact details for support.
- `contact_information`: Phone number for assistance.

---

#### 🔧 Provide Fraccionamiento Information

**Description:** Informs users about the possibility of requesting a split payment for amounts that could not be seized from their account and suggests contacting offices for assistance.

**Parameters:** None

**Outputs:**
- `office_location_information`: Details of different offices of the Tax Management Service and their hours of operation available through the provided link.

---

#### 🔧 Provide Tax Payment Methods

**Description:** Informs the user of the available methods for paying taxes and provides detailed options for each method.

**Parameters:** None

**Outputs:**
- `payment_methods_info`: Users can pay in person, schedule appointments, or online via the Tax Virtual Office with a digital certificate or Cl@ve. This includes a comprehensive list of methods for paying taxes, detailing entities, electronic options, and bank domiciliation.
- `additional_information_link`: For more detailed information, users can consult the provided link regarding debt installment without guarantee.

---


### 📂 Tax Information (3 functions)

#### 🔧 Provide Fiscal Calendar Information

**Description:** Provides information about accessing the fiscal calendar and resources related to tribute management, including contact details for assistance.

**Parameters:** None

**Outputs:**
- `office_virtual_tributaria_info`: Information about accessing the Office Virtual Tributaria, including a contact phone number and details regarding the fiscal calendar and its relevance to tribute payments. It also includes access to the fiscal calendar through the Oficina Virtual Tributaria, with a URL link and assistance contact number.

---

#### 🔧 Present Tax Calendar Link

**Description:** Provides a link to the tax calendar page in the Virtual Tax Office for further user exploration related to tax payment deadlines.

**Parameters:** None

**Outputs:**
- `tax_calendar_link`: URL to the tax calendar page for direct access in the Virtual Tax Office.

---

#### 🔧 Provide Tax Information

**Description:** Informs the user about the types of tributes or taxes managed by the Diputación and directs them to the Virtual Tax Office for more details or offers a contact number for further assistance.

**Parameters:** None

**Outputs:**
- `available_tributos_info`: A list of types of tributes managed and collected.
- `contact_information`: The phone number for assistance.
- `tax_management_info`: Details about taxes managed by the Diputación and the methods for accessing that information.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Disculpa, pero... ¿Me lo puedes repetir con otras palabras? Respondo a preguntas sobre la <b>gestión de tributos</b>.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 814 |
| Successful Calls | 814 |
| Failed Calls | 0 |
| Total Tokens | 876,799 |
| Estimated Cost | $0.5555 USD |
| Execution Time | 00:43:08 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 755,095 | 8,264 | 763,359 | $0.4729 |
| Analysis | 105,385 | 8,055 | 113,440 | $0.0826 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

