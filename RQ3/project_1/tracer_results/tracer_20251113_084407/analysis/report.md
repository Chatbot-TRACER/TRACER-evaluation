# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **30 functionalities** discovered across **16 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Bicycle Policy** (1 functions)
- *Provide Bicycle Transportation Information*: The chatbot provides information about the rules and policies governing bicyc...

**📂 Chatbot Meta** (3 functions)
- *Prompt For Language Selection*: Asks the user to select their preferred language for communication with the c...
- *Prompt For Privacy Policy Acceptance*: Requests the user to accept or decline the privacy policy to proceed with ass...
- *Prompt For Privacy Acceptance*: Requests the user to accept the privacy policy to proceed with further assist...

**📂 Fare Information** (1 functions)
- *Provide Fare Information*: Shares information regarding fare rules and requirements based on the user's ...

**📂 Fare Recommendations** (2 functions)
- *Provide Fare Recommendations*: Provides the user with recommended fare and tariff options based on their pro...
- *Provide Fare Recommendations*: Provides the user with recommended fare and tariff options based on their pro...

**📂 Map Services** (2 functions)
- *Present Map Download Options*: The chatbot offers different map download options to the user.
- *Provide Map Download*: The chatbot shares the schematic map of the metro upon request.

**📂 Network Status** (1 functions)
- *Provide Network Status*: Informs the user about the current network status, including any disruptions ...

**📂 Pet Policy** (1 functions)
- *Provide Pet Transportation Policy*: The chatbot informs the user about the policies regarding traveling with smal...

**📂 Regulation Information** (1 functions)
- *Prompt For Usage Regulation Info*: The chatbot offers a link to the regulations that govern usage of the metro s...

**📂 Route Information** (2 functions)
- *Provide Route Information*: The chatbot provides details about the route from the starting station to the...
- *Provide Route Information*: The chatbot provides details about the route from the starting station to the...

**📂 Ticket Information** (1 functions)
- *Provide Combined Ticket Info*: Provides details about the Combined Ticket, including its validity and usage ...

**📂 Train Schedule** (2 functions)
- *Provide Upcoming Trains Information*: Provides information about upcoming trains for the selected line at the user'...
- *Provide Next Train Info*: Displays information about the next trains arriving at the specified station,...

**📂 Transit Information** (2 functions)
- *Present Subway Line Options*: Provides information on the available subway lines at the specified station a...
- *List Train Lines*: Displays the available train lines at the user's specified station and prompt...

**📂 Transit Options** (1 functions)
- *Present Transport Card Options*: Lists different transportation cards available and their respective details.

**📂 User Information Gathering** (7 functions)
- *Prompt For Age Group Selection*: Requests the user to select their age group in order to provide tailored fare...
- *Prompt For User Type*: Inquires whether the user is a visitor or a regular user of the Metro network...
- *Prompt For Destination Zone Selection*: Requests the user to specify the destination zone for their journey.
- *Prompt For Destination Station*: Prompts the user for their destination station to provide directions.
- *Prompt For Start Zone*: Prompts the user to specify their starting zone for the journey.
- *...and 2 more functions*

**📂 User Interaction** (2 functions)
- *Prompt For General Inquiry*: The chatbot asks the user to specify other questions or inquiries they may have.
- *Prompt For Inquiry Type*: The chatbot asks the user to specify the type of inquiry they have from a pro...

**📂 User Support** (1 functions)
- *Present Assistance Options*: Presents the user with a comprehensive list of options and services available...

## 🗂️ Functionality Details

### 📂 Bicycle Policy (1 functions)

#### 🔧 Provide Bicycle Transportation Information

**Description:** The chatbot provides information about the rules and policies governing bicycle transportation on the subway.

**Parameters:** None

**Outputs:**
- `bicycle_transport_rules`: Details about the rules for traveling with bicycles, including specific regulations for transport on the subway.

---


### 📂 Chatbot Meta (3 functions)

#### 🔧 Prompt For Language Selection

**Description:** Asks the user to select their preferred language for communication with the chatbot.

**Parameters:**
- `selected_language`: The preferred language the user wishes to communicate in. *Options: `Español`, `Inglés`*

**Outputs:** None

**Child Functions:**
- `Prompt For Privacy Policy Acceptance`: Requests the user to accept or decline the privacy policy to proceed with assistance.
- `Prompt For Privacy Acceptance`: Requests the user to accept the privacy policy to proceed with further assistance.

---

#### 🔧 Prompt For Privacy Policy Acceptance

**Description:** Requests the user to accept or decline the privacy policy to proceed with assistance.

**Parameters:**
- `privacy_policy_acceptance`: The user's decision to accept or decline the privacy policy. *Options: `Accept`, `No`, `Not Accept`, `Sí`, `Yes`, `accept`, `reject`*

**Outputs:** None

**Parent Functions:** `Prompt For Language Selection`

**Child Functions:**
- `Prompt For Age Group Selection`: Requests the user to select their age group in order to provide tailored fare recommendations.
- `Prompt For User Type`: Inquires whether the user is a visitor or a regular user of the Metro network to provide relevant fare recommendations.

---

#### 🔧 Prompt For Privacy Acceptance

**Description:** Requests the user to accept the privacy policy to proceed with further assistance.

**Parameters:**
- `acceptance`: user confirmation for acceptance of the privacy policy. *Options: `Yes`, `No`*

**Outputs:** None

**Parent Functions:** `Prompt For Language Selection`

---


### 📂 Fare Information (1 functions)

#### 🔧 Provide Fare Information

**Description:** Shares information regarding fare rules and requirements based on the user's age group.

**Parameters:** None

**Outputs:**
- `fare_information_details`: Details about fare policies related to various age groups.

**Parent Functions:** `Prompt For Age Group Selection`

---


### 📂 Fare Recommendations (2 functions)

#### 🔧 Provide Fare Recommendations

**Description:** Provides the user with recommended fare and tariff options based on their profile, including pricing details for various ticket types and tourist passes.

**Parameters:** None

**Outputs:**
- `fare_options`: Details on pricing for various ticket options including single journeys (Billete sencillo combinado), 10-journey tickets (10 viajes combinado), and tourist passes (Título Turístico) with prices for different durations.

**Parent Functions:** `Prompt For Age Group Selection`, `Prompt For User Type`

---

#### 🔧 Provide Fare Recommendations

**Description:** Provides the user with recommended fare and tariff options based on their profile, including pricing details for various ticket types and tourist passes.

**Parameters:** None

**Outputs:**
- `fare_options`: Details on pricing for various ticket options including single journeys (Billete sencillo combinado), 10-journey tickets (10 viajes combinado), and tourist passes (Título Turístico) with prices for different durations.

**Parent Functions:** `Prompt For Age Group Selection`, `Prompt For User Type`

---


### 📂 Map Services (2 functions)

#### 🔧 Present Map Download Options

**Description:** The chatbot offers different map download options to the user.

**Parameters:** None

**Outputs:**
- `map_options`: Available maps include schematic map and tourist map.

---

#### 🔧 Provide Map Download

**Description:** The chatbot shares the schematic map of the metro upon request.

**Parameters:** None

**Outputs:** None

---


### 📂 Network Status (1 functions)

#### 🔧 Provide Network Status

**Description:** Informs the user about the current network status, including any disruptions or incidents affecting subway or train lines.

**Parameters:** None

**Outputs:**
- `network_incidents`: Specific incidents affecting subway lines, including detailed information about Line 6 and Line 7, their impact on train circulation, duration, and alternative transportation options available.

---


### 📂 Pet Policy (1 functions)

#### 🔧 Provide Pet Transportation Policy

**Description:** The chatbot informs the user about the policies regarding traveling with small pets on the subway.

**Parameters:** None

**Outputs:**
- `pet_policy_details`: Specific rules governing pet transport on the subway.

---


### 📂 Regulation Information (1 functions)

#### 🔧 Prompt For Usage Regulation Info

**Description:** The chatbot offers a link to the regulations that govern usage of the metro service.

**Parameters:** None

**Outputs:**
- `usage_regulation_link`: Link to the regulations of the metro service.

---


### 📂 Route Information (2 functions)

#### 🔧 Provide Route Information

**Description:** The chatbot provides details about the route from the starting station to the destination station, including estimated duration, transfer information, and an interactive map link.

**Parameters:**
- `current_station`: The starting station (e.g., Atocha); destination_station: The destination station (e.g., Chamartín)

**Outputs:**
- `route_information`: Estimated duration of the journey along with information about any required transfers.
- `interactive_map_link`: A link to an interactive map for journey visualization.

**Parent Functions:** `Prompt For Current Station`, `Prompt For Destination Station`

---

#### 🔧 Provide Route Information

**Description:** The chatbot provides details about the route from the starting station to the destination station, including estimated duration, transfer information, and an interactive map link.

**Parameters:**
- `current_station`: The starting station (e.g., Atocha); destination_station: The destination station (e.g., Chamartín)

**Outputs:**
- `route_information`: Estimated duration of the journey along with information about any required transfers.
- `interactive_map_link`: A link to an interactive map for journey visualization.

**Parent Functions:** `Prompt For Current Station`, `Prompt For Destination Station`

---


### 📂 Ticket Information (1 functions)

#### 🔧 Provide Combined Ticket Info

**Description:** Provides details about the Combined Ticket, including its validity and usage conditions.

**Parameters:** None

**Outputs:**
- `combined_ticket_info`: Information about the Combined Ticket, including its validity across different lines, usage requirements, qualities, and restrictions.

**Parent Functions:** `Prompt For User Type`

---


### 📂 Train Schedule (2 functions)

#### 🔧 Provide Upcoming Trains Information

**Description:** Provides information about upcoming trains for the selected line at the user's station, including destinations and arrival times.

**Parameters:**
- `selected_line`: The line that the user wants to check upcoming trains for (e.g., 4, 5, or 10).

**Outputs:**
- `upcoming_trains`: Lists the upcoming trains with their respective destinations, directions, and estimated arrival times.

**Parent Functions:** `List Train Lines`

---

#### 🔧 Provide Next Train Info

**Description:** Displays information about the next trains arriving at the specified station, including line numbers, directions, and waiting/arrival times.

**Parameters:** None

**Outputs:**
- `upcoming_trains_info`: Details of the next trains arriving, including line numbers, directions, waiting times, and arrival times.

---


### 📂 Transit Information (2 functions)

#### 🔧 Present Subway Line Options

**Description:** Provides information on the available subway lines at the specified station and prompts the user for their selection.

**Parameters:**
- `selected_line`: The train line the user wishes to inquire further about, including subway options. *Options: `10`, `4`, `5`, `All`, `All Lines`*

**Outputs:**
- `line_info`: Information about the selected line and its connections, including lines like Línea 4, Línea 5, and Línea 10.

**Parent Functions:** `Prompt For Current Station`

---

#### 🔧 List Train Lines

**Description:** Displays the available train lines at the user's specified station and prompts for the selection of a specific line.

**Parameters:**
- `selected_line`: Indicates which train line the user wants information about *Options: `1`, `2`, `3`*

**Outputs:**
- `available_lines`: Line 4, Line 5, Line 10. Lists the train lines that operate from the specified station.

**Parent Functions:** `Prompt For Current Station`

**Child Functions:**
- `Provide Upcoming Trains Information`: Provides information about upcoming trains for the selected line at the user's station, including destinations and arrival times.

---


### 📂 Transit Options (1 functions)

#### 🔧 Present Transport Card Options

**Description:** Lists different transportation cards available and their respective details.

**Parameters:** None

**Outputs:**
- `transport_card_types`: Information about the Public Transport Personal Card, Public Transport Multi Card, and others available on the network.

---


### 📂 User Information Gathering (7 functions)

#### 🔧 Prompt For Age Group Selection

**Description:** Requests the user to select their age group in order to provide tailored fare recommendations.

**Parameters:**
- `age_group`: The age group of the user for fare calculation and relevant recommendations, represented in various formats. *Options: `15-25`, `15_to_25`, `26-64`, `26_to_64`, `4-6`, `4_to_6`, `7-14`, `7_to_14`, `Entre 15 y 25 años`, `Entre 26 y 64 años`, `Entre 4 y 6 años`, `Entre 7 y 14 años`, `Menor de 4 años`, `Más de 65 años`, `Over 65`, `Under 4`, `over_65`, `under_4`*

**Outputs:** None

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

**Child Functions:**
- `Provide Fare Recommendations`: Provides the user with recommended fare and tariff options based on their profile, including pricing details for various ticket types and tourist passes.
- `Provide Fare Information`: Shares information regarding fare rules and requirements based on the user's age group.

---

#### 🔧 Prompt For User Type

**Description:** Inquires whether the user is a visitor or a regular user of the Metro network to provide relevant fare recommendations.

**Parameters:**
- `user_type`: The classification of the user's relationship with the Metro network, indicating if the user is a visitor or a regular metro user. *Options: `Estoy de visita`, `Regular User`, `Usuario habitual`, `regular`, `regular_user`, `visitor`*

**Outputs:** None

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

**Child Functions:**
- `Provide Fare Recommendations`: Provides the user with recommended fare and tariff options based on their profile, including pricing details for various ticket types and tourist passes.
- `Provide Combined Ticket Info`: Provides details about the Combined Ticket, including its validity and usage conditions.

---

#### 🔧 Prompt For Destination Zone Selection

**Description:** Requests the user to specify the destination zone for their journey.

**Parameters:**
- `destination_zone`: The zone to which the user intends to travel. *Options: `A`, `B1`, `B2`, `B3`, `C1`, `C2`, `E1`, `E2`, `No lo sé`, `Unsure`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`*

**Outputs:** None

---

#### 🔧 Prompt For Destination Station

**Description:** Prompts the user for their destination station to provide directions.

**Parameters:**
- `destination_station`: The station where the user is headed, or the name of the station the user is traveling to.

**Outputs:** None

**Child Functions:**
- `Provide Route Information`: The chatbot provides details about the route from the starting station to the destination station, including estimated duration, transfer information, and an interactive map link.

---

#### 🔧 Prompt For Start Zone

**Description:** Prompts the user to specify their starting zone for the journey.

**Parameters:**
- `departure_zone`: The zone from which the user plans to start their journey. *Options: `No lo sé`, `Unsure`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`*

**Outputs:** None

---

#### 🔧 Prompt For Fare Recommendation

**Description:** The chatbot prompts the user for information needed to recommend the best fare option.

**Parameters:**
- `age_group`: The user's age group for fare recommendation. *Options: `under_4`, `age_4_to_6`, `age_7_to_14`, `age_15_to_25`, `age_26_to_64`, `age_65_plus`*

**Outputs:** None

---

#### 🔧 Prompt For Current Station

**Description:** Requests the user to specify their current station to provide further assistance or train information.

**Parameters:**
- `current_station`: The name of the station where the user is currently located.

**Outputs:**
- `map_image`: link to or description of a map with the stations.

**Child Functions:**
- `Present Subway Line Options`: Provides information on the available subway lines at the specified station and prompts the user for their selection.
- `Provide Route Information`: The chatbot provides details about the route from the starting station to the destination station, including estimated duration, transfer information, and an interactive map link.
- `List Train Lines`: Displays the available train lines at the user's specified station and prompts for the selection of a specific line.

---


### 📂 User Interaction (2 functions)

#### 🔧 Prompt For General Inquiry

**Description:** The chatbot asks the user to specify other questions or inquiries they may have.

**Parameters:** None

**Outputs:** None

---

#### 🔧 Prompt For Inquiry Type

**Description:** The chatbot asks the user to specify the type of inquiry they have from a provided list.

**Parameters:**
- `inquiry_type`: The specific area the user wants assistance with. *Options: `service_hours`, `bicycle_access`, `pet_access`, `use_regulations`, `other`*

**Outputs:** None

---


### 📂 User Support (1 functions)

#### 🔧 Present Assistance Options

**Description:** Presents the user with a comprehensive list of options and services available for assistance with transportation-related inquiries.

**Parameters:** None

**Outputs:**
- `assistance_options`: Options available for assistance include inquiries about upcoming trains, recommended fares, transport card information, directions to stations, network status, facility status, and other inquiries.

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Este canal está destinado a cuestiones relacionadas con el servicio y atención al cliente de Metro de Madrid. Para otros temas, consulta nuestra web: 🌐 www.metromadrid.es. ¿Puedo ayudarte en algo más? 👇
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 2,166 |
| Successful Calls | 2,166 |
| Failed Calls | 0 |
| Total Tokens | 1,475,914 |
| Estimated Cost | $1.0505 USD |
| Execution Time | 02:04:24 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 966,221 | 27,598 | 993,819 | $0.6460 |
| Analysis | 418,068 | 64,027 | 482,095 | $0.4045 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

