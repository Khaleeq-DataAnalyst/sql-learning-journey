# Database Structure

A database follows a **hierarchical structure** — meaning each level contains the next level inside it.

## The Hierarchy

```
SERVER
  └── DATABASE (multiple databases possible)
        └── SCHEMA (group of related tables)
              └── TABLE
                    ├── COLUMNS
                    └── ROWS
                          └── CELL (row + column intersection)
```

---

## 1. Server

The first level is the **server** — a powerful computer (or software) where the entire database system runs.

A single server can host **multiple databases**.

---

## 2. Database

After the server comes the **database**. A server can contain multiple databases.

Each database is independent — for example, an HR database and a Sales database both exist on the same server but do not mix data.

---

## 3. Schema

Inside a database, we have **schemas**.

A schema is actually a **group of related tables** that we give a specific name to — and that group is called a schema.

### Technical Definition

> A schema is a logical group inside a database that organizes related objects (like tables) under a specific name.

### Example

```
ECommerce_DB
├── Sales Schema
│   ├── Orders
│   ├── OrderDetails
│   └── Customers
└── Inventory Schema
    ├── Products
    └── Categories
```

---

## 4. Tables

After schemas come **tables**.

A table is a **structured collection of rows and columns**.

### Components of a Table

- **Columns** — each column has:
  - A name
  - A data type
  - Some constraints (rules)

- **Rows** — also called **tuples** or **records**.

- **Cell** — the intersection of a row and a column is called a **cell**.

---

## 5. Data Types

Each column must have a specific data type that defines what kind of value it can store.

| Data Type | Stores |
|---|---|
| INT | Whole numbers |
| DECIMAL | Decimal numbers |
| VARCHAR | Text |
| DATE | Dates |
| TIME | Time values |
| BIT | True / False (0 or 1) |

---

## Visual Example — E-commerce Customers Table

```
ECommerce_DB → Sales Schema → Customers Table

┌────────────┬──────────┬──────────┬─────────────┐
│ CustomerID │ Name     │ City     │ JoinDate    │
├────────────┼──────────┼──────────┼─────────────┤
│ 1          │ Ali      │ Lahore   │ 2024-01-15  │
│ 2          │ Sara     │ Karachi  │ 2024-03-22  │
│ 3          │ Ahmed    │ Dubai    │ 2025-06-10  │
└────────────┴──────────┴──────────┴─────────────┘

  ↑                         ↑
  │                         │
Column                  Row / Record / Tuple
(with data type)
```

---

## Key Vocabulary to Remember

- **Tuple / Record** = Row
- **Field** = Column
- **Cell** = Row + Column intersection
- **Schema** = Logical group of related tables

---

## Key Takeaway

> Every relational database follows the same structure: Server → Database → Schema → Table → Columns/Rows. Once you understand this hierarchy, working with any SQL-based database becomes easier.

---

