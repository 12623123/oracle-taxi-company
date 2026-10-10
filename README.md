# Taxi Company Management Database

## Project Overview

This project represents a relational database designed to manage the operations of a taxi company. It organizes information about customers, drivers, vehicles, prices, routes, orders, payments, and customer reviews.

The database is implemented using Oracle SQL and is intended to demonstrate database design, table creation, data manipulation, and SQL queries.

## Database Structure

The database consists of the following eight tables:

1. **Customers** (`Клиенти`) — stores customer information.
2. **Drivers** (`Шофьори`) — stores driver information.
3. **Vehicles** (`Автомобили`) — stores information about the company's vehicles.
4. **Prices** (`Цени`) — stores pricing information.
5. **Routes** (`Маршрути`) — stores route information.
6. **Orders** (`Поръчки`) — stores taxi orders.
7. **Payments** (`Плащания`) — stores payment information.
8. **Reviews and Comments** (`Оценки_и_коментари`) — stores customer ratings and feedback.

## Technologies Used

- Oracle Database
- Oracle SQL
- SQL scripts for database creation and sample data insertion

## Repository Structure

```text
oracle-taxi-company/
├── README.md
├── docs/
│   ├── original-document.docx
│   └── original-document.txt
├── sql/
│   ├── 01_create_tables.sql
│   └── 02_sample_data.sql
└── queries/
    └── queries.md
```

## Getting Started

To set up the database:

1. Open Oracle SQL Developer or another compatible Oracle SQL environment.
2. Connect to your Oracle Database instance.
3. Execute `sql/01_create_tables.sql` to create the database tables.
4. Execute `sql/02_sample_data.sql` to insert the sample data.
5. Use the SQL queries documented in the `queries/` directory to explore the database.

Execute the scripts in the specified order.

## Documentation

The `docs/` directory contains the original project documentation in Bulgarian.

The `queries/` directory contains descriptions of the SQL queries associated with the project.

## Project Purpose

The purpose of this project is to apply database design and SQL programming concepts to a practical business scenario. It demonstrates how a relational database can organize and manage the main operations of a taxi company.

## Notes

- The table and column names may remain in Bulgarian, as defined in the original SQL scripts.
- The sample data should be checked to ensure that referenced records exist before executing all insert statements.
- The project documentation reflects the original academic project.

---

**Project:** Taxi Company Management Database  
**Database Technology:** Oracle SQL
