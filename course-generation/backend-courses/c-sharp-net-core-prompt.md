📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Backend Prompts Index`](./README.md) | [`📖 Course Output: C# + .NET Core`](https://github.com/worapha05/backend-courses/blob/main/c-sharp-net-core/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are an Enterprise Solutions Architect and Senior .NET Developer. Help me create a complete "Zero to Expert" self-learning bootcamp for C# and .NET Core (ASP.NET Core Web API) tailored for Modern Full-stack Developers.

# Target Structure
Generate all files inside a folder named `/c-sharp-net-core`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎีและแนวคิดการออกแบบสถาปัตยกรรมอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่าง C# ระดับ Production-ready ที่จัดโครงสร้างอย่างเป็นระเบียบ
3. `LAB.md`: โจทย์ทดสอบการพัฒนาและแก้ปัญหาระบบในชีวิตจริงเป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Modern C# & Core .NET)
- Modern C# syntax (C# 12+ features like Primary Constructors, Records, and Pattern Matching).
- LINQ (Language Integrated Query): Method syntax vs Query syntax, Deferred Execution, and data transformations.
- Object-Oriented Programming (OOP) in C#: Interfaces, Abstract Classes, Dependency Injection (DI) basics, and Exception Handling (Middleware-level).

## 2. Intermediate Level (ASP.NET Core Web API & Databases)
- Building Web APIs: Controllers (`[ApiController]`) vs Minimal APIs, Routing, and Model Binding.
- Data Persistence: **Entity Framework Core (EF Core)**, DbContext configuration, Code-First Migrations, and Managing Database Connections (PostgreSQL/SQL Server).
- Web Integration: Configuring CORS, Middleware Pipeline execution, Validation using FluentValidation, and JWT Authentication/Authorization.

## 3. Expert Level (Enterprise Security, Scale, & Clean Architecture)
- Advanced Security: **Role-Based Access Control (RBAC)**, Policy-based Authorization, and Token validation mechanics.
- High-Performance ORM: Optimizing EF Core queries, solving the N+1 problem (`Include` vs `Select`), AsNoTracking, and handling heavy asynchronous tasks with `async/await` and `Task.WhenAll`.
- Enterprise Operations: Structured Logging (using Serilog for Audit Logs), Background Tasks using `IHostedService`/BackgroundWorker, and highly efficient **Excel Data Exporting** using EPPlus or ClosedXML.
- Architecture Pattern: Structuring the solution using **Clean Architecture** or Onion Architecture (Separating Domain, Application, Infrastructure, and Web API projects).
```
