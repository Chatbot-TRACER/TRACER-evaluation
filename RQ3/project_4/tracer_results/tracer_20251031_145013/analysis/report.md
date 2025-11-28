# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **13 functionalities** discovered across **0 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📄 Uncategorized** (13 functions)
- *Provide Public Attention Hours*: States the usual public attention hours for the Ayuntamiento and notes variat...
- *Provide Cita Sac Information*: Provides specific information on how to book an appointment with the SAC, inc...
- *Prompt For Cita Selection*: "Prompts the user to select an appointment type from available options for sc...
- *Provide Cita Con Urbanismo Information*: Provides details on how to schedule an appointment with the Urbanism departme...
- *Provide Urbanism Appointment Information*: Supplies the user with details on how to schedule an appointment with the Urb...
- *...and 8 more functions*

## 🗂️ Functionality Details

### 📄 Uncategorized (13 functions)

#### 🔧 Provide Public Attention Hours

**Description:** States the usual public attention hours for the Ayuntamiento and notes variations for holiday periods.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Cita Sac Information

**Description:** Provides specific information on how to book an appointment with the SAC, including multiple methods.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Cita Selection

**Description:** "Prompts the user to select an appointment type from available options for scheduling with different departments."

**Parameters:**
- `selected_cita`: User's choice of appointment type. *Options: `cita_con_el_alcalde`, `cita_con_urbanismo`, `cita_con_el_sac`*

**Outputs:** None

---

#### 🔧 Provide Cita Con Urbanismo Information

**Description:** Provides details on how to schedule an appointment with the Urbanism department including contact methods.

**Parameters:** None

**Outputs:**
- `available_buttons`: Options for scheduling appointments presented as buttons.

**Child Functions:**
- `Provide Urbanism Appointment Information`: Supplies the user with details on how to schedule an appointment with the Urbanism department, including electronic, phone, and in-person methods.

---

#### 🔧 Provide Urbanism Appointment Information

**Description:** Supplies the user with details on how to schedule an appointment with the Urbanism department, including electronic, phone, and in-person methods.

**Parameters:** None

**Outputs:**
- `appointment_methods`: Methods to schedule an appointment include the electronic headquarters, phone, and in-person visit details.

---

#### 🔧 `Provide Services Information`

**Description:** "Provides information about the services offered by the Ayuntamiento de Morón de la Frontera, including details on how to contact specific departments and request appointments."

**Parameters:** None

**Outputs:**
- `urbanism_appointment_info`: Information on how to request an appointment with urbanism technicians.
- `citizen_attention_service_info`: Details on the hours and methods of contacting the citizen attention service.
- `urban_transport_service_info`: Information about the urban transport service, including details for pensioners.
- `social_services_contact_info`: Information on how to contact the Department of Social Services, including phone number for appointment booking.
- `social_services_specific_info`: Details about the registration of domestic partnerships as a specific service within the Department of Social Services.

---

#### 🔧 `Access Electronic Headquarters`

**Description:** "Provides the user with access to the electronic headquarters for scheduling appointments."

**Parameters:** None

**Outputs:**
- `electronic_headquarters_link`: Link to the Ayuntamiento's electronic headquarters for scheduling appointments: https://morondelafrontera.sedelectronica.es/.

---

#### 🔧 `Provide Electronic Identification Link`

**Description:** "Provides the user with a link to access the electronic identification process for scheduling appointments."

**Parameters:** None

**Outputs:**
- `electronic_identification_link`: URL for accessing the electronic identification process.

---

#### 🔧 Prompt For Alternate Question Rephrasing

**Description:** Asks the user to rephrase their question if not understood clearly.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Provide Service Department Contact Info

**Description:** Provides information on how to contact specific departments and the service hours for in-person and telephone assistance.

**Parameters:** None

**Outputs:**
- `service_contact_details`: Information on contacting departments for specific inquiries and their operating hours.

---

#### 🔧 `Introduce Chatbot Services`

**Description:** "Informs the user that the chatbot is part of the citizen service team and invites queries related to their needs."

**Parameters:** None

**Outputs:** None

---

#### 🔧 Present Service Type Options

**Description:** Provides the user with distinct service options available from the Ayuntamiento.

**Parameters:** None

**Outputs:**
- `service_type_options`: Available services include in-person appointments, service hours, and contact numbers.

---

#### 🔧 Provide Service Details For Appointment

**Description:** Responds with information regarding the availability and schedule for in-person appointments at the Ayuntamiento.

**Parameters:** None

**Outputs:** None

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
| Total LLM Calls | 804 |
| Successful Calls | 804 |
| Failed Calls | 0 |
| Total Tokens | 698,758 |
| Estimated Cost | $0.4490 USD |
| Execution Time | 00:41:23 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 611,058 | 7,913 | 618,971 | $0.3856 |
| Analysis | 71,184 | 8,603 | 79,787 | $0.0634 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

