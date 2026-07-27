# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal API Architect, Integration Engineer, and Technical Fellow specializing in modern API design paradigms. Help me create a complete "Zero to Expert" self-learning bootcamp for API Design, focusing on strict RESTful standards, advanced GraphQL schema design, performance tuning, and cross-paradigm architectural decisions.

# Target Structure
Generate all files inside a folder named `/basic-api-design`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี ปรัชญาการออกแบบ API เปรียบเทียบสถาปัตยกรรม และการจัดโครงสร้างข้อมูลอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน API Specification (OpenAPI/Swagger), การกำหนด GraphQL Schema Definition Language (SDL), การเขียน Resolvers และกลไกควบคุมข้อมูล (ใช้ TypeScript หรือ Node.js)
3. `LAB.md`: โจทย์ทดสอบการปรับปรุงโครงสร้าง API ที่แย่ (API Refactoring), การออกแบบ GraphQL Type System และการแก้ปัญหาคอขวดของ API จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และโค้ดอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (API Paradigms & Resource Modeling)
- Core API Philosophies: Understanding the architectural shift between REST (Resource-centric) vs GraphQL (Graph/Query-centric).
- Strict RESTful Design: Designing clear URI paths, utilizing plural nouns, selecting precise HTTP Methods, and mapping standard status codes correctly. Implementing clean query parameters for pagination, sorting, and metadata filters.
- GraphQL Foundations: Understanding the GraphQL Type System. Writing basic Schemas using Object Types, Fields, Queries, and Mutations. The anatomy of a GraphQL request/response payload.

## 2. Intermediate Level (API Contracts, Schemas, & Lifecycle Control)
- API Specifications & Documentation: Designing contract-first APIs using **OpenAPI v3 (Swagger)**. Structuring reusable schemas, path descriptions, and handling authentication definitions.
- Advanced GraphQL Engineering: Writing complex schemas with Input Types, Enums, Interfaces, and Union types. Designing clean Mutation payloads and handling nullable vs non-nullable field strategies.
- API Lifecycle & Evolution: Managing API Versioning strategies in REST (URL vs Custom Headers vs Media Type) vs GraphQL's evolutionary model (`@deprecated` tags, additive changes without breaking clients).

## 3. Expert Level (Performance Optimization, Security Hardening, & Data Stitching)
- Solving Performance Bottlenecks:
  - REST: Implementing conditional requests (`ETag` / `If-None-Match`), proper caching layers using HTTP Cache-Control headers, and payload compression.
  - GraphQL: Mitigating the infamous **N+1 Query Problem** using **DataLoader** (Batching and Caching layer), Query Complexity Analysis, and Query Depth Limiting to prevent DoS attacks.
- Enterprise API Security: Implementing structural field-level authorization, input sanitization at the GraphQL directive layer, preventing Over-fetching/Under-fetching leakage, and enforcing global API Rate Limiting.
- Distributed Data Ecosystems: Basic architectural concepts of **GraphQL Federation (Apollo Federation)** and API Mesh—combining multiple microservices schemas into a single unified gateway layer.
```