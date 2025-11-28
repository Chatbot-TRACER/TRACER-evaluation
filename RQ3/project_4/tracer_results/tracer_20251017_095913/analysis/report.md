# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **13 functionalities** discovered across **11 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Appointment Options** (1 functions)
- *Present Cita Options*: The chatbot offers specific options to request an appointment with various de...

**📂 Appointments** (1 functions)
- *Provide Alcalde Appointment Info*: The chatbot explains how to request an appointment with the alcalde via the e...

**📂 Chatbot Meta** (1 functions)
- *Provide Service Assistance*: Introduces the chatbot as a civic service representative and prompts the user...

**📂 Contact Information** (1 functions)
- *Provide Contact Information*: Offers details about how to contact the Ayuntamiento for in-person and phone ...

**📂 General Information** (3 functions)
- *Present Link To Website*: Provides a link to the official website of the Ayuntamiento de Morón de la Fr...
- *Present Link To Corporation Info*: Provides a link to the information about the municipal corporation of Morón d...
- *Provide Government Info*: Provides information about the current governing body of the Ayuntamiento and...

**📂 Identification** (1 functions)
- *Provide Identification Info*: The chatbot provides a link for electronic identification required for access...

**📂 Job & Services Information** (1 functions)
- *List Services And Job Offers*: Provides information about available services and job offers from the Ayuntam...

**📂 Service Access** (1 functions)
- *Provide Access To Electronic Headquarters*: Provides the user with access to the electronic headquarters of the Ayuntamie...

**📂 Service Information** (1 functions)
- *Provide Sac Hours*: The chatbot provides standard hours for in-person citizen services and teleph...

**📂 Service Options** (1 functions)
- *Present Service Options*: The chatbot provides a list of available service options offered by the Ayunt...

**📂 Tax Information** (1 functions)
- *Provide Tax Payment Schedule*: Provides the user with information about the specific deadlines for tax payme...

## 🗂️ Functionality Details

### 📂 Appointment Options (1 functions)

#### 🔧 Present Cita Options

**Description:** The chatbot offers specific options to request an appointment with various departments.

**Parameters:** None

**Outputs:**
- `cita_options`: Cita con el alcalde, Cita con Urbanismo, Cita con el SAC

---


### 📂 Appointments (1 functions)

#### 🔧 Provide Alcalde Appointment Info

**Description:** The chatbot explains how to request an appointment with the alcalde via the electronic headquarters or in person.

**Parameters:** None

**Outputs:** None

---


### 📂 Chatbot Meta (1 functions)

#### 🔧 Provide Service Assistance

**Description:** Introduces the chatbot as a civic service representative and prompts the user for their service-related inquiry.

**Parameters:** None

**Outputs:** None

---


### 📂 Contact Information (1 functions)

#### 🔧 Provide Contact Information

**Description:** Offers details about how to contact the Ayuntamiento for in-person and phone assistance, including operating hours.

**Parameters:** None

**Outputs:** None

---


### 📂 General Information (3 functions)

#### 🔧 Present Link To Website

**Description:** Provides a link to the official website of the Ayuntamiento de Morón de la Frontera.

**Parameters:** None

**Outputs:**
- `website_link`: URL of the Ayuntamiento's official website.

---

#### 🔧 Present Link To Corporation Info

**Description:** Provides a link to the information about the municipal corporation of Morón de la Frontera.

**Parameters:** None

**Outputs:**
- `corporation_info_link`: URL for the municipal corporation information page.

---

#### 🔧 Provide Government Info

**Description:** Provides information about the current governing body of the Ayuntamiento and the political groups represented.

**Parameters:** None

**Outputs:**
- `governing_body_info`: Information about the current governing body, including details about the ruling party and represented political groups.

---


### 📂 Identification (1 functions)

#### 🔧 Provide Identification Info

**Description:** The chatbot provides a link for electronic identification required for accessing the electronic headquarters.

**Parameters:** None

**Outputs:**
- `identification_link`: URL to the identification portal

---


### 📂 Job & Services Information (1 functions)

#### 🔧 List Services And Job Offers

**Description:** Provides information about available services and job offers from the Ayuntamiento de Morón de la Frontera, including details on job requirements, selection procedures, and relevant service offerings.

**Parameters:** None

**Outputs:**
- `available_job_offers`: Details about job offers available, including information on job requirements, selection procedures, and links to job offers on the Ayuntamiento's website.
- `available_services`: Details of services available from the Ayuntamiento de Morón de la Frontera.

---


### 📂 Service Access (1 functions)

#### 🔧 Provide Access To Electronic Headquarters

**Description:** Provides the user with access to the electronic headquarters of the Ayuntamiento, including a URL link for municipal services.

**Parameters:** None

**Outputs:**
- `electronic_headquarters_link`: URL for the electronic headquarters of the Ayuntamiento.

---


### 📂 Service Information (1 functions)

#### 🔧 Provide Sac Hours

**Description:** The chatbot provides standard hours for in-person citizen services and telephone assistance.

**Parameters:** None

**Outputs:**
- `service_hours_info`: Details about regular and seasonal service hours for in-person and telephone services.

---


### 📂 Service Options (1 functions)

#### 🔧 Present Service Options

**Description:** The chatbot provides a list of available service options offered by the Ayuntamiento and how to access them.

**Parameters:** None

**Outputs:**
- `service_types`: Types of services offered such as in-person assistance, electronic service, and telephone assistance.
- `service_options`: Available service options including appointment with the SAC, service hours, and the phone number of the Town Hall.

---


### 📂 Tax Information (1 functions)

#### 🔧 Provide Tax Payment Schedule

**Description:** Provides the user with information about the specific deadlines for tax payments for municipal taxes.

**Parameters:** None

**Outputs:**
- `tax_payment_schedule`: Specific deadlines for tax payments per year.

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
| Total LLM Calls | 766 |
| Successful Calls | 766 |
| Failed Calls | 0 |
| Total Tokens | 684,677 |
| Estimated Cost | $0.4442 USD |
| Execution Time | 00:15:38 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 561,277 | 7,975 | 569,252 | $0.3559 |
| Analysis | 104,825 | 10,600 | 115,425 | $0.0883 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

