# Populus

> Digital Twin Platform for Human-Centered Environments

Populus is a geospatial asset management platform based on Digital Twin technology. Its purpose is to create digital representations of real-world environments, connecting physical spaces with structured information to improve monitoring, maintenance, and decision-making.

By creating a bridge between the physical and digital worlds, Populus enables organizations to better understand, operate, and preserve the environments where people live, work, and interact.

---

## Project Background

Populus originated from a geospatial asset management project I worked on during my time at my current research center, within the Data Analysis and Information Management division.

My contribution to that project involved refactoring parts of the frontend architecture to modern React patterns, including the migration to Hooks. While this provided valuable insight into the domain, the technical challenges involved, and the potential applications of the idea, the project's requirements, architecture, and product decisions were already defined.

This project was created as an opportunity to revisit the same problem space from scratch, with full control over the product vision, architecture, and technical decisions.

The goal is not to reproduce the original solution, but to rethink and expand the concept into a flexible Digital Twin platform designed around the relationship between people and the environments they use.

Additionally, the project is part of the Business Plan presented by Tecnun eRacing Formula Student Team during the 2025–2026 Formula Student season, competing in Formula Student Czech Republic and Formula Student Germany.

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

As environments become larger and more complex, organizations require better ways to understand the physical spaces they manage and the elements contained within them.

---

## The Solution

Populus provides a digital representation of physical environments through an interactive map-based platform.

The system is designed around a flexible and scalable asset management architecture, allowing any physical element to be represented as a georeferenced asset with its own properties, condition, history, and maintenance workflow.

Instead of being limited to a specific industry, Populus acts as a general-purpose framework for creating Digital Twins of different environments.

The objective is to create a reusable foundation capable of adapting to different scenarios and operational needs.

For the initial development stage, three scenarios are being explored to demonstrate the adaptability of the platform:

* **Urban Environment:** Management of public spaces, street furniture, and city infrastructure.
* **Airport Infrastructure:** Representation of operational elements, signage, and maintenance assets.
* **Natural Environment:** Monitoring of biological and environmental assets.

However, the same architecture can be extended to many other domains, including:

* Railway infrastructure.
* Motorsport circuits.
* Industrial facilities.
* Smart city applications.
* Large-scale facilities.
* Any environment requiring asset location, monitoring, and maintenance management.

The platform enables users to understand:

* Which assets exist.
* Where they are located.
* Their current condition.
* Which defects or incidents affect them.
* Which maintenance tasks are pending or in progress.

By combining geospatial information, asset lifecycle management, and operational workflows, Populus provides the foundation for creating Digital Twins focused on real-world environments and the people who interact with them.

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

## Initial Use Cases

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

One of the main evolution paths for Populus is the integration of Computer Vision systems capable of automatically detecting assets from video footage captured by vehicles.

The objective is to partially automate the creation and updating of georeferenced inventories, reducing the need for manual inspections and improving data quality.

The detection system is designed as an independent component capable of feeding the Digital Twin with new information while keeping human validation as part of the workflow.

---

## Technologies

### Frontend

* React
* Vite
* TypeScript

### Backend

* Python
* FastAPI

### Database

* PostgreSQL
* PostGIS

### Infrastructure

* Docker

---

## Project Status

🚧 Active Development.

Populus is a personal project developed as a technical portfolio project and as a proof of concept for a scalable Digital Twin platform focused on understanding, managing, and improving physical environments.

The project is continuously evolving, exploring new applications and possible integrations between geospatial systems, data management, and intelligent detection technologies.

---

## License

MIT License
