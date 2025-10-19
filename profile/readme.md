<div align="center">
  <img src="https://github.com/kitojs/.github/blob/77b74df56562b7d75cf04bb7237dcd71527e6293/assets/kito-banner.png" width="220px" />
  
  <br />
  <br />
  
  <p>
    <strong>High-performance</strong>, fully <strong>type-safe</strong>, and modern web framework for <strong>TypeScript</strong>.  
    Powered by <strong>Rust</strong> for extremely speed and low memory usage.
  </p>
</div>

---

**Kito** is a TypeScript web framework designed for **performance and reliability**. It gives you an API familiar to Express.js users, but under the hood most of the heavy lifting runs in **Rust**, making it extremely fast and memory-efficient.

You write your code in TypeScript like normal, while Kito handles:

* Routing and middleware execution
* Request validation and type safety
* Efficient response building and socket handling

All the runtime-critical logic is executed in Rust, leaving TypeScript as a **developer-friendly layer**. You get **type safety, familiar syntax, and Node.js/Deno/Bun compatibility**, without sacrificing performance.

```ts
import { server } from "kitojs";

const app = server();

app.get("/", (ctx) => {
  ctx.res.send("hello world!");
});

app.listen(3000);
```

---

## Why Kito? 🐺

* **Minimal overhead:** most of the logic runs in Rust
* **Type-safe:** request and response types are fully inferred
* **Familiar API:** Express-style routing and middleware
* **Cross-platform:** works on Node.js, Deno, and Bun
* **Fast and memory-efficient:** ideal for high-throughput backends
* **Extensible:** you can greatly extend the ecosystem, from TypeScript or Rust

---
