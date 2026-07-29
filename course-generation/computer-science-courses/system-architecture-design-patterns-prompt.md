📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Computer Science Prompts Index`](./README.md) | 📖 [`Course Output: System Architecture & Design Patterns`](https://github.com/worapha05/computer-science-courses/blob/main/system-architecture-design-patterns/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Software Architect, Enterprise Systems Designer, and Technical Fellow specializing in Distributed Architecture. Help me create a complete "Zero to Expert" self-learning bootcamp for System Architecture and Design Patterns tailored for senior-level engineers and tech leads.

# Target Structure
Generate all files inside a folder named `/system-architecture-design-patterns`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี คอนเซปต์การออกแบบสถาปัตยกรรม และแนวคิดการเลือก Pattern อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการ 구현 Design Patterns ที่สำคัญ (ใช้ภาษา TypeScript, Go, หรือ Java แบบ Clean Code) พร้อมไดอะแกรมจำลองโครงสร้างไฟล์
3. `LAB.md`: โจทย์ทดสอบการออกแบบสถาปัตยกรรมระบบขนาดใหญ่ (System Design Interview Style) และการ refactor โค้ดที่ซับซ้อน เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างระบบ และโค้ดอย่างครบถ้วน

## 1. Beginner Level (Software Design Principles & Creational Patterns)
- Object-Oriented Design Foundations: Deep dive into **SOLID Principles** (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) with practical anti-patterns.
- Creational Design Patterns: Implementation and production use cases of **Singleton** (and its thread-safety implications), **Factory Method**, **Abstract Factory**, and **Builder** patterns.
- Architectural Basics: Understanding Layered (N-Tier) Architecture, Monolithic code structuring, and Separation of Concerns (SoC).

## 2. Intermediate Level (Structural & Behavioral Patterns)
- Structural Design Patterns: Code implementation of **Adapter**, **Decorator** (Extending behavior without inheritance), **Facade** (Simplifying complex subsystems), and **Proxy** patterns.
- Behavioral Design Patterns: Mastering **Observer** (Event-driven baseline), **Strategy** (Interchangeable algorithms), **State**, and **Command** patterns.
- Architectural Patterns: Model-View-Controller (MVC) vs Model-View-ViewModel (MVVM) and introduction to Hexagonal Architecture (Ports and Adapters).

## 3. Expert Level (Enterprise Clean Architecture & Distributed Systems Design)
- Enterprise Code Architecture: Deep dive into **Clean Architecture** (Robert C. Martin) and Domain-Driven Design (DDD) concepts (Bounded Contexts, Aggregates, Entities, Value Objects).
- Distributed Systems Architecture: Core architectural patterns: **CQRS** (Command Query Responsibility Segregation), **Event Sourcing**, and microservices orchestration via the Saga Pattern.
- System Design Fundamentals: Analyzing system trade-offs using the **CAP Theorem** (Consistency, Availability, Partition Tolerance), Designing for High Availability, Load Balancing strategies, Caching topologies, and Data Replication models.
- Resilience Patterns at Scale: Architectural implementation of Circuit Breakers, Bulkheads, Rate Limiters, and Graceful Degradation across distributed services.
```
