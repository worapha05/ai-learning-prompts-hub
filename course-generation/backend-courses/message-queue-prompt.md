# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Distributed Systems Architect and Expert Integration Engineer specializing in Event-Driven Architecture. Help me create a complete "Zero to Expert" self-learning bootcamp for Messaging Queues and Event Streaming, specifically focusing on Apache Kafka and RabbitMQ.

# Target Structure
Generate all files inside a folder named `/message-queue`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี คอนเซปต์การออกแบบ Distributed Messaging และสถาปัตยกรรมระบบอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Producer/Consumer และ Publisher/Subscriber (เช่น การใช้ JavaScript/TypeScript, Python หรือ Go ร่วมกับคิว)
3. `LAB.md`: โจทย์ทดสอบการสร้างระบบรับส่งข้อความและการแก้ปัญหาจากสถานการณ์จำลองในชีวิตจริง (เช่น ระบบประมวลผลออเดอร์, ระบบแจ้งเตือน Real-time หรือการแก้ปัญหาระบบคิวค้าง) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Messaging Foundations & Core Topologies)
- Core Messaging Concepts: Message Queues vs Event Streaming. What is a Producer, Consumer, Broker, and Message Payload?
- RabbitMQ Core: Understanding Exchanges (Direct, Fanout, Topic, Headers), Queues, Bindings, and basic Message Acknowledgement (ACK/NACK).
- Kafka Basics: Understanding Topics, Partitions, Brokers, Producers, Consumers, and Consumer Groups.

## 2. Intermediate Level (Advanced Integration Patterns & Reliability)
- RabbitMQ Reliability: Implementing Dead Letter Exchanges (DLX) for failed messages, Message TTL, and Work Queues (Competing Consumers pattern).
- Kafka Mechanics: Data retention policies, Offset management (Commit tracking), Message Keys, and how Consumer Rebalancing works within a Consumer Group.
- Application Integration: Building a reliable asynchronous task pipeline (e.g., Frontend pushes user actions to RabbitMQ/Kafka, Background Workers consume and process).

## 3. Expert Level (Enterprise Scale, High Availability & Resilience)
- Guaranteed Delivery & Order: Configuring Idempotent Producers, At-Least-Once vs At-Most-Once vs Exactly-Once processing semantics.
- Handling Massive Loads: High-throughput configuration, Partitioning strategies in Kafka for horizontal scaling, and RabbitMQ Quorum Queues for fault tolerance.
- Resilience Patterns: Managing Poison Pills, Implementing Exponential Backoff with Retry Queues, Circuit Breakers, and Handling Backpressure without crashing consumers.
- Production Operations: Monitoring cluster health, Lag Tracking (Burrow/Prometheus), and designing zero-downtime database updates driven by Change Data Capture (CDC) events.
```