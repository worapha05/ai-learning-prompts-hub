# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal API Architect and Senior Distributed Systems Engineer. Help me create a complete "Zero to Expert" self-learning bootcamp for API Protocols and Real-time Communication, specifically focusing on Enterprise RESTful APIs, WebSockets, and Microservices architecture patterns.

# Target Structure
Generate all files inside a folder named `/advanced-api-design`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี มาตรฐานการออกแบบ API และกลยุทธ์การทำ Real-time Connection อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการสร้าง REST Endpoints (ตามหลัก Richardson Maturity Model), การจัดการ WebSocket Server/Client, และการทำ API Gateway Configuration (TypeScript/Go/Python)
3. `LAB.md`: โจทย์ทดสอบการออกแบบ API, การแก้ปัญหาระบบ Real-time ล่ม และการเชื่อมต่อ Microservices จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (REST Standard & Basic Real-time)
- Richardson Maturity Model: Designing true RESTful APIs (Level 0 to Level 3 HATEOAS). Proper HTTP Methods (GET, POST, PUT, PATCH, DELETE) and Semantic Status Codes.
- API Design Best Practices: Structuring URIs, Handling Query Parameters for Filtering, Sorting, and Pagination.
- WebSockets Core: Understanding the HTTP Upgrade handshake, Full-Duplex communication vs Traditional Polling, and building a basic WebSocket Connection.

## 2. Intermediate Level (Stateful Connections & Microservices Foundations)
- Advanced WebSockets: Managing Connection Lifecycles, Heartbeats/Ping-Pong mechanisms to detect dead clients, Room-based broadcasting, and horizontal scaling of WebSockets using Redis Adapter (Pub/Sub).
- Microservices API Design: Designing Internal APIs vs External APIs, Implementing API Gateways (Reverse Proxy, Rate Limiting, Request Transformation), and Inter-service communication patterns.
- Payload Optimization & Security: Handling Complex JSON payloads, Versioning strategies (URL, Header, Media Type), and implementing Cross-Origin Resource Sharing (CORS) securely.

## 3. Expert Level (Enterprise Orchestration, Resilience, & Real-time at Scale)
- Microservices Data & Coordination: Handling Distributed Transactions using the Saga Pattern, Eventual Consistency, and Change Data Capture (CDC) events for loose coupling.
- High-Performance WebSockets: Mitigating performance bottlenecks, handling thousands of concurrent open socket connections (File Descriptor limits tuning), Backpressure handling, and designing reconnection fallback mechanisms (Exponential Backoff).
- Security Hardening & Zero-Downtime: Implementing OAuth2/JWT stateful token validation at the API Gateway level, Mutual TLS (mTLS) for internal microservices communication, breaking dependencies via Circuit Breakers, and designing APIs for seamless Blue-Green/Canary infrastructure updates.
```