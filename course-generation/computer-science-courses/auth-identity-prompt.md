📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Computer Science Prompts Index`](./README.md) | [`📖 Course Output: Authentication & Authorization`](https://github.com/worapha05/computer-science-courses/blob/main/auth-identity/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Security Architect, Enterprise IAM Engineer, and Cybersecurity Expert specializing in Application Security and Identity Federated Systems. Help me create a complete "Zero to Expert" self-learning bootcamp for Authentication and Authorization, focusing on architectural patterns, token-based security, protocol standards, and enterprise-grade access control.

# Target Structure
Generate all files inside a folder named `/auth-identity`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี ปรัชญาความปลอดภัย กลไกของโปรโตคอล และช่องโหว่ทางระบบความปลอดภัยอย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการออก Token, การตรวจสอบสิทธิ์ผ่าน Middleware, การคอนฟิก Identity Provider (เช่น Keycloak หรือ OAuth setup) และการจัดการ Session (ใช้ TypeScript, Node.js หรือ Go)
3. `LAB.md`: โจทย์ทดสอบการออกแบบระบบล็อกอิน, การทำ Token Revocation, การแก้ช่องโหว่ความปลอดภัย (เช่น Session Hijacking) และการทำสิทธิ์แบบละเอียดจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และสคริปต์แก้ไขอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Auth Foundations & Stateless vs Stateful Sessions)
- Authentication vs Authorization: Defining the boundary. Who are you vs What can you do?
- Session Management Paradigms:
  - Stateful Sessions: Cookies, Server-side Session Stores (Redis/SQL), Cookie attributes (`HttpOnly`, `Secure`, `SameSite`).
  - Stateless Sessions: JSON Web Tokens (JWT) anatomy (Header, Payload, Signature), Symmetric (`HS256`) signing, and token decoding.
- Basic Password Security: Hashing vs Encryption. Implementing secure hashing using **bcrypt** or **Argon2** with proper Salt metrics.

## 2. Intermediate Level (Token Lifecycles & Granular Access Control)
- Advanced JWT Architecture: Implementing short-lived Access Tokens and long-lived **Refresh Tokens**. Designing safe token rotation mechanisms and handling blacklisting/revocation via caching layers.
- Access Control Models:
  - **RBAC (Role-Based Access Control)**: Implementing Roles, Permissions, and hierarchical role checking at the application middleware layer.
  - **ABAC (Attribute-Based Access Control)**: Dynamic permission evaluation based on user, resource, and environmental context.
- Securing API Endpoints: Building generic Auth Middlewares, handling unauthorized (`401`) vs forbidden (`403`) exceptions, and preventing IDOR (Insecure Direct Object Reference) vulnerabilities.

## 3. Expert Level (Enterprise Federated Identity, OAuth 2.0/OIDC, & Security Hardening)
- Modern Identity Protocols:
  - **OAuth 2.0 Framework**: Deep dive into Grant Types (Authorization Code Flow with PKCE for single-page/mobile apps, Client Credentials for machine-to-machine integration).
  - **OpenID Connect (OIDC)**: Identity layer on top of OAuth 2.0. Understanding ID Tokens, UserInfo endpoint, and integration with Enterprise Identity Providers (e.g., Keycloak, Auth0).
- Advanced Threat Mitigation & Security Hardening:
  - Defending against Top OWASP API Security risks: Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), Token Leakage, and Replay Attacks.
  - Implementing Single Sign-On (SSO) architectures, Multi-Factor Authentication (MFA/TOTP flow), and Zero-Trust access verification patterns at the API Gateway level.
```
