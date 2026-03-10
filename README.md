Here’s a full, detailed `README.md` for your Oil Extraction Management project:

````markdown
# Oil Extraction Management System

## Overview
The Oil Extraction Management System is a Java console-based application designed to manage operations in an oil extraction environment. It allows users to manage oil rigs, track extraction records, maintain maintenance logs, and manage maintenance crews efficiently using Hibernate ORM with a PostgreSQL database.

## Features
- **Manage Oil Rigs:** Add, update, and view oil rigs.
- **Track Extraction Records:** Record and monitor oil extraction activities.
- **Maintenance Records:** Log and view maintenance tasks for rigs.
- **Maintenance Crew Management:** Register crews, update availability, and view the most active crews.
- **Reporting:** Generate reports on crew workload and rig maintenance.

## Technologies Used
- **Programming Language:** Java
- **ORM Framework:** Hibernate
- **Database:** PostgreSQL
- **Build Tool:** Maven
- **IDE:** Any Java IDE (IntelliJ, Eclipse, VS Code)

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/oil-extraction-management.git
````

2. **Database Setup**

   * Install PostgreSQL.
   * Create a database named `oilextraction_db`.
   * Update `hibernate.cfg.xml` with your database username, password, and URL.

3. **Build and Run the Project**

   ```bash
   mvn clean compile exec:java
   ```

   * Follow the console menu to navigate the system.

## Usage

* Navigate the main menu:

  ```
  1. Manage Oil Rigs
  2. Manage Extraction Records
  3. Manage Maintenance Records
  4. Manage Maintenance Crews
  5. Exit
  ```
* Submenus allow CRUD operations for rigs, records, and crews.
* View reports for most active crews and maintenance statistics.

## Project Structure

* `com.darren485` – Contains entities and Hibernate utility.
* `com.darren485.dao` – Data Access Objects for database operations.
* `com.darren485.menu` – Console menu classes for user interaction.
* `resources/hibernate.cfg.xml` – Hibernate configuration.

## License

This project is licensed under the MIT License.

```

If you want, I can also **write a version with badges, setup screenshots, and example usage output** to make it look professional on GitHub. Do you want me to do that?
```
