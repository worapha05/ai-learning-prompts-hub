# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Database Administrator (DBA), Senior Backend Architect, and Data DevOps Engineer. Help me create a complete "Zero to Expert" self-learning bootcamp for Database Migrations and Schema Evolution, focusing on Prisma Migration, Knex.js, and Liquibase tools to manage database versions safely in production environments.

# Target Structure
Generate all files inside a folder named `/database-migrations`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี ปรัชญาการทำ Database Version Control และความแตกต่างระหว่าง Declarative กับ Imperative Migration อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Schema และไฟล์ Migration (เช่น schema.prisma, knex migration files, หรือ liquibase changelogs)
3. `LAB.md`: โจทย์ทดสอบการปรับโครงสร้างตารางข้อมูลขนาดใหญ่ (Schema Refactoring) การย้ายข้อมูล (Data Migration) และการแก้ปัญหา Migration Conflict เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และสคริปต์แก้ไขอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Migration Foundations & Local Schemas)
- Why Database Migration?: The problem of manual SQL scripts. Understanding Database State, History Tracking Tables (e.g., `_prisma_migrations`, `knex_migrations`).
- Declarative vs Imperative: Comparing Prisma's Schema-driven approach (Source of truth is `schema.prisma`) vs Knex's step-by-step code approach (`up` and `down` functions).
- Basic CLI Workflows: Generating, running, and checking migration status locally (`prisma migrate dev`, `knex migrate:make`, `knex migrate:latest`).

## 2. Intermediate Level (Advanced Schema Changes & Data Migrations)
- Breaking Changes Isolation: Adding columns with non-null constraints, dropping tables safely, and managing foreign key constraints without locking local application flows.
- Data vs Schema Migration: Separating structural alterations from data seedings/transformations. Writing custom data migration scripts to transform existing records into new formats during deployment.
- Team Collaboration & Conflicts: Resolving migration history drifts and merge conflicts when multiple developers generate concurrent migrations in Git branch workflows (Fixing out-of-sync database states).

## 3. Expert Level (Enterprise Zero-Downtime Blue-Green Deployments & Rollbacks)
- Zero-Downtime Database Refactoring: Mastering the **Expand and Contract Pattern** (Parallel Run) for column renames or structural splits to ensure old and new application versions can run simultaneously.
- Advanced Enterprise Tooling (Liquibase): Designing Database-Agnostic changelogs, tracking changesets, utilizing Preconditions, and managing complex rollbacks in multi-environment setups (Dev, Staging, Prod).
- Production Operations & CI/CD: Integrating migrations securely into deployment pipelines (e.g., GitHub Actions, Jenkins). Handling large table locks using online schema change strategies, mitigating migration failures mid-way, and implementing post-deployment verification gates.
```