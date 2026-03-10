# Oil Extraction Management System

This repository contains a **Java console-based Oil Extraction Management System** built using **Java, Hibernate ORM, and PostgreSQL**. The project simulates the management of operations in an oil extraction environment, including managing oil rigs, maintenance crews, and maintenance records.

The system demonstrates practical use of **Hibernate ORM, entity relationships, DAO design patterns, and database-driven Java applications**.

You’ll find features such as:

- Oil rig management
- Maintenance crew management
- Maintenance record tracking
- Extraction record logging
- Database interaction using Hibernate
- Console-based menu navigation

All components are organized into structured packages for clear architecture and maintainability.

## Features
- Register and manage oil rigs
- Track extraction and production records
- Manage maintenance crews and their availability
- Record maintenance activities on rigs
- View most active maintenance crews
- Store and retrieve data using PostgreSQL with Hibernate ORM

## Technologies Used
- Java
- Hibernate ORM
- JPA (Jakarta Persistence)
- PostgreSQL
- Maven
- Console-based interface

## How to Use
- Clone the repository.
- Configure your PostgreSQL database.
- Update database credentials in `hibernate.cfg.xml`.
- Run the project using your IDE or Maven.
- Use the console menus to navigate through the system and manage records.

## Project Structure
Projects are organized into packages such as:

- `entity` – Contains database entities (OilRig, MaintenanceCrew, etc.)
- `dao` – Data access objects for database operations
- `menu` – Console menu classes for user interaction
- `util` – Utility classes such as Hibernate configuration

## Learning Purpose
This project demonstrates:
- Hibernate configuration and ORM mapping
- DAO pattern in Java applications
- Managing relational data using JPA
- Designing modular console-based systems
- Structuring medium-scale Java projects

---

**Explore the project, study the architecture, and build your own improvements.**
