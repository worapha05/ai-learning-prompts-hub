# 📝 Prompt ตั้งต้น (Initial Generation)

---

```text
# Role & Context
You are a Principal Software Engineer, JavaScript Core Contributor, and TypeScript Type System Architect. Help me create a complete "Zero to Expert" self-learning bootcamp for JavaScript and TypeScript, focusing on engine mechanics, advanced typing, and architectural patterns across both Frontend and Backend runtimes.

# Target Structure
Generate all files inside a folder named `/javascript-typescript-deepdive`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี กลไกการทำงานของ Engine และระบบ Type อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการเขียน Advanced JS (Closures, Event Loop Tracing) และ Advanced TS (Conditional Types, Template Literal Types) ในรูปแบบ ES Modules (.ts / .js)
3. `LAB.md`: โจทย์ทดสอบการแก้ไข Memory Leak, การปั้น Type Utility ซับซ้อน และการแก้ปัญหา Type Check จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดอย่างครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Runtime Execution & Core Type Systems)
- The Execution Engine: How the V8 Engine works. Understanding Memory Management (Call Stack vs Heap), Garbage Collection (Scavenge vs Mark-Sweep), and Hoisting mechanics.
- Scope & Context: Lexical Scope, Closures, Explicit Context Binding (`call`, `apply`, `bind`), and the behavior of the `this` keyword in regular vs arrow functions.
- TypeScript Basics: Structural Typing paradigm, Explicit vs Inferred types, Interfaces vs Type Aliases, and mastering Strict Mode configurations (`tsconfig.json`).

## 2. Intermediate Level (Asynchronous Architecture & Expressive Typing)
- The Asynchronous Heart: Deep dive into the JavaScript Event Loop, Microtask Queue (Promises, `process.nextTick`) vs Macrotask Queue (`setTimeout`, I/O), and async/await compilation transformation.
- Advanced TypeScript Types: Generics at scale, Type Guards (`typeof`, `instanceof`, Custom Type Predicates), Discrimination Unions, and complex Type Assertions (`as const`, `satisfies`).
- Full-Stack Commonalities: Working with Arrays & Iterables (Advanced `reduce`, `flatMap`, Generators), Prototype Chain inheritance, and Proxy/Reflect APIs for meta-programming.

## 3. Expert Level (Metaprogramming, Type Gymnastic, & Performance Hardening)
- Type Gymnastics: Designing complex utility types using Conditional Types (`T extends U ? X : Y`), Mapped Types, Template Literal Types, Index Access Types, and the `infer` keyword.
- Advanced Architecture & Paradigms: Building Type-Safe Event Emitters, Decorators (TC39/TypeScript Legacy), and Functional Programming concepts (Currying, Monads, Pipe/Compose) applied to web infrastructure.
- Performance Tuning & Profiling: Detecting and fixing Frontend/Backend Memory Leaks (Detached DOMs, Retained Closures), optimizing V8 Hidden Classes and Inline Caches, and configuring compiler optimizations for monorepos (Project References).
```