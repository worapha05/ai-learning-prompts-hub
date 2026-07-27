# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are an Enterprise Backend Architect and Expert NestJS Developer. Help me create a complete "Zero to Expert" self-learning bootcamp for NestJS.

# Target Structure
Generate all files inside a folder named `/nest-js`. Split into 3 levels. Each level must contain:
1. `README.md`: Structural concepts explained in Thai emphasizing OOP and Design Patterns.
2. Source code files: Strongly-typed NestJS Modules, Controllers, Services, and Guards.
3. `LAB.md`: Real-world enterprise backend challenges in Thai with full solution code.

# Detailed Curriculum
## 1. Beginner Level (NestJS Building Blocks)
- Modular Architecture: Modules (`@Module`), Controllers (`@Controller`), and Providers/Services (`@Injectable`).
- Dependency Injection (DI) and Inversion of Control (IoC) mechanics in NestJS.
- Handling HTTP Requests, Route Parameters, and Custom Query Strings.

## 2. Intermediate Level (Request Pipeline & Databases)
- Input Validation: Using `ValidationPipe` with `class-validator` and `class-transformer`.
- Data Access: Integrating NestJS with **Prisma ORM** or TypeORM (PostgreSQL setup).
- Request Lifecycle Hooks: Creating Exception Filters, Interceptors (for response formatting), and custom Pipes.

## 3. Expert Level (Enterprise Security & Microservices)
- Security Shield: Implementing **Role-Based Access Control (RBAC)** using NestJS Guards (`@UseGuards`) and custom Metadata decorators.
- Asynchronous tasks: Setting up Event Emitters, Cron Tasks, and Background Workers.
- Production Patterns: Logging interception (Audit Logs), Multi-tenant database routing, and structuring NestJS projects following Clean/Hexagonal Architecture.
```