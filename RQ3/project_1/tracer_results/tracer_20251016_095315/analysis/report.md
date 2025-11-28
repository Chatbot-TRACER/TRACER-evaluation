# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **21 functionalities** discovered across **4 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Chatbot Meta** (2 functions)
- *Prompt For Language Selection*: Prompts the user to select their preferred language for communication.
- *Prompt For Privacy Policy Acceptance*: Requests the user to confirm acceptance or decline of the privacy policy befo...

**📂 Customer Support** (1 functions)
- *Prompt For Confirmation Of Doubt Resolution*: The chatbot asks the user if their question has been resolved.

**📂 Fare Recommendations** (8 functions)
- *Prompt For Fare Information*: Asks the user questions sequentially to recommend the best fare based on user...
- *Prompt For Age Group Selection*: Prompts the user to specify their age group to recommend appropriate fare opt...
- *Prompt For Departure Zone Selection*: Prompts the user to select their departure zone for the journey, influencing ...
- *Prompt For User Type Selection*: Requests the user to specify their status as a visitor or a regular user of t...
- *Prompt For Destination Zone Selection*: Requests the user to specify their destination zone for fare calculation or j...
- *...and 3 more functions*

**📂 Transport Assistance** (10 functions)
- *Present Transport Help Options*: Presents a list of public transportation assistance topics that the user can ...
- *Present Available Services*: Lists the possible services the chatbot can assist with related to travel and...
- *Present Line Options*: Displays available metro line options at a specified station and prompts the ...
- *Present Transport Card Options*: The chatbot presents different types of transport cards available to the user.
- *Provide Metro Map*: Shares a schematic map of the Madrid Metro system along with travel informati...
- *...and 5 more functions*

## 🗂️ Functionality Details

### 📂 Chatbot Meta (2 functions)

#### 🔧 Prompt For Language Selection

**Description:** Prompts the user to select their preferred language for communication.

**Parameters:**
- `selected_language`: The language in which the user wants to communicate. *Options: `English`, `Español`, `Inglés`*

**Outputs:** None

**Child Functions:**
- `Prompt For Privacy Policy Acceptance`: Requests the user to confirm acceptance or decline of the privacy policy before proceeding with assistance.

---

#### 🔧 Prompt For Privacy Policy Acceptance

**Description:** Requests the user to confirm acceptance or decline of the privacy policy before proceeding with assistance.

**Parameters:**
- `privacy_policy_acceptance`: User's acceptance or decline of the privacy policy. *Options: `Acepto`, `No`, `No acepto`, `Sí`, `✓ Acepto`, `✗ No acepto`*

**Outputs:** None

**Parent Functions:** `Prompt For Language Selection`

**Child Functions:**
- `Present Transport Help Options`: Presents a list of public transportation assistance topics that the user can select from, including train schedules, fare recommendations, directions to stations, transport card information, network status, and facility inquiries.
- `Present Available Services`: Lists the possible services the chatbot can assist with related to travel and fare inquiries.

---


### 📂 Customer Support (1 functions)

#### 🔧 Prompt For Confirmation Of Doubt Resolution

**Description:** The chatbot asks the user if their question has been resolved.

**Parameters:**
- `resolution_confirmation`: Whether the user feels their question has been resolved. *Options: `Sí`, `No`*

**Outputs:** None

---


### 📂 Fare Recommendations (8 functions)

#### 🔧 Prompt For Fare Information

**Description:** Asks the user questions sequentially to recommend the best fare based on user responses.

**Parameters:**
- `user_age_group`: The age group of the user. *Options: `Menor de 4 años`, `Entre 4 y 6 años`, `Entre 7 y 14 años`, `Entre 15 y 25 años`, `Entre 26 y 64 años`, `Más de 65 años`*

**Outputs:** None

**Parent Functions:** `Present Transport Help Options`

---

#### 🔧 Prompt For Age Group Selection

**Description:** Prompts the user to specify their age group to recommend appropriate fare options.

**Parameters:**
- `age_group`: The age group of the user for fare determination. *Options: `Entre 15 y 25 años`, `Entre 26 y 64 años`, `Entre 4 y 6 años`, `Entre 7 y 14 años`, `Menor de 4 años`, `Más de 65 años`*

**Outputs:** None

**Child Functions:**
- `Prompt For Departure Zone Selection`: Prompts the user to select their departure zone for the journey, influencing fare recommendations.

---

#### 🔧 Prompt For Departure Zone Selection

**Description:** Prompts the user to select their departure zone for the journey, influencing fare recommendations.

**Parameters:**
- `fare_zone`: The selected fare zone from which the user will begin their journey. *Options: `A`, `B1`, `B2`, `B3`, `C1`, `C2`, `E1`, `E2`, `No lo sé`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`*

**Outputs:**
- `zone_image`: Visual representation of the zones to assist user selection.

**Parent Functions:** `Prompt For Age Group Selection`

---

#### 🔧 Prompt For User Type Selection

**Description:** Requests the user to specify their status as a visitor or a regular user of the Metro system to suggest appropriate fare options.

**Parameters:**
- `user_type`: Indicates the user's status regarding usage of the Metro system, whether they are a visitor or a regular user. *Options: `Estoy de visita`, `Usuario habitual`, `regular user`, `visitor`*

**Outputs:** None

---

#### 🔧 Prompt For Destination Zone Selection

**Description:** Requests the user to specify their destination zone for fare calculation or journey recommendations.

**Parameters:**
- `destination_zone`: Indicates the user's intended destination zone or fare zone for the user's journey. *Options: `A`, `B1`, `B2`, `B3`, `C1`, `C2`, `E1`, `E2`, `No lo sé`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`, `unknown`*

**Outputs:** None

---

#### 🔧 Provide Fare Recommendations

**Description:** Offers tailored fare suggestions based on user inputs for travel, including various ticket options and their respective prices.

**Parameters:** None

**Outputs:**
- `fare_options`: A list of travel ticket options, including billete sencillo, 10 viajes, and Título Turístico (available for 1 to 7 days), along with their respective prices for both regular and tourist fares.

---

#### 🔧 Provide Explanation For Single Ticket

**Description:** Explains the single ticket, including its options and requirements.

**Parameters:** None

**Outputs:**
- `ticket_details`: Information about the single ticket's coverage and usage.

---

#### 🔧 Provide Tourist Ticket Details

**Description:** The chatbot provides detailed information about the Tourist Ticket, including validities and pricing.

**Parameters:** None

**Outputs:**
- `tourist_ticket_details`: Details on the validity periods and corresponding costs of the Tourist Ticket.

---


### 📂 Transport Assistance (10 functions)

#### 🔧 Present Transport Help Options

**Description:** Presents a list of public transportation assistance topics that the user can select from, including train schedules, fare recommendations, directions to stations, transport card information, network status, and facility inquiries.

**Parameters:** None

**Outputs:**
- `transport_assistance`: A list of inquiries the chatbot can assist with, including nearby trains, recommended fares, transport card details, directions to stations, service status, upcoming trains, and installation status.

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

**Child Functions:**
- `Prompt For Fare Information`: Asks the user questions sequentially to recommend the best fare based on user responses.

---

#### 🔧 Present Available Services

**Description:** Lists the possible services the chatbot can assist with related to travel and fare inquiries.

**Parameters:** None

**Outputs:**
- `service_options`: Consulting upcoming trains, recommended fares, transportation card info, directions to a station, network status, installation status, and other queries.

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

---

#### 🔧 Present Line Options

**Description:** Displays available metro line options at a specified station and prompts the user to select one.

**Parameters:**
- `selected_line`: User's selected metro line to receive information about. *Options: `Línea 1`, `Línea 10`, `Línea 2`, `Línea 3`, `Línea 4`, `Línea 5`, `Ver todas`*
- `station_name`: The name of the station where the user is currently located.

**Outputs:**
- `line_options`: A list of metro lines available at the specified station along with their respective directions and arrival times.

---

#### 🔧 Present Transport Card Options

**Description:** The chatbot presents different types of transport cards available to the user.

**Parameters:** None

**Outputs:**
- `transport_card_types`: Types of transport cards including Tarjeta Personal, Tarjeta Multi, Tarjeta Azul, Tarjeta Infantil, and others.

---

#### 🔧 Provide Metro Map

**Description:** Shares a schematic map of the Madrid Metro system along with travel information between specified stations.

**Parameters:** None

**Outputs:**
- `metro_map_link`: URL to the interactive metro map with origin and destination stations.
- `travel_duration`: Estimated travel time between the specified stations.
- `transfers_information`: Information on whether transfers are required for the journey.
- `metro_map`: A schematic representation of the Metro network.

---

#### 🔧 Provide Train Information

**Description:** Provides details about the next arriving trains at a specified station, including lines, directions, and expected arrival times.

**Parameters:**
- `selected_line`: the train line the user wants to inquire about *Options: `4`, `5`, `10`*

**Outputs:**
- `next_trains_info`: Information about upcoming trains, including line numbers, directions, expected arrival times, and wait times.

---

#### 🔧 Prompt For Station Info

**Description:** Prompts the user to specify their station name to provide relevant information about train schedules or facility status.

**Parameters:**
- `current_station`: The name of the station where the user is located.

**Outputs:** None

---

#### 🔧 Provide Network Status

**Description:** Informs the user about current incidents affecting the metro network, including specific lines impacted and available services during disruptions.

**Parameters:** None

**Outputs:**
- `metro_incidents`: Details about current incidents affecting the metro network, including specific line numbers, nature of disruptions, circulation interruptions, and substitute services available for affected routes.
- `alternative_services`: Information about substitute bus services available for commuters.

---

#### 🔧 Prompt For Destination Station

**Description:** Prompts the user to specify their destination station to provide travel information.

**Parameters:**
- `destination_station`: The name of the station the user is traveling to.

**Outputs:** None

---

#### 🔧 Provide Route Details And Link

**Description:** Provides estimated travel duration and a link to the interactive map for the user's specified route.

**Parameters:** None

**Outputs:**
- `route_duration`: Estimated time for the journey or travel duration.
- `route_map_link`: URL to the interactive map for directions or metro map.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Este canal está destinado a cuestiones relacionadas con el servicio y atención al cliente de Metro de Madrid.\n\nPara otros asuntos, visita nuestra web:\n🌐  www.metromadrid.es\n\n¿Hay algo más en lo que pueda ayudarte? 👇
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 1,862 |
| Successful Calls | 1,862 |
| Failed Calls | 0 |
| Total Tokens | 1,428,012 |
| Estimated Cost | $1.0037 USD |
| Execution Time | 01:20:38 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 942,230 | 26,863 | 969,093 | $0.6298 |
| Analysis | 404,159 | 54,760 | 458,919 | $0.3739 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

