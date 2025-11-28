# Chatbot Functionality Analysis

## 📊 TRACER Report

✅ **30 functionalities** discovered across **5 categories**

🌐 **Languages supported:** Spanish

### 🎯 Functionality Overview

**📂 Chatbot Meta** (4 functions)
- *Prompt For Language Selection*: Prompts the user to select their preferred language for communication.
- *Prompt For Privacy Policy Acceptance*: Requests the user to accept or reject the privacy policy before providing ass...
- *List Service Options*: Presents a list of services that the chatbot can assist the user with after a...
- *Confirm Query Resolution*: The chatbot confirms whether the provided information resolved the user's query.

**📂 Fare Management** (11 functions)
- *Prompt For Age Group Selection*: Prompts the user to specify their age group to recommend suitable fare options.
- *Provide Tourist Ticket Information*: Provides information about the tourist ticket, including validity, age catego...
- *Provide Single Ticket Info*: The chatbot gives specific information about the Single Ticket, including its...
- *Provide Fare Recommendations*: Offers recommended fare options based on the user's provided information, inc...
- *Provide Transport Card Details*: Provides details about the selected type of transport card when the user requ...
- *...and 6 more functions*

**📂 Journey Planning** (2 functions)
- *Prompt For Departure Zone Selection*: Requests the user to specify their starting fare zone for journey planning, p...
- *Prompt For Destination Zone Selection*: Prompts the user to specify their destination fare zone for journey planning ...

**📂 Public Transport Inquiry** (12 functions)
- *Present Available Lines*: Displays available train lines for the specified station and prompts the user...
- *Provide Station Information*: Provides detailed information about the selected station, including connectio...
- *Present Train Lines Info*: Provides information about the train lines available at the specified station.
- *Present Assistance Options*: Provides a list of assistance options related to public transport inquiries.
- *Present Line Plans*: Offers a choice of different metro plans for the user to download based on li...
- *...and 7 more functions*

**📂 User Identification** (1 functions)
- *Prompt For User Type*: Prompts the user to identify their relationship with the Metro system as eith...

## 🗂️ Functionality Details

### 📂 Chatbot Meta (4 functions)

#### 🔧 Prompt For Language Selection

**Description:** Prompts the user to select their preferred language for communication.

**Parameters:**
- `selected_language`: The language the user chooses for the conversation, indicating their preferred communication language. *Options: `Español`, `Inglés`*

**Outputs:** None

**Child Functions:**
- `Prompt For Privacy Policy Acceptance`: Requests the user to accept or reject the privacy policy before providing assistance.

---

#### 🔧 Prompt For Privacy Policy Acceptance

**Description:** Requests the user to accept or reject the privacy policy before providing assistance.

**Parameters:**
- `privacy_policy_acceptance`: User's choice to accept or decline the privacy policy. *Options: `Acepto`, `No`, `No acepto`, `Sí`*

**Outputs:** None

**Parent Functions:** `Prompt For Language Selection`

**Child Functions:**
- `List Service Options`: Presents a list of services that the chatbot can assist the user with after accepting the privacy policy.

---

#### 🔧 List Service Options

**Description:** Presents a list of services that the chatbot can assist the user with after accepting the privacy policy.

**Parameters:** None

**Outputs:**
- `available_services`: A comprehensive list of services offered, including train schedules, recommended fares, transport card information, directions to stations, circulation status, installation status, and other inquiries.

**Parent Functions:** `Prompt For Privacy Policy Acceptance`

---

#### 🔧 Confirm Query Resolution

**Description:** The chatbot confirms whether the provided information resolved the user's query.

**Parameters:** None

**Outputs:** None

---


### 📂 Fare Management (11 functions)

#### 🔧 Prompt For Age Group Selection

**Description:** Prompts the user to specify their age group to recommend suitable fare options.

**Parameters:**
- `age_group`: User's age group for fare recommendations, categorized into specific ranges. *Options: `15 to 25`, `26 to 64`, `4 to 6`, `7 to 14`, `Entre 15 y 25 años`, `Entre 26 y 64 años`, `Entre 4 y 6 años`, `Entre 7 y 14 años`, `Menor de 4 años`, `Más de 65 años`, `Over 65`, `Under 4`, `entre_15_y_25`, `entre_26_y_64`, `entre_4_y_6`, `entre_7_y_14`, `mayores_de_65`, `menores_de_4`*

**Outputs:** None

---

#### 🔧 Provide Tourist Ticket Information

**Description:** Provides information about the tourist ticket, including validity, age categories, and available zones.

**Parameters:** None

**Outputs:**
- `tourist_ticket_details`: Examples and conditions related to tourist ticket usage.

---

#### 🔧 Provide Single Ticket Info

**Description:** The chatbot gives specific information about the Single Ticket, including its rules and validity.

**Parameters:** None

**Outputs:**
- `ticket_validity`: Details about the validity and usage of the Single Ticket
- `required_card_info`: Information about the Tarjeta Multi required for loading the ticket.

---

#### 🔧 Provide Fare Recommendations

**Description:** Offers recommended fare options based on the user's provided information, including ticket types and pricing.

**Parameters:** None

**Outputs:**
- `fare_recommendations`: Details of suggested fares, including single tickets and tourist passes, along with their prices based on user information.

---

#### 🔧 Provide Transport Card Details

**Description:** Provides details about the selected type of transport card when the user requests more information about a specific card.

**Parameters:**
- `card_type`: The type of transport card the user is inquiring about. *Options: `Tarjeta Personal`, `Tarjeta Multi`, `Tarjeta Azul`, `Tarjeta Infantil`*

**Outputs:** None

---

#### 🔧 Present Card Purchase Options

**Description:** Provides information on how and where the user can purchase the selected transport card.

**Parameters:** None

**Outputs:**
- `card_purchase_options`: Options include Online purchase, In-person at Gestión Offices, and New application document requirements.

---

#### 🔧 Provide New Application Documentation

**Description:** Informs the user about the documentation required for a new request for the transport card.

**Parameters:** None

**Outputs:**
- `required_documents`: Documentation includes a recent photograph, DNI, passport, or residence permit.

---

#### 🔧 Present Card Recharge Options

**Description:** Lists options available for recharging the transportation card and provides a link for more info about the official app.

**Parameters:** None

**Outputs:**
- `recharge_options`: Options include Machines at stations, Official App, Stamps, CaixaBank ATMs
- `app_info`: Link to the official app website.

---

#### 🔧 Provide Ticket Fare Options

**Description:** Provides recommendations for available ticket types and fare options based on user's journey and previous inputs, including pricing details.

**Parameters:** None

**Outputs:**
- `fare_options_and_ticket_types`: A comprehensive list of available fare options and ticket types, including single journey tickets, multiple-trip tickets, tourist passes, and various subscriptions, along with their respective prices.

---

#### 🔧 Present Transport Card Options

**Description:** Lists different types of transport cards available and prompts the user to select one for more information.

**Parameters:** None

**Outputs:**
- `transport_card_options`: Available transport cards include Personal Card, Multi Card, Blue Card, and Child Card (Tarjeta Personal, Tarjeta Multi, Tarjeta Azul, Tarjeta Infantil).

---

#### 🔧 Provide Multi Card Info

**Description:** Offers information about the Multi Card type and its functionalities.

**Parameters:** None

**Outputs:**
- `card_details`: Description of the Multi Card features and how it can be used.

---


### 📂 Journey Planning (2 functions)

#### 🔧 Prompt For Departure Zone Selection

**Description:** Requests the user to specify their starting fare zone for journey planning, providing options based on the fare zones.

**Parameters:**
- `starting_zone`: The fare zone from which the user intends to start their journey, corresponding to the user's starting station. *Options: `Don't know`, `No lo sé`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`, `Zone A`, `Zone B1`, `Zone B2`, `Zone B3`, `Zone C1`, `Zone C2`, `Zone E1`, `Zone E2`*

**Outputs:** None

---

#### 🔧 Prompt For Destination Zone Selection

**Description:** Prompts the user to specify their destination fare zone for journey planning or fare recommendations.

**Parameters:**
- `destination_zone`: Represents the fare zone or geographical zone where the user plans to travel. *Options: `A`, `B1`, `B2`, `B3`, `C1`, `C2`, `Don't know`, `E1`, `E2`, `No lo sé`, `Zona A`, `Zona B1`, `Zona B2`, `Zona B3`, `Zona C1`, `Zona C2`, `Zona E1`, `Zona E2`, `Zone A`, `Zone B1`, `Zone B2`, `Zone B3`, `Zone C1`, `Zone C2`, `Zone E1`, `Zone E2`*

**Outputs:** None

---


### 📂 Public Transport Inquiry (12 functions)

#### 🔧 Present Available Lines

**Description:** Displays available train lines for the specified station and prompts the user to select which line they wish to inquire about.

**Parameters:**
- `selected_line`: The specific train line the user prefers to inquire about. *Options: `10`, `4`, `5`, `All`, `All lines`*

**Outputs:** None

---

#### 🔧 Provide Station Information

**Description:** Provides detailed information about the selected station, including connections, lines serving the station, and additional transport details.

**Parameters:**
- `station_name`: Name of the station requested by the user.

**Outputs:**
- `station_details`: Information about the selected station, including lines serving the station, connections, and a web link for more details.
- `connection_info`: Details of additional transport connections available.

---

#### 🔧 Present Train Lines Info

**Description:** Provides information about the train lines available at the specified station.

**Parameters:** None

**Outputs:**
- `train_lines`: Details of the train lines available at the user's specified station.

---

#### 🔧 Present Assistance Options

**Description:** Provides a list of assistance options related to public transport inquiries.

**Parameters:** None

**Outputs:**
- `assistance_options`: Options include upcoming trains, recommended fares, transport card information, directions, service status, facility status, and other inquiries.

---

#### 🔧 Present Line Plans

**Description:** Offers a choice of different metro plans for the user to download based on line inquiry.

**Parameters:** None

**Outputs:**
- `line_plan_options`: Available plans include a schematic plan and a tourist plan.

---

#### 🔧 Prompt For Current Station Name

**Description:** Prompts the user to provide the name of their current station to assist with checking train schedules and providing train information.

**Parameters:**
- `current_station`: The name of the station where the user is currently located.

**Outputs:**
- `train_schedule`: List of upcoming trains with lines, directions, and arrival times.

---

#### 🔧 Provide Network Status Info

**Description:** Informs the user about the current status of the metro network, including any incidents affecting specific lines and alternative transportation options.

**Parameters:** None

**Outputs:**
- `network_incident_info`: Details of ongoing incidents affecting train service, including information on affected lines, current circulation issues, alternative arrangements (e.g., shuttle buses), and available transportation services.

---

#### 🔧 Present Assistance Categories

**Description:** Lists the available categories of assistance the chatbot can provide to the user.

**Parameters:** None

**Outputs:**
- `train_assistance`: Includes options for checking upcoming trains, recommended fare types, transport card information, directions to a station, network status, and installation status.

---

#### 🔧 Provide Train Arrival Information

**Description:** Provides detailed information about the next arriving trains at a specified station or line, including line numbers, directions, and estimated arrival times or wait times.

**Parameters:**
- `station_name`: The name of the station specified by the user.

**Outputs:**
- `next_train_info`: Details of the next trains arriving at the station, including line numbers, directions, and estimated arrival times.

---

#### 🔧 Provide Route Information

**Description:** Provides detailed route information, including estimated travel time, transfer details, and an interactive map link based on the user's current station and destination.

**Parameters:**
- `start_station`: The name of the current station; destination_station: The name of the destination station.

**Outputs:**
- `route_details`: Estimated travel time, transfer information, and whether transfers are needed.
- `map_link`: Interactive map link for the route.

---

#### 🔧 Prompt For Station For Facility Status

**Description:** Asks the user to specify which station they want to check for the status of facilities.

**Parameters:**
- `station_name`: The name of the station the user wants information about.

**Outputs:** None

**Child Functions:**
- `Present Facility Status Info`: Provides information about the status of facilities, such as elevators and escalators, for the specified station.

---

#### 🔧 Present Facility Status Info

**Description:** Provides information about the status of facilities, such as elevators and escalators, for the specified station.

**Parameters:**
- `station_name`: The name of the station for which the facility status is provided.

**Outputs:**
- `facility_status_info`: Details about the operational status of elevators and escalators at the specified station.

**Parent Functions:** `Prompt For Station For Facility Status`

---


### 📂 User Identification (1 functions)

#### 🔧 Prompt For User Type

**Description:** Prompts the user to identify their relationship with the Metro system as either a tourist or a regular user to offer tailored assistance.

**Parameters:**
- `user_type`: Indicates the user's relationship to the Metro system (visitor or regular user). *Options: `Estoy de visita`, `Regular User`, `Usuario habitual`, `Visitor`*

**Outputs:** None

---


## ⚙️ Technical Details

### 🌐 Language Support

- Spanish

### 🔄 Fallback Behavior

```
Lo siento, este es *un canal de información de servicio y de atención al cliente* de Metro de Madrid.\n \nPara cualquier otro tipo de información puedes consultar nuestra página web:\n🌐 www.metromadrid.es\n \n¿Con qué otra duda podría ayudarte? 👇
```

## 📈 Performance Statistics

### Overview

| Metric | Value |
|--------|-------|
| Total LLM Calls | 3,387 |
| Successful Calls | 3,387 |
| Failed Calls | 0 |
| Total Tokens | 1,996,265 |
| Estimated Cost | $1.4846 USD |
| Execution Time | 02:42:26 |

### Phase Breakdown

| Phase | Prompt Tokens | Completion Tokens | Total Tokens | Cost |
|-------|---------------|-------------------|--------------|------|
| Exploration | 1,071,150 | 36,636 | 1,107,786 | $0.7306 |
| Analysis | 765,746 | 122,733 | 888,479 | $0.7540 |

### Models Used

- gpt-4o-mini

## 📁 Generated Files

This analysis generated the following files:

- **`README.md`** - This main report with comprehensive functionality analysis
- **`functionalities.json`** - Raw JSON data structure
- **`workflow_graph.*`** - Visual graph of functionality relationships (format depends on configuration: PDF, PNG, SVG, or all formats)
- **`profiles/`** - Directory containing user profile YAML files

