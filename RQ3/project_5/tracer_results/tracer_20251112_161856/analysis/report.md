# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **11 functionalities** discovered across **4 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Environmental Services** (1 functions)
- *Provide Environmental Services Info Link*: Provides a link to detailed information about the environmental services avai...

**📂 General Information** (4 functions)
- *Prompt For Ayuntamiento Service Inquiry*: Asks the user to specify their inquiry regarding services provided by the Ayu...
- *Present Information About Arucas*: Provides a brief description of the chatbot's role as an assistant regarding ...
- *Handle Repeat Query*: Acknowledges the user's request for repetition of previously stated informati...
- *Solicit Repeat Information*: Requests the user to repeat their previous query when the chatbot does not un...

**📂 Public Announcements** (4 functions)
- *Present Opposition Announcements Info*: Informs the user where to find all announcements for public competitions, men...
- *Provide Link To Bop*: Supplies a link to the Boletín Oficial de la Provincia of Las Palmas where al...
- *Provide Link To Public Sector Employment*: Supplies a URL to the public sector employment announcements section of the P...
- *Repeat Opposition Announcements Info*: Reiterates the information about where to find opposition announcements when ...

**📂 Subsidies Information** (2 functions)
- *Present Information Options*: The chatbot lists various types of information regarding subsidies in Arucas ...
- *Provide Link To Active Subsidies*: Provides a link to access all active subsidy calls from public organizations.

## 🗂️ Functionality Details

### 📂 Environmental Services (1 functions)

#### 🔧 Provide Environmental Services Info Link

**Description:** Provides a link to detailed information about the environmental services available at the Ayuntamiento of Arucas.

**Parameters:** None

**Outputs:**
- `environmental_service_info`: Provides a URL link to detailed information regarding the environmental services available at the Ayuntamiento of Arucas.

---


### 📂 General Information (4 functions)

#### 🔧 Prompt For Ayuntamiento Service Inquiry

**Description:** Asks the user to specify their inquiry regarding services provided by the Ayuntamiento of Arucas.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Present Information About Arucas

**Description:** Provides a brief description of the chatbot's role as an assistant regarding inquiries related to Arucas.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Handle Repeat Query

**Description:** Acknowledges the user's request for repetition of previously stated information without providing new answers.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Solicit Repeat Information

**Description:** Requests the user to repeat their previous query when the chatbot does not understand their request.

**Parameters:** None

**Outputs:** None

---


### 📂 Public Announcements (4 functions)

#### 🔧 Present Opposition Announcements Info

**Description:** Informs the user where to find all announcements for public competitions, mentioning the Boletín Oficial de la Provincia de las Palmas (BOP) and the Portal de Transparencia section.

**Parameters:** None

**Outputs:**
- `category_info`: Describes announcement locations including BOP and Portal de Transparencia.

---

#### 🔧 Provide Link To Bop

**Description:** Supplies a link to the Boletín Oficial de la Provincia of Las Palmas where all public job announcements can be found.

**Parameters:** None

**Outputs:**
- `link_to_bop`: URL to the Boletín Oficial.

---

#### 🔧 Provide Link To Public Sector Employment

**Description:** Supplies a URL to the public sector employment announcements section of the Portal de Transparencia.

**Parameters:** None

**Outputs:**
- `public_sector_employment_link`: URL linking to the employment announcements and public sector employment section of the Portal de Transparencia.

---

#### 🔧 Repeat Opposition Announcements Info

**Description:** Reiterates the information about where to find opposition announcements when prompted by the user.

**Parameters:** None

**Outputs:**
- `location_info`: Details about where to find opposition announcements, including links to the Boletín Oficial de la Provincia de las Palmas and the Portal de Transparencia.

---


### 📂 Subsidies Information (2 functions)

#### 🔧 Present Information Options

**Description:** The chatbot lists various types of information regarding subsidies in Arucas and prompts the user to select a topic of interest.

**Parameters:**
- `selected_option`: Describes the specific type of information regarding subsidies the user can request. *Options: `Subvenciones públicas activas`, `Subvenciones para la promoción del empleo autónomo del Gobierno de Canarias`, `Subvenciones de apoyo a autónomos y microempresas del municipio de Arucas por covid-19`, `¿Cómo puedo conocer las subvenciones activas de los diferentes organismos públicos?`, `¿Qué documentación debe acompañar a la solicitud de subvención?`*

**Outputs:** None

---

#### 🔧 Provide Link To Active Subsidies

**Description:** Provides a link to access all active subsidy calls from public organizations.

**Parameters:** None

**Outputs:**
- `active_subsidies_link`: URL for accessing the list of active subsidy calls.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Ups, no he entendido a que te refieres.
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 795 |
| Successful Calls | 795 |
| Failed Calls | 0 |
| Total Tokens | 758,288 |
| Estimated Cost | $0.4795 USD |
| Execution Time | 00:53:11 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 658,593 | 6,117 | 664,710 | $0.4098 |
| Analysis | 86,072 | 7,506 | 93,578 | $0.0697 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

