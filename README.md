# Swiggy Power Query ETL – Conditional Columns, Merge & Append

## 📌 Project Overview
This project demonstrates a complete ETL workflow using Excel Power Query on a Swiggy restaurant dataset.

The focus is on conditional logic, row-level transformations, index columns, and combining datasets using Merge and Append operations.

---

## 🎯 Objectives
- Create conditional columns using IF–ELSE logic
- Apply row-level transformations
- Add index columns for row identification
- Merge tables using join logic
- Append tables with similar structure
- Prepare analysis-ready dataset

---

## 🛠️ Tools Used
- Microsoft Excel
- Power Query Editor

---

## 🔧 Transformations Applied

### Conditional Column
Created new columns using logical conditions.

Example:
- Rating >= 4 → High Rated
- Else → Average Rated

### Row-Level Operations
Applied logic independently to each row.

### Index Column
Added unique row identifiers for tracking.

---

## 🔗 Merge Queries (SQL Join Concept)
Merged datasets using common columns.

Join types demonstrated:
- Inner Join
- Left Join
- Full Outer Join

---

## ➕ Append Queries (SQL UNION Concept)
Combined rows from multiple tables with identical structure.

---

## 🔄 Merge vs Append

| Feature | Merge | Append |
|---|---|---|
| Combines | Columns | Rows |
| Requirement | Matching key | Same structure |
| SQL Equivalent | JOIN | UNION |

---

## 🚀 Key Outcomes
- Implemented SQL-style joins in Power Query
- Applied conditional logic for categorization
- Combined datasets using merge and append
- Created analysis-ready Swiggy dataset

