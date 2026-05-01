# Types of SQL Commands

SQL commands are divided into **5 main categories** based on their purpose.

```
                   SQL COMMANDS
                       │
   ┌───────┬───────────┼───────────┬───────┐
   │       │           │           │       │
  DDL     DML         DQL         DCL     TCL
```

---

## 1. DDL — Data Definition Language

**DDL** stands for **Data Definition Language**. It is used to **create, modify, and delete database structure** like tables, schemas, and databases.

### Commands

- `CREATE`
- `ALTER`
- `DROP`
- `TRUNCATE`

### Important Point

> DDL commands are **auto-commit**, which means once the command is run, it **cannot be reversed** in most cases.

---

## 2. DML — Data Manipulation Language

**DML** stands for **Data Manipulation Language**. It is used to **manipulate the data** stored in tables — such as inserting, updating, and deleting records.

### Commands

- `INSERT`
- `UPDATE`
- `DELETE`

---

## 3. DQL — Data Query Language

**DQL** stands for **Data Query Language**. It is used to **retrieve data** from a database. It only reads data and does **not modify** it.

### Command

- `SELECT`

---

## 4. DCL — Data Control Language

**DCL** stands for **Data Control Language**. It is used to **control access and permissions** in the database, defining what actions users are allowed to perform.

### Commands

- `GRANT`
- `REVOKE`

---

## 5. TCL — Transaction Control Language

**TCL** stands for **Transaction Control Language**. It is used to **manage transactions** in a database, ensuring that operations are either fully completed or fully undone.

### What is a Transaction?

> A transaction is a **group of operations** that are executed completely or not at all.

### Commands

- `COMMIT`
- `ROLLBACK`
- `SAVEPOINT`

---

## Quick Summary Table

| Category | Full Form | Purpose | Commands |
|---|---|---|---|
| DDL | Data Definition Language | Define structure | CREATE, ALTER, DROP, TRUNCATE |
| DML | Data Manipulation Language | Manipulate data | INSERT, UPDATE, DELETE |
| DQL | Data Query Language | Retrieve data | SELECT |
| DCL | Data Control Language | Control access | GRANT, REVOKE |
| TCL | Transaction Control Language | Manage transactions | COMMIT, ROLLBACK, SAVEPOINT |

---

## Note on Command Usage

The actual usage and syntax of these commands will be covered in upcoming topics — this file focuses on **what each category is and which commands belong to it**, which is commonly asked in interviews.

---

