## 💻 Db-ClassWork: PostgreSQL (SQL) Practicum 🚀

This repository contains practical SQL queries for working with **PostgreSQL**. The materials cover all stages of working with a relational database: from creating the schema and populating data to complex analytical queries, aggregation, and handling relationships.

---

### 📜 File Contents

| File | Description |
| :--- | :--- |
| **1. `pgsql` DDL/DML** | Database creation (`CREATE`/`DROP DATABASE`), table creation (`CREATE TABLE`), constraints (`PRIMARY KEY`, `NOT NULL`, `DEFAULT`). **CRUD**: Basic `INSERT`, `SELECT`, `ORDER BY`, `LIMIT`/`OFFSET`. |
| **2. `pgsql` Filtering (WHERE)** | Comparison operators, logical operators (`AND`, `OR`), pattern matching (`LIKE`/`ILIKE`), `BETWEEN`, `IN`, `IS NULL`. **DML**: `UPDATE` and `DELETE`. |
| **3. `pgsql` Relationships (JOINs)** | Creating 1:n relationships (`REFERENCES`, `ON UPDATE`/`DELETE`). Types of `JOINs` (`INNER`, `LEFT`, `FULL OUTER`). **Aggregation**: `COUNT`, `AVG`, `SUM`, `GROUP BY`, `HAVING`. |
| **4. `pgsql` Advanced Queries** | Working with the m:n relationship (`phones_to_orders`). **Subqueries** (`Scalar`, `IN`, `EXISTS`, `ALL`/`ANY`). **Conditional Logic**: `CASE WHEN`. **Query Combination**: `UNION`, `INTERSECT`, `EXCEPT`. |

---

### 🛠️ Key SQL Concepts

| Category | Primary Commands / Constructs | Purpose |
| :--- | :--- | :--- |
| **Schema (DDL)** | `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE` | Defining table structure and constraints (`PRIMARY KEY`, `CHECK`). |
| **Relationships** | `FOREIGN KEY`, `INNER JOIN`, `LEFT JOIN` | Ensuring data integrity and combining data from related tables. |
| **Filtering** | `WHERE`, `LIKE`/`ILIKE`, `BETWEEN`, `IN` | Selecting data based on specified conditions. |
| **Analytics** | `GROUP BY`, `HAVING`, `AVG`, `SUM` | Grouping rows and calculating aggregate metrics. |
| **Complexity** | Subqueries, `CASE WHEN`, `UNION` | Conditional logic, nested queries, and combining query results. |

---

### 🖼️ Schema Visualizations (ERD)

| File | Description |
| :--- | :--- |
| `hospital.erd`, `hospital.png` | Entity-Relationship Diagram (ERD) for the 1:n relationship example (Doctors : Patients). |
| `phones_sales.drawio`, `phones_sales.png` | DB Schema for the phone sales example, demonstrating 1:n and m:n relationships. |
