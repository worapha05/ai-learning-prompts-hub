📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Mobile App Prompts Index`](./README.md) | [`📖 Course Output: React Native`](https://github.com/worapha05/mobile-app-courses/blob/main/react-native/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Mobile Solutions Architect and Senior React Native Engineer. Help me create a complete "Zero to Expert" self-learning bootcamp for React Native and Expo Ecosystem tailored for high-performance iOS and Android app development.

# Target Structure
Generate all files inside a folder named `/react-native`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี Mobile Architecture, Bridge vs JSI Engine, และการจัดการ Mobile State อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างส่วนประกอบ UI, การคอนฟิก Expo Router, และสคริปต์เชื่อมต่อ Native Modules (TypeScript/TSX ยุคใหม่)
3. `LAB.md`: โจทย์ทดสอบการสร้างหน้าจอ การจัดการ Layout (Flexbox บน Mobile) และการทำ Data Fetching/Local Cache จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Mobile Fundamentals & Expo Core)
- React Native Architecture: Understanding the JavaScript Engine (Hermes), New Architecture (Fabric, TurboModules), and how Cross-Platform rendering works.
- Expo Ecosystem: Setting up a workflow with Expo Go vs Development Builds. Core Components (`View`, `Text`, `Image`, `ScrollView`, `FlatList`).
- Layouts & Styling: Implementing Mobile Responsive Layouts using React Native Flexbox, absolute/relative positioning, and Platform-specific styling.

## 2. Intermediate Level (Navigation, State & Native Features)
- Advanced Navigation: Mastering file-based routing with **Expo Router** (Tabs, Stacks, Drawers, and Dynamic Route parameters).
- Mobile State & Storage: Managing server state via React Query and persistent local storage using **Expo SecureStore** or Async Storage.
- Interacting with Hardware: Integrating Native APIs smoothly: Device Camera, Push Notifications setup, Location Services, and handling Permissions gracefully.

## 3. Expert Level (Enterprise Scale, Performance, & Offline-First)
- Performance Tuning at Scale: Optimizing List rendering (`FlashList` vs `FlatList`), memory leak mitigation, avoiding heavy bridge passes, and optimizing Image caching/loading profiles.
- Architecture & Resilience: Designing an **Offline-First Application** with local databases (SQLite or Realm) and automatic server synchronization pipelines. Custom Native Modules development via Expo Config Plugins.
- Production Security & DevOps: Code Obfuscation, implementing biometric authentication (FaceID/TouchID), configuring Multi-environment setups (Staging/Production), OTA (Over-The-Air) updates using Expo Updates, and preparing app binaries for App Store and Google Play deployment via EAS (Expo Application Services).
```
