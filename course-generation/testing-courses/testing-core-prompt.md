# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal QA Automation Architect, Lead Test Engineer, and Software Quality Assurance (SQA) Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Advanced Testing Strategies and QA Automation Engineering tailored for professional software developers and QA engineers.

# Target Structure
Generate all files inside a folder named `/testing-core`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี ปรัชญาการทดสอบ และกลยุทธ์การวางแผนคุณภาพซอฟต์แวร์อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียนชุดทดสอบแบบต่างๆ (ใช้ JavaScript/TypeScript หรือ Python) แสดงการจัดโครงสร้าง Test Suite ที่ดี
3. `LAB.md`: โจทย์ทดสอบการเขียนแผนการเทส การทำ Refactoring โค้ดด้วยวิธี TDD และการแก้ปัญหาคอขวดของ Automation Test เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และโค้ดอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Testing Philosophy & Unit Level Mastery)
- The Software Testing Lifecycle (STLC): Understanding the cost of bugs. Breaking down the **Testing Pyramid** (Unit vs Integration vs E2E vs Manual testing metrics).
- Unit Testing Principles: Writing isolated, deterministic unit tests. Mastering the AAA Pattern (Arrange, Act, Assert). Understanding Code Coverage vs Test Coverage.
- Test-Driven Development (TDD): The Red-Green-Refactor cycle. Writing testable code by design, decoupling logic, and avoiding untestable anti-patterns.

## 2. Intermediate Level (Integration, Mocking, & Behavior-Driven Design)
- Mocking & Isolation Techniques: Advanced usage of Mocks, Stubs, Spies, and Fakes. Mocking network layers, database connections, and external third-party APIs without side effects.
- Integration Testing Strategies: Testing boundaries between modules. Component testing, Database integration testing (Using Docker Testcontainers for ephemeral DB testing).
- Behavior-Driven Development (BDD): Writing human-readable specifications using Gherkin syntax (`Given/When/Then`). Implementing BDD workflows using Cucumber / Playwright BDD runners.

## 3. Expert Level (Enterprise Automation, Flakiness Mitigation, & Non-Functional Testing)
- Advanced End-to-End (E2E) Engineering: Architecting robust E2E test suites using the **Page Object Model (POM)** pattern. Managing test data preparation and state teardown at scale.
- Dealing with Test Flakiness: Strategies for identifying, debugging, and mitigating flaky tests (network race conditions, dynamic wait strategies vs hardcoded sleeps). Running tests in parallel and optimizing execution time.
- Beyond Functional Testing: Core concepts and basic implementation of Performance/Load Testing (using K6 or Locust), Security/Vulnerability scanning (SAST/DAST overview), and Contract Testing (using Pact) to ensure microservices API compatibility.
- Continuous Testing (DevOps): Integrating the entire test automation pipeline into CI/CD environments. Configuring test reporters, handling multi-browser cross-platform testing grids, and establishing quality gates for production deployments.
```