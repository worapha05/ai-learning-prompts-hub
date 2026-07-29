📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 DevOps Prompts Index`](./README.md) | 📖 [`Course Output: CI/CD Pipeline`](https://github.com/worapha05/dev-ops-courses/blob/main/ci-cd-pipeline/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal DevOps Engineer and Cloud Infrastructure Architect. Help me create a complete "Zero to Expert" self-learning bootcamp for CI/CD Pipelines, specifically focusing on GitHub Actions and Jenkins.

# Target Structure
Generate all files inside a folder named `/ci-cd-pipeline`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี คอนเซปต์ Automation Pipeline และการออกแบบ Workflow อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียนไฟล์ Configuration (เช่น YAML สำหรับ GitHub Actions และ Jenkinsfile สำหรับ Jenkins)
3. `LAB.md`: โจทย์ทดสอบการสร้างและแก้ไข Pipeline จากสถานการณ์จำลองในชีวิตจริง (เช่น รัน Test อัตโนมัติ, Build Docker Image, Deploy ขึ้น Cloud) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (CI/CD Foundations & Basic Workflows)
- Core Concepts: What is Continuous Integration (CI) and Continuous Delivery/Deployment (CD)?
- GitHub Actions Basics: Understanding Syntax (Workflows, Jobs, Steps, Actions), Triggers (`on: [push, pull_request]`), and using Environment Variables.
- Jenkins Core: Installing Jenkins via Docker, setting up the Dashboard, creating Freestyle Projects, and configuring simple build triggers.

## 2. Intermediate Level (Advanced Automation & Pipeline as Code)
- Jenkinsfile & Declarative Pipelines: Deep dive into Declarative syntax, Stages, Steps, Post-actions, and Agents.
- Security & Credentials: Securely managing API Keys, Tokens, and SSH Keys using GitHub Secrets and Jenkins Credentials Provider.
- Automated Testing & Artifacts: Integrating automated testing steps (Unit Tests, Linting) and archiving build artifacts (e.g., zip, jar files).
- Matrix Builds: Running tests concurrently across multiple software versions or operating systems using GitHub Actions Matrix.

## 3. Expert Level (Enterprise Delivery, Security & Cloud Deployment)
- Production-Ready Deployment: Building Multi-stage pipelines that build Docker images, push to container registries (Docker Hub/Artifact Registry), and deploy automatically to Google Cloud Run or AWS.
- Deployment Strategies: Designing advanced workflows for Blue-Green Deployments, Canary Releases, and implementing Manual Approval gates.
- Pipeline Optimization & Security: Caching dependencies (npm, pip, go) to speed up build times, optimizing runner usage, and performing Static Application Security Testing (SAST) using SonarQube or Trivy inside the pipeline.
```
