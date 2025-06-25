# RTO-Database
This project is a PostgreSQL-based relational database system designed to manage and streamline the core operations of an RTO (Regional Transport Office). It handles essential tasks such as vehicle registration, license issuance, ownership records, and officer management through a normalized and scalable schema.
📌 Features
Vehicle registration and license record management
Owner and vehicle relationship tracking
Normalized schema for minimal redundancy
Functional dependencies and relational modeling
Optimized SQL queries for real-world use cases and reporting
ER Diagram and Relational Model diagrams included
🧩 Technologies Used
PostgreSQL – Database system
pgAdmin 4 – GUI for managing PostgreSQL databases
Standard SQL
DBMS concepts (Normalization, Functional Dependencies, Relational Algebra)
Python (for optional query execution)
🛠️ How to Run
Install PostgreSQL and pgAdmin 4 if not already installed.
Open pgAdmin 4 and create a new database (e.g., rto_db).
Use the Query Tool in pgAdmin to:
Run RTO DDL Statements.sql to create the schema.
Run RTO Data.sql to insert sample records.
Run queries from RTO Query Statements.sql to test functionality.
(Optional) Use RTO API (python).py to interact with the database programmatically via Python.
