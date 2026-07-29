📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Mobile App Prompts Index`](./README.md) | [`📖 Course Output: Flutter`](https://github.com/worapha05/mobile-app-courses/blob/main/flutter/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Mobile Solutions Architect and Expert Flutter Developer specializing in Enterprise Mobile Systems. Help me create a complete "Zero to Expert" self-learning bootcamp for Flutter and Dart tailored for high-performance iOS and Android app development.

# Target Structure
Generate all files inside a folder named `/flutter`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี Flutter Engine Lifecycle, Dart Concurrency, และกลยุทธ์การออกแบบ State Management อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างส่วนประกอบ UI Widget, โครงสร้าง Clean Architecture, และสคริปต์จัดการ Data Flow (Dart ยุคใหม่ที่มี Strict Null Safety)
3. `LAB.md`: โจทย์ทดสอบการจัด Layout การปั้น UI Component และการทำ API Data Interception/Caching จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Dart Core & Flutter UI Basics)
- Modern Dart Foundations: Strict Null Safety, Object-Oriented Programming (OOP) in Dart, Mixins, Extends vs Implements, and Async-Await futures.
- Flutter Widget Architecture: Everything is a Widget. Understanding Declarative UI, Stateless vs Stateful Widgets, Widget Lifecycle, and BuildContext mechanics.
- Layouts & Compositing: Designing pixel-perfect, responsive mobile layouts using Row, Column, Stack, Flex, GridView, and custom Themes.

## 2. Intermediate Level (State Management, Navigation, & Core Services)
- Enterprise State Management: Implementing robust state control using **BLoC / Cubit** or **Riverpod** (Separating UI logic from Business Logic).
- Declarative Navigation: Configuring structured app routing using **GoRouter** (Handling Nested Navigation, Shell Routes, and Route Guards for Auth redirect).
- Networking & Local Storage: Making secure API requests with **Dio**, Custom Interceptors setup, Type-safe Model generation using `json_serializable`/`freezed`, and local persistence via **Isar** or **Hive** databases.

## 3. Expert Level (Enterprise Scale, Performance, & DevOps Automation)
- Rendering Engine & Performance Tuning: Profiling app performance using Flutter DevTools, debugging unnecessary rebuilds (`const` constructors optimization), image caching strategies, and utilizing Dart **Isolates** for multi-threaded heavy background processing (e.g., Data Parsing / File Upload pipelines).
- Architecture & Hardware Integration: Implementing the application using **Clean Architecture** patterns (Data, Domain, Presentation Layers). Integrating Native Platform Channels to communicate with system APIs (Biometrics, Push Notifications, Platform-specific Code via MethodChannels).
- Security & DevOps Pipeline: Implementing SSL Pinning, Secure Storage, Code Obfuscation, and configuring multi-environment build setups (Development, Staging, Production) using Flutter Flavors. Automating deployment pipelines for iOS and Android store binaries using Fastlane integrated with GitHub Actions/Jenkins.
```
