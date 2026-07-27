# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Cloud Architect, Senior DevOps Engineer, and Cloud-Native Infrastructure Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Cloud Computing Platforms, specifically focusing on Amazon Web Services (AWS) and Google Cloud Platform (GCP) architecture, core services integration, and Infrastructure as Code (IaC).

# Target Structure
Generate all files inside a folder named `/cloud-computing`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี โมเดลการให้บริการคลาวด์ (IaaS, PaaS, FaaS) และเปรียบเทียบสถาปัตยกรรม AWS vs GCP อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียนคอนฟิก Infrastructure as Code (Terraform สคริปต์), การเขียนสคริปต์ CLI (gcloud / aws CLI) และการตั้งค่า Environment ที่ปลอดภัย
3. `LAB.md`: โจทย์ทดสอบการออกแบบโครงสร้างคลาวด์ที่รองรับการสเกล, การแก้ปัญหาระบบ Infrastructure พังหรือเชื่อมต่อไม่ได้, และการจัดการ Secrets จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยวิธีคิด โครงสร้างไฟล์ และสคริปต์อย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Cloud Paradigms & Compute/Storage Core)
- Cloud Fundamentals: Shared Responsibility Model, Regional Architecture (Regions, Availability Zones), and IaaS vs PaaS vs FaaS definitions.
- Compute & Virtualization: Implementing and managing Virtual Machines on AWS (EC2) and GCP (Compute Engine). Understanding Auto Scaling Groups and Load Balancers.
- Cloud Storage Topologies: Deep dive into Object Storage (AWS S3 vs GCP Cloud Storage), Lifecycle policies, bucket permissions, and static web hosting blocks.
- Cloud IAM Basics: Creating users, groups, and service accounts/roles. Enforcing the Principle of Least Privilege (PoLP).

## 2. Intermediate Level (Container Runtimes, Managed Databases, & Secrets Management)
- Modern Container Orchestration: Deploying scalable APIs using serverless container models (AWS ECS/Fargate vs GCP Cloud Run).
- Managed Databases: Configuring high-availability transactional and relational database layers (AWS RDS vs GCP Cloud SQL) with automatic replicas.
- Security & Environment Secrets: Managing runtime environment variables, tokens, and credentials securely using centralized managers (AWS Secrets Manager vs GCP Secret Manager) without hardcoding config files.
- Virtual Networking: Structuring custom Virtual Private Clouds (VPC), Subnets (Public vs Private), Routing Tables, Network ACLs, and Cloud Firewalls.

## 3. Expert Level (Infrastructure as Code, High Availability, & Multi-Cloud Engineering)
- Infrastructure as Code (IaC): Automating multi-cloud deployment entirely via **Terraform**. Designing reusable modules, managing remote backend states securely, and handling infrastructure drifts.
- Resilience & Multi-Region Design: Designing Disaster Recovery (DR) strategies (Active-Active, Active-Passive), cross-region data replication, and global traffic orchestration using Global Load Balancers / Route 53.
- Observability & Cost Management: Centralized log collection and trace analytics (AWS CloudWatch/X-Ray vs GCP Cloud Logging/Cloud Trace). Optimization strategies for cloud spending (FinOps, Right-sizing instances, Spot/Preemptible VMs usage).
```