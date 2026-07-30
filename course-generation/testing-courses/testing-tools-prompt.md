📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Testing Prompts Index`](./README.md) | [`📖 Course Output: Testing Tools & Ecosystem`](https://github.com/worapha05/testing-courses/blob/main/testing-tools/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Frontend Engineer and QA Automation Architect. Help me create a complete "Zero to Expert" self-learning bootcamp for Modern Tooling and Testing Ecosystems, specifically focusing on Webpack, Vite, Jest, React Testing Library, and Cypress.

# Target Structure
Generate all files inside a folder named `/testing-tool`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกการ Bundling และกลยุทธ์การออกแบบ Test Suite อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการคอนฟิกไฟล์ (webpack.config.js, vite.config.ts) และไฟล์สคริปต์การเขียนเทส (.test.tsx, .cy.ts)
3. `LAB.md`: โจทย์ทดสอบการตั้งค่าเครื่องมือ การเขียนระบบทดสอบอัตโนมัติ และการแก้ปัญหาระบบพังจากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Build Tools Foundations & Unit Testing Basics)
- Evolution of Tooling: What is a Module Bundler? Comparing Webpack (Dependency Graph) vs Vite (Native ESM dev server).
- Vite & Webpack Basics: Setting up a project from scratch, handling assets, CSS preprocessors, and configuring environment variables.
- Introduction to Unit Testing: Basic testing concepts using **Jest**, writing assertions (`expect`), mocking functions (`jest.fn`), and testing asynchronous utilities.

## 2. Intermediate Level (Component Testing & Integration Workflows)
- UI Component Testing: Testing UI components using **React Testing Library** (or Vue Test Utilities/Vitest depending on context, focusing on user-centric testing patterns).
- Querying & Interaction: Understanding RTL Queries (`getBy`, `findBy`, `queryBy`), firing events (`fireEvent` vs `userEvent`), and testing conditional rendering/loading states.
- Integration Testing: Mocking API requests inside tests using MSW (Mock Service Worker) or Jest fetch mocks to test data-fetching components.

## 3. Expert Level (End-to-End Automation & CI/CD Testing Pipeline)
- E2E Testing with **Cypress**: Installing Cypress, writing full user journey tests (e.g., UI interactions, Form submission, and Route Guard redirection checks).
- Advanced Cypress Patterns: Handling Network Requests stubbing (`cy.intercept`), custom command creation, and multi-user simulation.
- Production Optimization & Quality Metrics: Code Coverage configuration (Istanbul), optimization of Webpack/Vite bundles (Code Splitting, Tree Shaking), and integrating testing steps (Lint, Unit, Integration, E2E headless mode) into GitHub Actions or Jenkins pipelines.
```
