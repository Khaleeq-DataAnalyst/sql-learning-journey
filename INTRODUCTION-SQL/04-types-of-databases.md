# Types of Databases

There are mainly **two types** of databases:

1. **Relational Database** (SQL)
2. **Non-Relational Database** (NoSQL)

---

## 1. Relational Database

A relational database stores data in the form of **tables**, and **relationships** exist between those tables.

### Key Features

- Stores data in tables (rows and columns)
- Uses **SQL language**
- Follows **strict rules** — for example, if a column has the `INT` data type, you cannot store text in it
- Data is **structured** — every row has the same columns and same data types

### Examples of Relational Databases

- MySQL
- PostgreSQL
- SQL Server
- Oracle
- SQLite

### Example Table

```
Customers Table:
┌────────────┬──────────┬──────────┐
│ CustomerID │ Name     │ City     │
├────────────┼──────────┼──────────┤
│ 1          │ Ali      │ Lahore   │
│ 2          │ Sara     │ Karachi  │
│ 3          │ Ahmed    │ Dubai    │
└────────────┴──────────┴──────────┘
```

---

## 2. Non-Relational Database (NoSQL)

A non-relational database stores data in a **flexible format** — it does not follow fixed rules.

### Key Features

- Does **not** store data in tables
- Uses its **own query language** (not SQL)
- Data is **unstructured or semi-structured** — every row may have different columns and data types
- Highly flexible
- Highly **scalable** for big data

### Examples of Non-Relational Databases

- MongoDB
- Cassandra
- Redis
- Firebase
- DynamoDB

### Why is NoSQL an Umbrella Term?

NoSQL has several types because it covers many different storage approaches:

| Type | Example |
|---|---|
| Document | MongoDB |
| Key-Value | Redis |
| Column-family | Cassandra |
| Graph | Neo4j |

---

## SQL vs NoSQL — Quick Comparison

| Feature | SQL (Relational) | NoSQL (Non-Relational) |
|---|---|---|
| Data Format | Tables | Documents / JSON / Key-Value |
| Schema | Fixed (strict) | Flexible |
| Language | SQL | Own query language |
| Best For | Structured data | Unstructured data |
| Examples | SQL Server, MySQL | MongoDB, Cassandra |

---

## Key Takeaway

> Relational databases follow strict structures and are used where data accuracy is critical (banks, e-commerce, hospitals). Non-relational databases are flexible and used where huge volumes of varied data need to be handled (social media, IoT, real-time apps).

---

