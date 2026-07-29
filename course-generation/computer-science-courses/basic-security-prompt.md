📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Computer Science Prompts Index`](./README.md) | 📖 [`Course Output: Basic Security Concepts`](https://github.com/worapha05/computer-science-courses/blob/main/basic-security/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Security Engineer, Certified Information Systems Security Professional (CISSP), and Secure Software Architect. Help me create a complete "Zero to Expert" self-learning bootcamp for Basic Security Concepts, focusing on cybersecurity foundations, threat identification, data protection, and secure development lifecycles.

# Target Structure
Generate all files inside a folder named `/basic-security`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี แกนหลักความปลอดภัยไซเบอร์ แนวคิดการประเมินความเสี่ยง และช่องโหว่พื้นฐานอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการนำแนวคิดความปลอดภัยไปประยุกต์ใช้ (เช่น สคริปต์การทำ Data Encryption/Decryptionพื้นฐาน, การจัดตั้ง Rate Limiting หรือ Input Sanitization เบื้องต้น ด้วย TypeScript หรือ Python)
3. `LAB.md`: โจทย์ทดสอบการวิเคราะห์หาช่องโหว่ในระบบ, การทำ Threat Modeling และการออกแบบสถาปัตยกรรมความปลอดภัยจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และแนวทางแก้ไขอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (The Core Triad & Security Philosophy)
- The CIA Triad: Core pillars of security—**Confidentiality** (รักษาความลับ), **Integrity** (รักษาความถูกต้อง), and **Availability** (พร้อมใช้งานเสมอ) พร้อมกรณีศึกษาเมื่อเสาหลักต้นใดต้นหนึ่งหักลง
- DAD Triad (The Counterparts): Understanding Disclosure, Alteration, and Destruction.
- The Principle of Least Privilege (PoLP): แนวคิดการให้สิทธิ์เท่าที่จำเป็นในการทำงาน และการลด Attack Surface (พื้นที่การโจมตี) ของระบบ
- Defense in Depth: การวางแนวป้องกันหลายชั้น (Network, Host, Application, Data) เพื่อไม่ให้เกิด Single Point of Failure ฝั่งความปลอดภัย

## 2. Intermediate Level (Cryptography, Common Vulnerabilities & Web Protection)
- Symmetric vs Asymmetric Cryptography: การใช้งานและความแตกต่างของการเข้ารหัส (AES vs RSA), แนวคิดการเข้ารหัสข้อมูลขณะส่ง (Data in Transit) และขณะจัดเก็บ (Data at Rest)
- Hashing vs Encoding vs Encryption: แยกแยะความแตกต่างเพื่อการนำไปใช้งานที่ถูกต้อง (เช่น การใช้ SHA-256 สำหรับตรวจสอบความถูกต้องข้อมูล ไม่ใช่เพื่อเก็บความลับ)
- Introduction to OWASP Top 10: เจาะลึกช่องโหว่เว็บยอดนิยมเบื้องต้น เช่น Injection (SQLi/XSS), Broken Authentication, และ Sensitive Data Exposure พร้อมแนวทางการป้องกัน (Sanitization & Parametric Queries)

## 3. Expert Level (Threat Modeling, Secure SDLC, & Incident Management)
- Threat Modeling Frameworks: การวิเคราะห์และประเมินภัยคุกคามด้วยระบบ **STRIDE** (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege) จากสถาปัตยกรรมระบบแอปพลิเคชัน
- Secure Software Development Lifecycle (SSDLC): การผสานกระบวนการความปลอดภัยเข้ากับวงจรการพัฒนาซอฟต์แวร์ (เช่น การทำ SAST/DAST Code Scanning ก่อนการ Build deploy)
- Incident Response & Logging Basics: แนวคิดการตอบสนองต่อเหตุการณ์ภัยคุกคาม การออกแบบ Audit Logs ที่ปลอดภัยและไม่สามารถปลอมแปลงได้ เพื่อใช้ในกระบวนการพิสูจน์หลักฐาน (Digital Forensics)
```
