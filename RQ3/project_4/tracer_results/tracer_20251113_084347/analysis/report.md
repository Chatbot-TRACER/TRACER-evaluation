# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **12 functionalities** discovered across **3 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Appointment Scheduling** (3 functions)
- *Prompt For Appointment Selection*: Prompts the user to select a type of appointment from available options.
- *Provide Mayor Appointment Info*: Provides information on how to request a mayor's appointment, including avail...
- *Provide Urbanism Appointment Info*: Provides detailed information on how to schedule an appointment with the Urba...

**📂 Customer Support** (7 functions)
- *List Main Services*: Provides information about the main services offered by the Ayuntamiento de M...
- *Provide Complaint Submission Information*: Informs the user about the process to submit a complaint or claim, including ...
- *Provide Municipal Corporation Information*: The chatbot provides information about the current government team and munici...
- *Provide Tax Payment Deadlines*: The chatbot informs the user about the deadlines for paying municipal taxes b...
- *Provide Contact Information For Sae*: Provides details on how to contact the Servicio Andaluz de Empleo (SAE) throu...
- *...and 2 more functions*

**📂 User Authentication** (2 functions)
- *Prompt For Identification Access*: Asks the user to access the electronic identification process for making onli...
- *Present Electronic Headquarters Link*: Provides the user with a link to access the electronic headquarters or office...

## 🗂️ Functionality Details

### 📂 Appointment Scheduling (3 functions)

#### 🔧 Prompt For Appointment Selection

**Description:** Prompts the user to select a type of appointment from available options.

**Parameters:**
- `selected_appointment_type`: Represents the choice of appointment the user wants to schedule *Options: `Cita con el alcalde`, `Cita con Urbanismo`, `Cita con el SAC`*

**Outputs:**
- `appointment_options`: Options for types of appointments (Cita con el alcalde, Cita con Urbanismo, Cita con el SAC)

**Parent Functions:** `List Main Services`

**Child Functions:**
- `Provide Mayor Appointment Info`: Provides information on how to request a mayor's appointment, including available scheduling methods.
- `Provide Urbanism Appointment Info`: Provides detailed information on how to schedule an appointment with the Urbanism department, including methods and location details.

---

#### 🔧 Provide Mayor Appointment Info

**Description:** Provides information on how to request a mayor's appointment, including available scheduling methods.

**Parameters:** None

**Outputs:**
- `appointment_request_methods`: Includes options for requesting appointments either online through the electronic headquarters or in person at the Citizen Attention Service (SAC).

**Parent Functions:** `Prompt For Appointment Selection`

**Child Functions:**
- `Prompt For Identification Access`: Asks the user to access the electronic identification process for making online appointments by directing them to the relevant website.

---

#### 🔧 Provide Urbanism Appointment Info

**Description:** Provides detailed information on how to schedule an appointment with the Urbanism department, including methods and location details.

**Parameters:** None

**Outputs:**
- `appointment_scheduling_methods`: Methods for scheduling an appointment, which includes electronic platforms, phone, or in-person visits, along with location details of the Urbanism department.
- `department_location`: The physical address of the Urbanism department for in-person visits: Edificio de las Filipenses, calle Cantarranas, número 33, Morón de la Frontera.

**Parent Functions:** `Prompt For Appointment Selection`

---


### 📂 Customer Support (7 functions)

#### 🔧 List Main Services

**Description:** Provides information about the main services offered by the Ayuntamiento de Morón de la Frontera, including hours and methods for making appointments.

**Parameters:** None

**Outputs:**
- `service_availability`: Details on in-person and phone assistance hours
- `appointment_methods`: Describes methods for scheduling appointments (online, phone, in-person)

**Child Functions:**
- `Prompt For Appointment Selection`: Prompts the user to select a type of appointment from available options.

---

#### 🔧 Provide Complaint Submission Information

**Description:** Informs the user about the process to submit a complaint or claim, including instructions for filling out a General Instance and options for submission methods, both in-person and online.

**Parameters:** None

**Outputs:**
- `submission_methods`: Options for submitting a complaint, including in-person at the Registry and online through the Electronic Headquarters with a digital certificate. Provides instructions and information on how to submit complaints or claims electronically as well as specific requirements.
- `electronic_headquarters_link`: URL for accessing the Electronic Headquarters for submissions.

---

#### 🔧 Provide Municipal Corporation Information

**Description:** The chatbot provides information about the current government team and municipal groups represented in the Ayuntamiento.

**Parameters:** None

**Outputs:**
- `municipal_government_info`: Details about the ruling party and other represented groups, along with a link to the municipal corporation information.

---

#### 🔧 Provide Tax Payment Deadlines

**Description:** The chatbot informs the user about the deadlines for paying municipal taxes based on different fractions and types of taxes.

**Parameters:** None

**Outputs:**
- `tax_payment_deadlines`: Specific dates for tax payments.

---

#### 🔧 Provide Contact Information For Sae

**Description:** Provides details on how to contact the Servicio Andaluz de Empleo (SAE) through various channels, including information on scheduling appointments and service hours.

**Parameters:** None

**Outputs:**
- `service_hours`: Information about operating hours for in-person and telephone services.
- `appointment_scheduling`: Instructions on how to schedule an appointment, including options via electronic office, phone, in-person, and telephone methods.

---

#### 🔧 Provide Basic Information About Unemployment Services

**Description:** The chatbot provides guidance and information regarding types of assistance available for individuals in unemployment situations and directs them to appropriate services.

**Parameters:** None

**Outputs:**
- `unemployment_assistance_info`: Information about the types of assistance available for unemployed individuals, including guidance on services from the Servicio Andaluz de Empleo and options for evaluating existing circumstances regarding unemployment support.
- `contact_information`: Details on how to contact the SAE and the central office for further assistance.

---

#### 🔧 Present Ayuntamiento Website Link

**Description:** Provides a direct link to the Ayuntamiento's website for additional information.

**Parameters:** None

**Outputs:**
- `website_link`: Direct URL to the Ayuntamiento's website.

---


### 📂 User Authentication (2 functions)

#### 🔧 Prompt For Identification Access

**Description:** Asks the user to access the electronic identification process for making online appointments by directing them to the relevant website.

**Parameters:** None

**Outputs:** None

**Parent Functions:** `Provide Mayor Appointment Info`

**Child Functions:**
- `Present Electronic Headquarters Link`: Provides the user with a link to access the electronic headquarters or office of the Ayuntamiento.

---

#### 🔧 Present Electronic Headquarters Link

**Description:** Provides the user with a link to access the electronic headquarters or office of the Ayuntamiento.

**Parameters:** None

**Outputs:**
- `electronic_office_link`: URL to the electronic office headquarters site for the Ayuntamiento.

**Parent Functions:** `Prompt For Identification Access`

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
| Total LLM Calls | 729 |
| Successful Calls | 729 |
| Failed Calls | 0 |
| Total Tokens | 736,609 |
| Estimated Cost | $0.4691 USD |
| Execution Time | 00:39:51 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 613,989 | 7,972 | 621,961 | $0.3875 |
| Analysis | 107,535 | 7,113 | 114,648 | $0.0816 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

