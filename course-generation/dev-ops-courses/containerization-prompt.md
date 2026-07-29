📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 DevOps Prompts Index`](./README.md) | 📖 [`Course Output: Containerization`](https://github.com/worapha05/dev-ops-courses/blob/main/containerization/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Infrastructure Architect and Expert DevOps Engineer specializing in Cloud-Native Technologies. Help me create a complete "Zero to Expert" self-learning bootcamp for Containerization, specifically focusing on Docker and Kubernetes (K8s).

# Target Structure
Generate all files inside a folder named `/containerization`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี สถาปัตยกรรมเบื้องหลัง และหลักการออกแบบ Infrastructure อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียนไฟล์ Configuration (เช่น Dockerfile, docker-compose.yml และ Kubernetes Manifests ในรูปแบบ YAML)
3. `LAB.md`: โจทย์ทดสอบการสร้าง จัดการ และแก้ไขตู้คอนเทนเนอร์จากสถานการณ์จำลองในชีวิตจริง (เช่น การแพ็คแอปพลิเคชัน Full-stack, การทำ Scaling, และการแก้ปัญหา Pod ล่ม) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Docker Foundations & Local Operations)
- Containerization Concepts: What is a Container vs Virtual Machine (VM)? Understanding Images, Containers, and Registries.
- Docker CLI Core: Essential commands (`docker run`, `build`, `ps`, `stop`, `rm`, `images`, `logs`, `exec`).
- Storage & Networks: Managing persistent data using Docker Volumes and connecting containers via Docker Networks.
- Docker Compose: Writing `docker-compose.yml` to spin up multi-container applications locally (e.g., Frontend + Backend + Database) with a single command.

## 2. Intermediate Level (Production-Ready Docker & Kubernetes Essentials)
- Production Dockerfiles: Writing optimized, secure **Multi-stage Builds** to minimize image size and vulnerabilities for platforms like Google Cloud Run.
- Introduction to Kubernetes: Core architecture (Control Plane vs Worker Nodes) and understanding basic objects: Pods, ReplicaSets, and Deployments.
- Local K8s Environment: Setting up and interacting with a local cluster using Minikube or Kind and `kubectl` CLI tool.
- Service & Networking: Exposing applications internally and externally using K8s Services (`ClusterIP`, `NodePort`, `LoadBalancer`).

## 3. Expert Level (Enterprise Kubernetes Orchestration & Resilience)
- Configuration & Secrets: Managing application environments securely using K8s ConfigMaps and Secrets.
- Scalability & Health: Implementing Horizontal Pod Autoscaling (HPA) and configuring `Liveness`, `Readiness`, and `Startup` Probes to ensure zero-downtime.
- Advanced Traffic Routing: Setting up Ingress Controllers and defining Ingress Rules for path-based routing and SSL/TLS termination.
- Storage at Scale: Working with PersistentVolumes (PV), PersistentVolumeClaims (PVC), and StorageClasses for stateful applications.
- Production Security: Container hardening, non-root user execution, and understanding network policies inside Kubernetes clusters.
```
