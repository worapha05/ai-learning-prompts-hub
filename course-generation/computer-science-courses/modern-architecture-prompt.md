📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Computer Science Prompts Index`](./README.md) | 📖 [`Course Output: Modern Software Architecture`](https://github.com/worapha05/computer-science-courses/blob/main/modern-architecture/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Cloud Solution Architect and Expert Systems Engineer specializing in Cloud-Native Distributed Systems. Help me create a complete "Zero to Expert" self-learning bootcamp for Modern Software Architecture, specifically focusing on Microservices and Serverless (AWS Lambda / GCP Cloud Functions & Cloud Run).

# Target Structure
Generate all files inside a folder named `/modern-architecture`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี แนวคิดการออกแบบสถาปัตยกรรม และการเปรียบเทียบ Trade-offs อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Serverless Functions, การทำ API Gateway Configuration และการเชื่อมต่อบริการแบบ Distributed
3. `LAB.md`: โจทย์ทดสอบการออกแบบ การย้ายระบบ (Migration) และการแก้ไขปัญหาระบบล่มจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Architecture Foundations & Serverless Core)
- Monolith vs Microservices vs Serverless: Understanding Core Patterns, Benefits, and Architectural Trade-offs.
- Serverless Essentials: Function-as-a-Service (FaaS) execution model, Stateless design, and Event-driven triggers.
- Writing Your First Function: Creating, testing, and deploying basic functions using AWS Lambda (or Python/Go on GCP Cloud Functions).
- API Gateway Integration: Mapping HTTP endpoints to serverless functions, handling CORS, and passing query strings/headers.

## 2. Intermediate Level (Microservices Patterns & Distributed Communication)
- Microservices Communication: Synchronous (REST, gRPC) vs Asynchronous (Event Streaming using Queues) communication patterns.
- Service Discovery & API Gateways: Implementing Reverse Proxies, Request Routing, and Centralized Logging at the Gateway layer.
- Distributed Data Management: Database-per-service pattern, Shared Databases vs Polyglot Persistence, and the challenges of Data Consistency.
- Cold Starts & Environments: Understanding Cold Starts in Serverless, optimizing deployment package sizes, and managing Environment Variables via Secret Manager securely.

## 3. Expert Level (Enterprise Distributed Patterns, Resilience, & Mesh)
- Distributed Transactions: Designing and implementing the Saga Pattern (Choreography vs Orchestration) and Two-Phase Commit (2PC) alternatives.
- Advanced Resilience: Implementing Circuit Breakers, Retries with Exponential Backoff, Rate Limiting, and Graceful Degradation to prevent Cascading Failures.
- Observability at Scale: Distributed Tracing (OpenTelemetry / AWS X-Ray / GCP Cloud Trace), Centralized Log Aggregation, and Metric Monitoring.
- Enterprise Serverless Operations: Infrastructure as Code (IaC) using Serverless Framework or Terraform, Multi-region deployments, and Canary/Blue-Green deployments for serverless functions.
```
