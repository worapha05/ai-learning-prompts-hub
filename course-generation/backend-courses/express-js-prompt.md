📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Backend Prompts Index`](./README.md) | 📖 [`Course Output: Express.js`](https://github.com/worapha05/backend-courses/blob/main/express-js/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Backend Engineer and Node.js Core Architecture Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Node.js and Express.js, focusing on clean architecture, security, and enterprise-grade API development.

# Target Structure
Generate all files inside a folder named `/express-js`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกการทำงานของ Node.js และสถาปัตยกรรมของ Express อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน API, การจัดการ Middleware และการทำ Layered Architecture (JavaScript/TypeScript ยุคใหม่)
3. `LAB.md`: โจทย์ทดสอบการพัฒนาฟีเจอร์และการแก้ปัญหาระบบหลังบ้านจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Node.js Core & Express Fundamentals)
- Node.js Runtime: Understanding the V8 engine, NPM/PNPM package management, and CommonJS vs ES Modules (`import`/`export`).
- Express.js Basics: Setting up an Express app, Routing methods, Handling Request/Response objects, and parsing JSON payload/URL-encoded data.
- The Middleware Pattern: How Express Middleware works, creating Custom Logger Middlewares, and using built-in error handling mechanism.

## 2. Intermediate Level (Data Persistence, Validation, & Authentication)
- Layered Architecture: Structuring Express applications using the Controller-Service-Repository pattern (Separating concerns).
- Data Access Layer: Connecting Express to databases (PostgreSQL/MySQL) via Knex.js or Prisma ORM, and implementing Database Migrations.
- Request Sanitization & Validation: Integrating **Joi** or **Zod** schema validation to protect endpoints from malicious inputs.
- Authentication & Sessions: Implementing JWT (JSON Web Tokens) authentication, managing token lifecycles, and setting up secure CORS/Helmet HTTP headers.

## 3. Expert Level (Performance Optimization, Security Hardening, & Scale)
- Asynchronous Excellence: Advanced error handling inside async/await blocks, creating custom Global Error Handling Middlewares, and preventing uncaught exceptions/unhandled promise rejections.
- Real-time and Files: Streamlining file processing using Node.js Streams (`stream.pipe`) for memory efficiency, and handling multi-part file uploads securely.
- Production Security & Tuning: Implementing Rate Limiting (`express-rate-limit`), preventing NoSQL/SQL injection and XSS attacks at the middleware layer.
- Scalability & Clustering: Leveraging the Node.js **Cluster Module** or **PM2** to utilize multi-core CPUs, implementing connection pooling optimization, and writing health check endpoints for Docker/Kubernetes probes.
```
