📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Frontend Prompts Index`](./README.md) | 📖 [`Course Output: Svtle & SvelteKit`](https://github.com/worapha05/frontend-courses/blob/main/svelte/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Frontend Architect and Svelte/SvelteKit Core Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Svelte and SvelteKit tailored for High-Performance Web Development.

# Target Structure
Generate all files inside a folder named `/svelte`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี แนวคิด Compiler-first Architecture, Reactivity System และ Data Flow อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างส่วนประกอบ Svelte (.svelte), สคริปต์การจัดการ State, และการวางโครงสร้าง Routing ของ SvelteKit (TypeScript ยุคใหม่)
3. `LAB.md`: โจทย์ทดสอบการจัด Layout การปั้น UI Component และการทำ Data Fetching/Form Actions จากสถานการณ์จำลองในชีวิตจริง เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (Svelte Core & True Reactivity)
- Compiler vs Virtual DOM: Understanding Svelte's architectural paradigm shift and how it achieves zero-runtime overhead.
- Svelte Reactivity: Assignments (`=`), Reactive declarations (`$:`) or the new Svelte 5 Runes syntax (`$state`, `$derived`, `$inspect`), and reactive statements.
- Templating & Components: Logic blocks (`{#if}`, `{#each}`, `{#await}`), component props, slot mechanisms (or snippets), and handling DOM events.

## 2. Intermediate Level (Advanced Svelte Features & SvelteKit Essentials)
- State Management: Svelte Stores (Writable, Readable, Derived, Custom stores) and context API (`setContext` / `getContext`).
- Component Lifecycle & Transitions: Using built-in transitions/animations (`fly`, `fade`, `tweened`) and lifecycle hooks (`onMount`, `onDestroy`, `tick`).
- SvelteKit Framework Foundations: File-based routing (Layouts, Pages, Server Routes), Data Loading via `load` functions (`+page.ts` / `+page.server.ts`), and handling Forms using SvelteKit **Form Actions** cleanly.

## 3. Expert Level (Enterprise Scale, Hydration & Server Engines)
- Performance Tuning at Scale: Handling massive dynamic data grids with Tailwind CSS in Svelte, optimizing reactivity to prevent unnecessary re-renders, and memory leak mitigation.
- Rendering Strategies: Configuring Server-Side Rendering (SSR), Static Site Generation (SSG), and Single Page Application (SPA) modes per route using SvelteKit Adapters (Vercel, Node, Static).
- Advanced Operations: Building global middlewares using SvelteKit Hooks (`handle` hook) for JWT Authentication/RBAC, managing hydration mismatch errors, caching strategies at the server level, and integrating SvelteKit with modern ORMs.
```
