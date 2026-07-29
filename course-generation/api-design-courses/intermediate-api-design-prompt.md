📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 API Design Prompts Index`](./README.md) | [`📖 Course Output: Intermediate API Design`](https://github.com/worapha05/api-design-courses/blob/main/intermediate-api-design/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal API Architect and Distributed Systems Engineer. Help me create a complete "Zero to Expert" self-learning bootcamp for Advanced API Designs and Communication Protocols, specifically focusing on GraphQL and gRPC.

# Target Structure
Generate all files inside a folder named `/intermediate-api-design`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี คอนเซปต์การออกแบบโปรโตคอลการสื่อสาร และการเปรียบเทียบ Trade-offs อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Schema, Protocol Buffers (.proto) และการสร้าง Server/Client (เช่น การใช้ TypeScript/JavaScript, Go หรือ Python)
3. `LAB.md`: โจทย์ทดสอบการสร้างระบบสื่อสารประสิทธิภาพสูงและการแก้ปัญหาจากสถานการณ์จำลองในชีวิตจริง (เช่น การทำ Data Aggregation หรือการอัปเดตข้อมูลแบบ Real-time) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (API Paradigms & Schema Definitions)
- Beyond REST: Introduction to GraphQL and gRPC. Core concepts, architectural shifting, and execution models.
- GraphQL Foundations: Understanding Schema Definition Language (SDL), Queries, Mutations, and Object Types.
- gRPC Foundations: Introduction to Protocol Buffers (proto3 syntax), defining Messages, Services, and Unary RPC operations.

## 2. Intermediate Level (Advanced Resolvers & Streaming Protocols)
- GraphQL Advanced: Implementing Resolvers, Input Types, Custom Scalars, and solving the N+1 Queries problem using DataLoaders.
- gRPC Streaming Patterns: Deep dive into Server Streaming, Client Streaming, and Bidirectional Streaming RPCs.
- Full-stack Integration: Configuring GraphQL Subscriptions (WebSockets) for real-time updates and setting up gRPC-Web to allow frontend apps to communicate with gRPC backends.

## 3. Expert Level (Enterprise Security, Performance, & Gateway Orchestration)
- Federation & Subgraphs: Designing Distributed GraphQL Architecture using Apollo Federation / Subgraphs to merge multiple microservice schemas.
- Performance Tuning & Security: Implementing Query Depth Limiting and Query Cost Analysis in GraphQL to prevent DoS attacks. Optimizing gRPC payloads, connection reuse, and multiplexing over HTTP/2.
- Production Gateway Operations: Implementing API Gateways that act as a proxy between external REST/GraphQL requests and internal gRPC microservices (gRPC Gateway pattern), handling distributed tracing (OpenTelemetry), and implementing secure Mutual TLS (mTLS) for gRPC communication.
```
