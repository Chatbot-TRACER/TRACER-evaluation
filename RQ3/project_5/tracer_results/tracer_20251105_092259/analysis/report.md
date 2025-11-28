# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **22 functionalities** discovered across **13 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Appointment Details** (1 functions)
- *Prompt For Appointment Details*: The chatbot prompts the user for further details when scheduling an appointme...

**📂 Appointment Scheduling** (5 functions)
- *Provide Appointment Information For Councillor*: Informs users about how to request an appointment with a councillor and provi...
- *Present Appointment Booking Options*: Presents users with various methods for booking appointments, including onlin...
- *Schedule Cita Previa*: Provides information and options for scheduling a prior appointment (cita pre...
- *Link To Certificate Appointment*: Provides a direct link for scheduling an appointment to obtain a digital cert...
- *Present Service Type Options*: Presents available appointment types that can be requested.

**📂 Contact Information** (1 functions)
- *Provide Library Contact Info*: Provides the contact information for the Biblioteca de Arucas, including phon...

**📂 Contact Options** (2 functions)
- *Present Available Contact Options*: Presents a list of contact categories available for the user to choose from.
- *Provide Service Contact Options*: Provides different communication channels available for requesting appointments.

**📂 Department Selection** (1 functions)
- *Prompt For Department Selection*: Prompts the user to select a specific department for scheduling appointments ...

**📂 Documentation Requirements** (2 functions)
- *Provide Model Communication Previa Details*: Relays the requirement for the model of Communication Previa and documentatio...
- *Request Documents For Submission*: Requests and clarifies the documents needed for the submission of the communi...

**📂 Electronic Submission** (1 functions)
- *Provide Electronic Submission Guidelines*: Informs the user on how to submit the communication request electronically, i...

**📂 Guidance** (2 functions)
- *Provide Communication Request Guidance*: Provides comprehensive guidance on submitting a communication request for con...
- *Provide Appointment Video Link*: Provides a link to a video that explains how to book or request an appointment.

**📂 Information Access** (2 functions)
- *Provide Urbanism Service Information*: Provides the user with a link to access information about the urbanism depart...
- *Provide Subsidiary Norms Information*: Provides the user with a link to access the subsidiary norms of Arucas.

**📂 Navigation** (1 functions)
- *Present Sede Electronica Link*: Provides a direct link to access the Sede Electrónica for appointment schedul...

**📂 Payment** (1 functions)
- *Provide Icio Payment Information*: Provides information regarding the ICIO payment process, including payment de...

**📂 Request Processing** (2 functions)
- *Prompt For Urbanism Request Details*: Prompts the user for necessary details to submit a request for an urbanism co...
- *Prompt For Appointment Request Methods*: Prompts the user for information on how to request an appointment with the re...

**📂 User Authentication** (1 functions)
- *Provide Digital Certificate Information*: Explains what a digital certificate is, the process to acquire one, and how i...

## 🗂️ Functionality Details

### 📂 Appointment Details (1 functions)

#### 🔧 Prompt For Appointment Details

**Description:** The chatbot prompts the user for further details when scheduling an appointment with different departments, specifying the need to provide context for the request.

**Parameters:**
- `context_of_request`: Description of the reason for the appointment; property_reference: Reference details about a property or parcel
- `if applicable; case_number`: Number of any ongoing case related to the appointment.

**Outputs:** None

---


### 📂 Appointment Scheduling (5 functions)

#### 🔧 Provide Appointment Information For Councillor

**Description:** Informs users about how to request an appointment with a councillor and provides a direct link to the relevant service.

**Parameters:** None

**Outputs:**
- `council_member_appointment_link`: Direct link for requesting an appointment with a council member.

---

#### 🔧 Present Appointment Booking Options

**Description:** Presents users with various methods for booking appointments, including online and phone scheduling, along with necessary details for each department.

**Parameters:** None

**Outputs:**
- `appointment_services`: Lists the departments for scheduling appointments, such as Urbanism and Intervention, detailing methods for booking appointments, including online and phone options along with required information for each department.

---

#### 🔧 Schedule Cita Previa

**Description:** Provides information and options for scheduling a prior appointment (cita previa) through various channels.

**Parameters:** None

**Outputs:**
- `cita_previa_information`: Information on scheduling cita previa through various methods such as phone, mobile app, or online, including detailed contact numbers and website links.

---

#### 🔧 Link To Certificate Appointment

**Description:** Provides a direct link for scheduling an appointment to obtain a digital certificate.

**Parameters:** None

**Outputs:**
- `digital_certificate_appointment_link`: URL for booking an appointment for the digital certificate accreditation.

---

#### 🔧 Present Service Type Options

**Description:** Presents available appointment types that can be requested.

**Parameters:** None

**Outputs:**
- `appointment_type_options`: Types of appointments available include 'Cita previa para acreditar un certificado digital', 'Cita previa con el Departamento de Intervención', 'Cita previa con el Servicio Canario de Empleo (SCE)', 'Cita previa con el Departamento de urbanismo/oficina técnica', 'Cita previa con un concejal o concejala'.

---


### 📂 Contact Information (1 functions)

#### 🔧 Provide Library Contact Info

**Description:** Provides the contact information for the Biblioteca de Arucas, including phone number and email address.

**Parameters:** None

**Outputs:**
- `library_contact_phone`: Phone number for the Biblioteca de Arucas.
- `library_contact_email`: Email address for the Biblioteca de Arucas.

---


### 📂 Contact Options (2 functions)

#### 🔧 Present Available Contact Options

**Description:** Presents a list of contact categories available for the user to choose from.

**Parameters:** None

**Outputs:**
- `contact_categories`: Contact categories include Centro de Salud, Biblioteca, Formulario de Contacto (Ayuntamiento), Teléfonos de interés, Oficina de Desarrollo Local, Dpto. de Intervención, Servicio Municipal de Participación Ciudadana, Casa de la Cultura, Patrimonio Histórico, Oficina de Recaudación, Unidad de Atención a las Drogodependencias.

---

#### 🔧 Provide Service Contact Options

**Description:** Provides different communication channels available for requesting appointments.

**Parameters:** None

**Outputs:**
- `communication_channel_options`: Options for contacting services include phone calls, mobile application usage, or online booking through electronic platforms.

---


### 📂 Department Selection (1 functions)

#### 🔧 Prompt For Department Selection

**Description:** Prompts the user to select a specific department for scheduling appointments and provides available options for that selection.

**Parameters:**
- `selected_department`: Specifies the chosen department for scheduling the appointment. *Options: `urbanismo`, `intervención`, `empleo`, `concejal`*

**Outputs:**
- `department_options`: Departments available for appointment scheduling include: Intervention, Urbanism, Employment Services, Councillors.

---


### 📂 Documentation Requirements (2 functions)

#### 🔧 Provide Model Communication Previa Details

**Description:** Relays the requirement for the model of Communication Previa and documentation needed when making the request.

**Parameters:** None

**Outputs:**
- `communication_model_info`: Information about the Communication Previa model and required documentation.

---

#### 🔧 Request Documents For Submission

**Description:** Requests and clarifies the documents needed for the submission of the communication request based on the user's specific requirements.

**Parameters:** None

**Outputs:**
- `required_documents`: A list of required documents needed for submission, including documents necessary for a communication request and specific reference to the model of Communication Previa.

**Parent Functions:** `Provide Communication Request Guidance`

---


### 📂 Electronic Submission (1 functions)

#### 🔧 Provide Electronic Submission Guidelines

**Description:** Informs the user on how to submit the communication request electronically, including guidelines on the digital submission process, recommended browser use, payment instructions, and required documentation.

**Parameters:** None

**Outputs:**
- `electronic_submission_guidelines`: Instructions and information on the electronic submission process, including recommendations for supported browsers.
- `payment_information`: Details on payment options and the procedure for paying the ICIO through the Virtual Tax Office.
- `documentation_requirements`: Minimum documentation required for submission.
- `contact_information`: Phone numbers for appointment scheduling and ICIO inquiries.

**Parent Functions:** `Provide Communication Request Guidance`

---


### 📂 Guidance (2 functions)

#### 🔧 Provide Communication Request Guidance

**Description:** Provides comprehensive guidance on submitting a communication request for construction works, including necessary documentation, appointment scheduling, location information, and payment details.

**Parameters:** None

**Outputs:**
- `appointment_details`: Information on how to request and schedule an appointment, including relevant contact numbers and where to submit the request.
- `required_documents`: List of documents required for a communication request, including clarification on necessary documents such as the Communication Model and ICIO payment details.
- `payment_information`: Details about the ICIO tax, including its percentage and instructions on how to make the payment.
- `electronic_submission_guidance`: Instructions for electronically submitting requests using the Sede Electrónica.
- `contact_numbers`: Relevant contact numbers for further assistance.
- `location_information`: The address of the Oficina de Atención Ciudadana.

**Child Functions:**
- `Provide Electronic Submission Guidelines`: Informs the user on how to submit the communication request electronically, including guidelines on the digital submission process, recommended browser use, payment instructions, and required documentation.
- `Request Documents For Submission`: Requests and clarifies the documents needed for the submission of the communication request based on the user's specific requirements.

---

#### 🔧 Provide Appointment Video Link

**Description:** Provides a link to a video that explains how to book or request an appointment.

**Parameters:** None

**Outputs:**
- `appointment_video_link`: URL link to a video guide on how to request, schedule, and book an appointment.

---


### 📂 Information Access (2 functions)

#### 🔧 Provide Urbanism Service Information

**Description:** Provides the user with a link to access information about the urbanism department.

**Parameters:** None

**Outputs:**
- `urbanism_service_link`: URL to information about the urbanism service
- `general_plan_link`: URL to General Urban Planning document

---

#### 🔧 Provide Subsidiary Norms Information

**Description:** Provides the user with a link to access the subsidiary norms of Arucas.

**Parameters:** None

**Outputs:**
- `subsidiary_norms_link`: URL to the Normas Subsidiarias de Arucas document

---


### 📂 Navigation (1 functions)

#### 🔧 Present Sede Electronica Link

**Description:** Provides a direct link to access the Sede Electrónica for appointment scheduling and services.

**Parameters:** None

**Outputs:**
- `electronic_headquarters_link`: Direct URL to the Sede Electrónica for accessing services.

---


### 📂 Payment (1 functions)

#### 🔧 Provide Icio Payment Information

**Description:** Provides information regarding the ICIO payment process, including payment details and contact numbers for inquiries.

**Parameters:** None

**Outputs:**
- `icio_payment_contact_info`: Information regarding the ICIO payment process, including contact numbers for further inquiries.

---


### 📂 Request Processing (2 functions)

#### 🔧 Prompt For Urbanism Request Details

**Description:** Prompts the user for necessary details to submit a request for an urbanism consultation.

**Parameters:** None

**Outputs:**
- `urbanism_request_instructions`: Instructions on how to correctly submit a request for urbanism consultation.

---

#### 🔧 Prompt For Appointment Request Methods

**Description:** Prompts the user for information on how to request an appointment with the relevant employment service through various channels.

**Parameters:** None

**Outputs:**
- `employment_service_appointment_methods`: Describes the methods available for booking appointments with the employment service, including the Servicio Canario de Empleo.

---


### 📂 User Authentication (1 functions)

#### 🔧 Provide Digital Certificate Information

**Description:** Explains what a digital certificate is, the process to acquire one, and how it is utilized for online procedures.

**Parameters:** None

**Outputs:**
- `digital_certificate_information`: Explanation of the digital certificate process and its use cases.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
¿Decías?
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 1,511 |
| Successful Calls | 1,511 |
| Failed Calls | 0 |
| Total Tokens | 1,171,474 |
| Estimated Cost | $0.8067 USD |
| Execution Time | 01:12:59 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 792,265 | 15,967 | 808,232 | $0.5137 |
| Analysis | 321,516 | 41,726 | 363,242 | $0.2931 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

