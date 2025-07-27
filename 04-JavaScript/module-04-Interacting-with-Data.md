# ✅ Module 4: Interacting with Data

---

## 🧠 Course Introduction

This module focuses on how web developers interact with data—both user‑generated and database‑stored—and how they leverage JavaScript and SQL to manage that data effectively.

---

## 🎯 Learning Objectives

After completing Module 4, you should be able to:

* Define data and common data types (especially in JavaScript)
* Explain CRUD: Create, Read, Update, Delete
* Describe MySQL and basic SQL syntax
* Demonstrate how to create, populate, query, and update a MySQL database

---

## 1. Understanding Data

* **Data**: Pieces of information a computer can store and process (e.g., form inputs, search queries)
* Examples:

  * Searching for "candle" (user input)
  * Review suggestions (derived from historical data)
  * Login/authentication (user credentials vs stored data)
  * Geolocation and pre‑filled address fields
  * Total cost calculation (price + tax + shipping)

---

## 2. Common Data Types (JavaScript Primitives)

| Data Type   | Example                    | Description                  |
| ----------- | -------------------------- | ---------------------------- |
| `string`    | `"hello"`                  | Textual data                 |
| `number`    | `42`, `3.14`               | Integers and decimals        |
| `boolean`   | `true`, `false`            | Logical values               |
| `undefined` | a variable not yet defined | Not assigned a value         |
| `null`      | `null`                     | Intentional absence of value |

---

## 3. CRUD Operations & SQL

Web developers typically work with four operations through SQL:

* **Create** – add new records
* **Read** – retrieve data from database
* **Update** – modify existing records
* **Delete** – remove records from tables

SQL is the structured query language used widely (especially in MySQL) to implement these operations.

---

## 4. SQL Essentials & MySQL Commands

### a) Create a Database

```sql
CREATE DATABASE movies;
```

### b) Create a Table

```sql
CREATE TABLE movie_info (
  movieNum INT,
  movieTitle VARCHAR(100),
  releaseYear YEAR,
  directorLastName VARCHAR(50),
  country VARCHAR(50),
  durationMin INT
);
```

### c) Insert Data

```sql
INSERT INTO movie_info (movieNum, movieTitle, releaseYear, directorLastName, country, durationMin)
VALUES
  (1, "Les Parapluies de Cherbourg", 1964, "Demy", "France", 91),
  (2, "In the Mood for Love", 2000, "Kar-wai", "Hong Kong", 98),
  (3, "Roma", 2018, "Cuarón", "Mexico", 135);
```

### d) Read Data

```sql
SELECT * FROM movie_info;

SELECT movieTitle, durationMin
FROM movie_info
WHERE country = 'Mexico';
```

### e) Update Data

```sql
UPDATE movie_info
SET releaseYear = 2000
WHERE movieTitle = 'In the Mood for Love';
```

*(Always include a WHERE clause to avoid unintended changes to all rows.)*

---

## 5. SQL Command Types

| Category                             | Commands                     | Purpose                             |
| ------------------------------------ | ---------------------------- | ----------------------------------- |
| **Data Definition Language (DDL)**   | `CREATE`, `ALTER`, `DROP`    | Define or modify database structure |
| **Data Manipulation Language (DML)** | `INSERT`, `UPDATE`, `DELETE` | Add, modify, or remove data         |
| **Data Query Language (DQL)**        | `SELECT`                     | Retrieve data                       |

---

## 6. Additional Notes

* SQL keywords aren't case-sensitive but best practice is to use **UPPERCASE** for keywords.
* Use **underscores** in table names and **camelCase** in column names (e.g. `durationMin`, `movieTitle`).
* End each SQL statement with a **semicolon (`;`)**.

---

## ✅ Summary

* JavaScript handles data types like strings, booleans, numbers, etc.
* CRUD operations—Create, Read, Update, Delete—are essential for database manipulation.
* MySQL syntax requires structured SQL commands to manage a database effectively.
* Practical use includes creating a table, inserting data, running SELECT queries, and updating records.

---
