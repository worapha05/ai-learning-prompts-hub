📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Backend Prompts Index`](./README.md) | [`📖 Course Output: Django`](https://github.com/worapha05/backend-courses/blob/main/django/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Senior Python Architect and Django Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Python Django and Django REST Framework (DRF).

# Target Structure
Generate all files inside a folder named `/django`. Split into 3 levels. Each level must contain:
1. `README.md`: Core architectural patterns (MVT/MVC) explained in Thai.
2. Source code files: Well-structured Django projects with clear configuration separation.
3. `LAB.md`: Practical web and API challenges in Thai with full solution code.

# Detailed Curriculum
## 1. Beginner Level (Django Monolith Core)
- MVT Architecture: Models (ORM), Views (FBVs & CBVs), and Django Template Engine.
- Database Layer: Django ORM fundamentals, Queries (`filter`, `exclude`), and Database Migrations.
- Django Admin panel customization and secure form processing (`CSRF` protection).

## 2. Intermediate Level (Django REST Framework - DRF)
- Transitioning to Headless API: Setting up **Django REST Framework (DRF)**.
- Serializers: Serializing/Deserializing data, ModelSerializers, and Custom Field Validation.
- API Views: APIView, Generic Views, and ViewSets with Routers.
- Authentication: Token Authentication, JWT (Simple JWT), and basic CORS settings for Frontend integration.

## 3. Expert Level (Enterprise Data Handling & Performance)
- ORM Optimization: Solving the N+1 problem using `select_related` and `prefetch_related`, and writing complex aggregations.
- Security & Permissions: Custom DRF Permission classes for Role-Based Access Control (RBAC).
- Scaled Operations: Background task processing using Celery/Redis, writing optimized management commands for data ingestion, and building a custom **Excel/CSV Exporter** for massive tables.
```
