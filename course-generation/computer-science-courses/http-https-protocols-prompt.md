📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Computer Science Prompts Index`](./README.md) | [`📖 Course Output: HTTP & HTTPS Protocols`](https://github.com/worapha05/computer-science-courses/blob/main/http-https-protocols/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Network Architect, Web Performance Engineer, and Cyber Security Expert specializing in Application Layer Protocols. Help me create a complete "Zero to Expert" self-learning bootcamp for HTTP and HTTPS protocols, focusing on underlying networking mechanics, secure handshakes, protocol evolution, and performance tuning.

# Target Structure
Generate all files inside a folder named `/http-https-protocols`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกการทำงานของระบบเครือข่าย โครงสร้าง Packet/Header และความปลอดภัยอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการสร้าง Low-level HTTP Server/Client (เช่น การใช้ Node.js native, Go, หรือ Python), การวิเคราะห์ Raw HTTP Text, และตัวอย่างคอนฟิก TLS/SSL บน Web Servers (เช่น NGINX)
3. `LAB.md`: โจทย์ทดสอบการตรวจจับ/วิเคราะห์ HTTP Header, การแก้ปัญหา SSL/TLS Certificate Error และการทำ Performance Optimization จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และสคริปต์อย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (HTTP Paradigm & Raw Text Protocol Mechanics)
- The Client-Server Model: How the Web works. Understanding TCP/IP stack mapping for the Application Layer.
- Anatomy of Request & Response: Dissecting Start Lines, Standard Headers (Host, Content-Type, User-Agent, Cache-Control), Body formats, and HTTP Status Codes taxonomy.
- Statelessness & State Retention: How HTTP manages state via Cookies, Session Identifiers, and Local/Session Storage mechanics.
- HTTP Methods & Idempotency: Deep dive into safe vs unsafe methods, and the practical implications of Idempotency (GET/PUT vs POST).

## 2. Intermediate Level (HTTPS Cryptography & The Secure Handshake)
- Symmetric vs Asymmetric Encryption: Foundations of Public Key Cryptography, RSA, and Diffie-Hellman applied to the web.
- The TLS/SSL Handshake: Step-by-step breakdown of TLS 1.2 vs TLS 1.3 handshakes (ClientHello, ServerHello, Key Exchange, Session Keys generation, 0-RTT).
- Digital Certificates & PKI: Public Key Infrastructure, Certificate Authorities (CAs), Root Certificates, Certificate Chains, and managing Let's Encrypt certificates.
- Security Headers: Implementing and configuring secure response headers: HSTS (HTTP Strict Transport Security), CSP (Content Security Policy), X-Frame-Options, and SameSite cookie attributes.

## 3. Expert Level (Protocol Evolution & High-Performance Web Engineering)
- Protocol Generations (HTTP/1.1 vs HTTP/2 vs HTTP/3):
  - HTTP/1.1 Bottlenecks: Head-of-Line (HOL) Blocking, Keep-Alive connections, and domain sharding.
  - HTTP/2 Optimization: Binary Framing Layer, Multiplexing over a single TCP connection, Header Compression (HPACK), and Server Push.
  - HTTP/3 & QUIC: Transition from TCP to UDP, connection migration, solving transport-layer HOL blocking, and congestion control enhancements.
- Network Profiling & Debugging: Analyzing raw network traffic and application streams using tools like Wireshark, cURL, and Browser DevTools (Network tab).
- Production Infrastructure & Performance Tuning: Configuring NGINX/Reverse Proxies for optimal HTTPS (TLS Session Resumption, ALPN negotiation, OCSP Stapling, HTTP/2 & HTTP/3 multiplexing enabled). Mitigating common application-layer attacks (Slowloris, HTTP Flood DDoS, MiTM interception mitigation).
```
