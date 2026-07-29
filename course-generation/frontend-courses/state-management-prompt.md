📍 **Nav:** [`🏠 AI Learning Prompts Hub`](../../README.md) | [`📂 Frontend Prompts Index`](./README.md) | [`📖 Course Output: State Management`](https://github.com/worapha05/frontend-courses/blob/main/state-management/README.md)

---

# 📝 Prompt ตั้งต้น (Initial Generation)

```text
# Role & Context
You are a Principal Frontend Architect and State Management Expert. Help me create a complete "Zero to Expert" self-learning bootcamp for Advanced State Management and Server State Caching, specifically focusing on Redux (Redux Toolkit), NgRx, React Query (TanStack Query), and Apollo Client.

# Target Structure
Generate all files inside a folder named `/state-management`. Split into 3 levels. Each level must contain:
1. `README.md`: คำอธิบายทฤษฎี ความแตกต่างระหว่าง Client State กับ Server State และการออกแบบ Data Flow อย่างละเอียดเป็นภาษาไทย พร้อม Best Practices
2. Source code files: โค้ดตัวอย่างการคอนฟิก Store, Actions, Reducers, Selectors, และการตั้งค่า Query/Apollo Client (TypeScript ยุคใหม่)
3. `LAB.md`: โจทย์ทดสอบการออกแบบระบบจัดการข้อมูลและการแก้ปัญหาจากสถานการณ์จำลองในชีวิตจริง (เช่น ระบบกรองข้อมูลขั้นสูงแบบ Real-time หรือการทำ Offline-first Cache) เป็นภาษาไทย พร้อมเฉลยโค้ดครบถ้วน

# Detailed Curriculum
## 1. Beginner Level (State Paradigms & Basic Stores)
- State Management Shifting: Client State vs Server State. Local State vs Global State. When to use what?
- Redux Toolkit (RTK) Foundations: Understanding Store, Slices, Actions, Reducers, and Hooks (`useSelector`, `useDispatch`).
- React Query & Apollo Basics: Setting up QueryClient and ApolloProvider. Writing basic `useQuery` for REST APIs and GraphQL operations.

## 2. Intermediate Level (Reactive Store & Server State Architecture)
- NgRx for Enterprise Angular: Deep dive into Actions, Reducers, Selectors, and Handling Side Effects using RxJS Operators (`createEffect`, `switchMap`, `catchError`).
- React Query Advanced: Managing Cache Time (`gcTime`) vs Stale Time, Pagination, Infinite Queries (`useInfiniteQuery`), and Automated Cache Invalidation via Mutation (`useMutation`).
- Apollo Client Caching: Understanding Normalized Cache (`InMemoryCache`), Reading/Writing directly to the cache, and managing Client-only fields using Local State (`@client`).

## 3. Expert Level (High-Performance Sync, Optimistic UI, & Large Data Grids)
- Optimistic Updates: Implementing Optimistic UI in React Query and Apollo Client to update the interface instantly before server confirmation, with automatic rollback on failure.
- Enterprise Integration & Performance: Combining Redux/NgRx with Server State (React Query) effectively without data duplication. Performance tuning for large-scale dashboards with massive dynamic data grids using Selective Selectors and Memoization.
- Advanced Cache Synchronization: Handling Real-time Sync (WebSockets/GraphQL Subscriptions) directly updating Redux/NgRx stores or Server Caches, Offline-first capabilities, and Cache Prefetching strategies for zero-latency user experiences.
```
