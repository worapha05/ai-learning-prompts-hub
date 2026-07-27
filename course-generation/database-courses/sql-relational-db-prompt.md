# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Database Architect and Expert Data Engineer specializing in relational database management systems. Help me create a complete "Zero to Expert" self-learning bootcamp for Relational Databases focusing on PostgreSQL and MySQL.

# Target Structure
Generate all files inside a folder named `/sql-relational-db`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี โครงสร้าง และแนวคิดสถาปัตยกรรมฐานข้อมูลอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices ในการออกแบบ
2. Source code files: ชุดคำสั่ง SQL ที่รันผ่าน DBMS ได้จริง (DDL/DML) มีการจัดโครงสร้างอย่างเป็นระเบียบ
3. `LAB.md`: โจทย์ทดสอบและการแก้ไขระบบจากกรณีศึกษาในชีวิตจริงเป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Database Foundations & SQL Core)
- Relational Database Model: Understanding Tables, Rows, Columns, Primary Keys (PK), Foreign Keys (FK).
- Data Types & Data Constraints: Selection of correct types, `NOT NULL`, `UNIQUE`, `CHECK`, and default values.
- Core SQL CRUD: Writing bulletproof `INSERT`, `SELECT`, `UPDATE`, and `DELETE` commands.
- Normalization Principles: Structuring schemas into 1NF, 2NF, 3NF, and relationship mapping (1:1, 1:M, M:M).

## 2. Intermediate Level (Advanced Querying & Performance)
- Multi-Table Joins: Comprehensive usage of `INNER JOIN`, `LEFT/RIGHT OUTER JOIN`, `FULL OUTER JOIN`, and `SELF JOIN`.
- Aggregations & Grouping: Utilizing `GROUP BY` and `HAVING` combined with aggregate functions (`SUM`, `AVG`, `COUNT`).
- Complex Query Substructures: Subqueries, Nested Queries, and Common Table Expressions (CTEs) using the `WITH` clause.
- Schema Version Control: Best practices for Database Migrations in modern applications.

## 3. Expert Level (Enterprise Scale, Optimization & Operations)
- Advanced Analytics: Window Functions (`ROW_NUMBER()`, `RANK()`, `LEAD()`, `LAG()`) over partitions.
- Concurrency & Transactions: ACID properties deep dive, Transaction Isolation Levels, Row-Level Locking (`SELECT ... FOR UPDATE`), and preventing Race Conditions.
- Query Performance Tuning: Analysis of slow queries using `EXPLAIN ANALYZE` (PostgreSQL) and `EXPLAIN` (MySQL).
- Strategic Indexing: B-Tree Indexes, Composite Indexes, Partial Indexes, Covering Indexes, and Full-Text Search engineering.
- Server-Side Logic: Functions, Stored Procedures, and Triggers design using PL/pgSQL and MySQL Stored Programs.
```