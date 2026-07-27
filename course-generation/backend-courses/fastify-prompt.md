# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Backend Architect and Fastify Core Contributor specializing in Ultra-High-Performance Node.js Applications. Help me create a complete "Zero to Expert" self-learning bootcamp for Fastify, focusing on its plugin architecture, low-overhead mechanics, schema validation, and enterprise routing patterns.

# Target Structure
Generate all files inside a folder named `/fastify`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกภายในของ Fastify (Low Overhead, Encapsulation) และการออกแบบ Data Flow อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการคอนฟิก Fastify Server, การเขียน Plugins, และการกำหนด JSON Schema Validation (TypeScript ยุคใหม่)
3. `LAB.md`: โจทย์ทดสอบการออกแบบ API ความเร็วสูง, การจัดการโครงสร้าง Plugin ที่ซับซ้อน และการแก้ปัญหาคอขวดประสิทธิภาพระบบจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Low-Overhead Paradigms & Fastify Core)
- Express vs Fastify: Understanding why Fastify is faster (Avoidance of overhead, radical serialization performance via `fast-json-stringify`).
- Core Routing & Lifecycle: Setting up a Fastify instance, declaring routes, handling Request & Reply objects, and using shorthand methods.
- The Plugin System: Understanding Fastify's core ecosystem rule: "Everything is a Plugin". The concept of **Encapsulation** vs Root level registration, and utilizing `fastify-plugin` (`fp`).

## 2. Intermediate Level (Schema-Driven Development & Hooks Mechanics)
- Schema Validation & Serialization: Writing declarative **JSON Schemas** (using Ajv) for input validation (`body`, `querystring`, `params`, `headers`) and optimizing output serialization via `response` status schemas.
- Lifecycle Hooks: Deep dive into the Fastify request lifecycle hooks (`onRequest`, `preParsing`, `preValidation`, `preHandler`, `onResponse`). Implementing global/route-specific middlewares using hooks.
- Data Integration & Logging: Connecting Fastify to databases (PostgreSQL/MongoDB) cleanly via plugins, managing graceful shutdown using `close` hooks, and configuring ultra-fast structured logging via **Pino**.

## 3. Expert Level (Enterprise Scaling, High-Performance Tuning, & Production Hardening)
- Advanced Plugin Architecture: Designing complex enterprise applications using Hexagonal or Clean Architecture patterns via Fastify's nested plugin encapsulation boundaries.
- Ultra-High Performance Tuning: Tuning Ajv validators, managing memory leak mitigation under high concurrent load, preventing blocking asynchronous operations, and optimizing HTTP/2 setups inside Fastify.
- Production Security & Operations: Implementing secure cookie/session handling, global Rate Limiting, CORS configuration, customized centralized error handling (`setErrorHandler`), and automating zero-downtime microservices registration.
```