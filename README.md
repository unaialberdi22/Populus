# Izarbide

> Digital Twin Asset Management Platform

Izarbide is a geospatial asset management platform based on Digital Twin technology. Its purpose is to digitally represent outdoor environments and facilitate the monitoring, maintenance, and operation of distributed infrastructure through a single centralized source of information.

---

## Project Background

Izarbide originated from a geospatial asset management project I worked on during my time at a software company.

My contribution to that project involved refactoring parts of the frontend architecture to modern React patterns, including the migration to Hooks. While this provided valuable insight into the domain and the technical challenges involved, the project's requirements, architecture, and product decisions were already defined.

This project was created as an opportunity to revisit the same problem space from scratch, with full control over the product vision, architecture, and technical decisions. The goal is not to reproduce the original solution, but to rethink and expand the concept into a more flexible Digital Twin platform capable of supporting multiple environments such as urban infrastructure, airport facilities, and natural ecosystems.

Additionally, the project is part of the Business Plan presented by Tecnun eRacing Formula student team during the 2025–2026 Formula Student season, competing in Formula Student Czech Republic and Formula Student Germany.

---

## The Problem

Managing distributed assets often relies on outdated inventories, fragmented documentation, and manual processes that make it difficult to locate, monitor, and maintain infrastructure efficiently.

This typically results in:

* Difficulty locating assets.
* Limited traceability of incidents and maintenance activities.
* Duplicate work and inefficiencies.
* Increased operational costs.
* Longer intervention times.
* Information scattered across multiple systems.

---

## The Solution

Izarbide centralizes asset information within an interactive map that acts as a digital representation of the physical environment.

The platform enables users to know at any time:

* Which assets exist.
* Where they are located.
* Their current condition.
* Which defects or incidents affect them.
* Which maintenance tasks are pending or in progress.

---

## Main Features

### Asset Management

Register and visualize georeferenced assets using precise geographic coordinates.

Each asset can store:

* Unique identifier.
* Asset type.
* Current status.
* Photographs.
* Technical information.
* Maintenance history.
* Custom metadata.

---

### Defect & Incident Management

Assets can have associated defects or incidents that reflect their real-world condition.

Each defect includes:

* Defect type.
* Severity level.
* Description.
* Photographic evidence.
* Detection date.
* Resolution status.

---

### Task Management

Defects and incidents can generate maintenance tasks assigned to operators.

Each task includes:

* Assigned operator.
* Priority level.
* Due date.
* Status.
* Notes and observations.
* Intervention evidence.

---

### User Management

The platform supports different user roles.

#### Administrators

* Global system management.
* Asset management.
* Incident management.
* Task assignment.

#### Operators

* View assigned tasks.
* Update task status.
* Register interventions.
* Report new incidents.

---

### Interactive Map

The map is the core component of the platform.

It allows users to visualize:

* Assets.
* Incidents.
* Tasks.
* Operational status.
* Contextual information.

---

## Use Cases

The architecture is designed to support multiple sectors.

### Urban Environments

* Traffic signs.
* Street lights.
* Benches.
* Waste bins.
* Urban infrastructure.

### Airport Infrastructure

* Signage systems.
* Airfield lighting.
* Runway equipment.
* Operational infrastructure.

### Natural Environments

* Trees.
* Biological monitoring points.
* Environmental observation assets.
* Ecological inventories.

---

## Workflow

```text
Inspection
    ↓
Incident Detection
    ↓
Defect Registration
    ↓
Task Creation
    ↓
Operator Assignment
    ↓
Intervention
    ↓
Status Update
    ↓
History & Traceability
```

---

## Future Vision

One of the planned evolution paths for Izarbide is the integration of Computer Vision systems capable of automatically detecting assets from video footage captured by vehicles.

The goal is to partially automate the creation and updating of georeferenced inventories, reducing the need for manual inspections and improving data quality.

---

## Technologies

### Frontend

* React-Vite Typescript

### Backend

* Python FastAPI

### Database

* PostgreSQL
* PostGIS

### Infrastructure

* Docker

---

## Project Status

🚧 Active Development.

Izarbide is a personal project developed both as a technical portfolio project and as a proof of concept for a scalable Digital Twin solution focused on geospatial asset management and infrastructure maintenance.

---

## License

MIT License
