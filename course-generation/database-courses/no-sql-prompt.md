📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Database Prompts Index`](./README.md) | [`📖 Course Output: NoSQL Database`](https://github.com/worapha05/database-courses/blob/main/no-sql/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Data Architect and High-Throughput Systems Engineer. Help me create a complete "Zero to Expert" self-learning bootcamp for NoSQL Databases and Caching Mechanisms, specifically focusing on MongoDB and Redis.

# Target Structure
Generate all files inside a folder named `/no-sql`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี แนวคิดการออกแบบ Schema แบบ NoSQL และกลยุทธ์การทำ Caching อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการใช้งานภาษา JavaScript/TypeScript หรือ Python ร่วมกับฐานข้อมูล และคำสั่งระดับ Production
3. `LAB.md`: โจทย์ทดสอบการออกแบบและแก้ไขระบบจากกรณีศึกษาในชีวิตจริง (เช่น ระบบ e-Commerce หรือ Real-time Dashboard) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (NoSQL Foundations & Core Operations)
- Introduction to NoSQL: Document Store (MongoDB) vs Key-Value Store (Redis) vs Relational Databases.
- MongoDB Core Operations: BSON format, Basic CRUD (`insertOne`, `find`, `updateOne`, `deleteOne`), and query selectors.
- Redis Basic Commands: String operations (`SET`, `GET`, `DEL`, `INCR`), Data Expiration (`EXPIRE`, `TTL`), and working with Hashes (`HSET`, `HGET`).

## 2. Intermediate Level (Advanced Querying & Caching Strategies)
- MongoDB Aggregation Framework: Deep dive into aggregation pipelines (`$match`, `$group`, `$project`, `$lookup`, `$unwind`) for complex data reporting.
- Advanced Redis Data Structures: Working with Lists (`LPUSH`, `RPOP`), Sets (`SADD`, `SMEMBERS`), and Sorted Sets (`ZADD`, `ZRANGE`) for ranking/leaderboard features.
- Caching Patterns: Core implementation workflows including Cache-Aside (Lazy Loading), Write-Through, and handling Cache Eviction Policies.
- Data Modeling: Designing Embedded Documents vs References in MongoDB based on application access patterns.

## 3. Expert Level (Enterprise Scale, Optimization & Resilience)
- High-Performance Caching: Mitigating architectural risks like Cache Avalanche, Cache Stampede (Thundering Herd), and Cache Penetration.
- MongoDB Indexing & Tuning: Single-field, Compound, Text, and Geospatial Indexes. Analyzing execution stats using `.explain("executionStats")`.
- Real-time Architecture: Utilizing MongoDB Change Streams and Redis Pub/Sub (Publish/Subscribe) or Redis Streams for event-driven systems.
- Distributed Operations at Scale: Understanding MongoDB Replica Sets & Sharding basics, and Redis Sentinel & Cluster architectures for High Availability (HA).
```
