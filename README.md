# Sales Operations Database System | SQL Server

Project Overview
This project is a comprehensive database system designed for a restaurant operation named "Papa Georgios" (PG). The system captures and manages various aspects of the restaurant’s business, including sales, employee management, inventory tracking, customer loyalty programs, and operational data. It was developed as part of the CS 488 Database Systems course.

The project is divided into three main phases:

Entity Relationship Diagram (ERD) Design
Physical Database Implementation in SQL Server
Data Population and CRUD Operations
Project Features
Part 1: Entity Relationship Diagram (ERD) Design
Objective: Create a conceptual database design representing the restaurant’s business processes.
Scope:
Captures sales and detailed order information.
Models employee roles, hierarchies, and job history.
Includes menu items with categories, sizes, prices, and historical prices.
Tracks customer loyalty points, vendor supplies, and food preparation stages.
Applies Crow's Foot Notations for clarity.
Ensures data integrity using normalization up to 3NF.
Part 2: Physical Database Implementation
Objective: Translate the ERD into a physical database in Microsoft SQL Server.
Implementation Details:
Tables, relationships, and constraints are created using SQL code.
Primary keys, foreign keys, and data types are defined and enforced.
Cascading rules for ON DELETE and ON UPDATE operations ensure consistency.
SQL code is organized in execution order to respect integrity rules.
Part 3: Data Population and CRUD Operations
Objective: Populate the database with realistic sample data and perform CRUD operations.
Key Queries:
Total quantity and dollar amount sold for each category.
Total quantity and dollar amount sold for subcategories.
Pizza-specific sales data.
Average number of pizzas per order.
Average price per category.
Customers who ordered pizza or pasta.
Products with sales above the average quantity sold.
Menu items and their details.
Data Integrity: Ensures that all sample data complies with the defined constraints and relationships.
Installation and Usage
Prerequisites
Microsoft SQL Server installed on your machine.
SQL Server Management Studio (SSMS) for managing the database.
Setup Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/restaurant-database-system.git
cd restaurant-database-system
Execute SQL Scripts:

Navigate to the SQL folder.
Run scripts in the following order:
create_tables.sql: Creates database tables and relationships.
insert_data.sql: Populates the database with sample data.
queries.sql: Contains SELECT, UPDATE, and DELETE operations.
Verify Data:

Use queries.sql to test and explore the database.
Adjust sample data if needed to reflect additional scenarios
