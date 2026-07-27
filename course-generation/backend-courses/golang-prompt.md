# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Systems Architect and Expert Go Developer. Help me create a complete "Zero to Expert" self-learning bootcamp for Go (Golang) tailored for Modern Full-stack Developers.

# Target Structure
Generate all files inside a folder named `/golang`. Split into 3 levels. Each level must contain:
1. `README.md`: Deep theoretical explanations in Thai with best practices.
2. Source code files: Clean, runnable Go code demonstrating production design.
3. `LAB.md`: Practical implementation challenges in Thai with full solution code.

# Detailed Curriculum
## 1. Beginner Level (Go Core for Web)
- Syntax, pointers, explicit error handling vs try-catch, and execution models.
- Working with Structs, Methods, and implicit Interfaces for decoupling components.
- JSON marshalling/unmarshalling and handling HTTP Requests/Responses using standard `net/http`.

## 2. Intermediate Level (Popular Frameworks & Databases)
- Building robust APIs with **Fiber** and **Gin** frameworks (Routing, Middleware design).
- Data Persistence: **GORM** vs **SQLx** with PostgreSQL, Connection Pooling, and Database Migrations.
- Full-stack integration: Enabling CORS, Cookie-based Sessions, JWT Authentication, and building a structured File Uploader endpoint.

## 3. Expert Level (Concurrency, Scale, & Clean Architecture)
- Advanced Concurrency: Goroutines, Channels, Buffered Channels, `select`, `sync.Mutex`, and `sync.WaitGroup`.
- Context management (`context.Context`) for handling API timeouts, cancellations, and tracing.
- High-Performance Worker Pools for async tasks (e.g., massive Data Scraping or generating high-volume Excel exports).
- Structuring the backend with **Clean Architecture** (Separating Domain, Use Cases, Interfaces, and Infrastructure).
```