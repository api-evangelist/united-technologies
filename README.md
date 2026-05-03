# United Technologies (united-technologies)

United Technologies Corporation (UTC) was an American multinational conglomerate that merged with Raytheon Company in 2020 to form Raytheon Technologies, later renamed RTX Corporation in 2023. Prior to the merger, UTC's major subsidiaries included Otis Elevator (now independent), Carrier Global (now independent), Pratt & Whitney, and Collins Aerospace. Today, Collins Aerospace (formerly UTC Aerospace Systems and Rockwell Collins) provides aviation connectivity and data exchange services through the ARINC Digital Exchange platform, including messaging, flight operations, and weather data APIs for commercial aviation.

**URL:** [Visit Collins Aerospace](https://www.rtx.com/collinsaerospace)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Aerospace, Defense, Aviation, Manufacturing, Connectivity

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Collins Aerospace ARINC Messaging API

The Collins Aerospace ARINC Messaging API provides access to the ARINC Global Network for aviation messaging and data exchange. Supports ACARS, OOOI flight events, aviation weather, and operational communications between aircraft, airlines, airports, and ground operations. Part of the Collins Aerospace ARINC Digital Exchange platform.

**Human URL:** [https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange](https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange)

#### Tags:

 - Aviation, Messaging, ACARS, OOOI, Aerospace

#### Properties

- [Documentation](https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange/arinc-messaging)
- [OpenAPI](openapi/united-technologies-arinc-messaging-openapi.yml)
- [Message Schema](json-schema/arinc-messaging-message-schema.json)
- [Flight Schema](json-schema/arinc-messaging-flight-schema.json)
- [Message Structure](json-structure/arinc-messaging-message-structure.json)
- [JSON-LD Context](json-ld/united-technologies-arinc-messaging-context.jsonld)
- [Message Example](examples/arinc-messaging-message-example.json)

## Common Properties

- [Collins Aerospace Website](https://www.rtx.com/collinsaerospace)
- [ARINC Online Portal](https://arinconline.collinsaerospace.com)
- [Messaging and Data Exchange](https://www.rtx.com/collinsaerospace/what-we-do/industries/commercial-aviation/ground-operations/messaging-data-exchange)

## Features

| Name | Description |
|------|-------------|
| ARINC Global Network | Industry-standard aviation communications network connecting aircraft, airlines, airports, and ground operations worldwide. |
| ACARS Messaging | Aircraft Communications Addressing and Reporting System messaging for digital communications between aircraft and ground. |
| OOOI Flight Events | Real-time Out, Off, On, In flight event tracking for operational efficiency and on-time performance monitoring. |
| Aviation Weather Data | METARs, TAFs, SIGMETs, PIREPs, and graphical weather services for flight operations and dispatch. |
| ARINC Integrator Platform | Flexible integration platform deployable on-premise, SaaS, or in customer cloud for managing aviation data exchange. |
| Connected Aircraft Solutions | InteliSight, GlobalConnect, and FlightHub platforms for comprehensive connected aircraft and ground operations. |
| Airport Network Connectivity | AviNet Airport and GLOBALink network infrastructure for airport ground operations and avionics connectivity. |

## Use Cases

| Name | Description |
|------|-------------|
| Airline Operations Control | Monitor real-time flight status, OOOI events, and aircraft communications for dispatch and operations center workflows. |
| Ground Operations Automation | Automate gate assignments, crew notifications, and turnaround communications using ACARS uplink messaging. |
| Flight Dispatch | Access METARs, TAFs, and SIGMETs for pre-flight weather briefings and in-flight weather monitoring. |
| Maintenance MRO Integration | Receive ACARS maintenance messages and fault codes from aircraft for predictive maintenance workflows. |
| Passenger Service Messaging | Send gate change and operational update messages to aircraft for cabin crew announcements. |
| Airport Operations Management | Integrate OOOI flight data into airport management systems for terminal planning and resource allocation. |

## Integrations

| Name | Description |
|------|-------------|
| Airbus Skywise | Collins Aerospace joined the Digital Alliance for Aviation powered by Airbus Skywise for predictive maintenance and health monitoring. |
| SAP Aviation | ARINC flight operations data integrates with SAP IS-A for airline operations and financial management. |
| Amadeus | OOOI and flight status data integrates with Amadeus Altea CM for airline departure control and passenger services. |
| SITA | Complementary aviation communications network for shared messaging and airport data exchange services. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Collins Aerospace ARINC Messaging API](openapi/united-technologies-arinc-messaging-openapi.yml)

### JSON Schema

- [arinc-messaging-message-schema.json](json-schema/arinc-messaging-message-schema.json)
- [arinc-messaging-message-list-schema.json](json-schema/arinc-messaging-message-list-schema.json)
- [arinc-messaging-flight-schema.json](json-schema/arinc-messaging-flight-schema.json)
- [arinc-messaging-flight-list-schema.json](json-schema/arinc-messaging-flight-list-schema.json)
- [arinc-messaging-weather-data-schema.json](json-schema/arinc-messaging-weather-data-schema.json)
- [arinc-messaging-send-message-request-schema.json](json-schema/arinc-messaging-send-message-request-schema.json)

### JSON Structure

- [arinc-messaging-message-structure.json](json-structure/arinc-messaging-message-structure.json)
- [arinc-messaging-flight-structure.json](json-structure/arinc-messaging-flight-structure.json)
- [arinc-messaging-weather-data-structure.json](json-structure/arinc-messaging-weather-data-structure.json)

### JSON-LD

- [ARINC Messaging Context](json-ld/united-technologies-arinc-messaging-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Collins Aerospace ARINC Messaging API](capabilities/shared/arinc-messaging.yaml) — 4 operations for messages, flights, and weather

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Aviation Operations](capabilities/aviation-operations.yaml) | ARINC Messaging | 4 | Operations Controller, Dispatcher, Ground Operations Manager |

## Vocabulary

- [United Technologies Vocabulary](vocabulary/united-technologies-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [United Technologies Spectral Rules](rules/united-technologies-spectral-rules.yml) — 25 rules across 10 categories enforcing Collins Aerospace API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
