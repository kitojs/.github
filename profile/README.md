> [!IMPORTANT]
> Kito is still in development and is not available at this time. When this notice is removed, you will know that the framework will be available.

<div align="center">
  
---
  
<img src="./logo.png" height="200px" />

### A web framework written in Rust for TypeScript.

---
  
</div>

**Kito** is the **web framework** written in *Rust* and exposed in an **end-to-end type-safe** *TypeScript* API. Inspired by tRPC, Elysia, and ExpressJS, **Kito** aims to unify the ease and convenience of *TypeScript* with the **performance and speed** of *Rust*.

Underneath it uses [Actix](https://github.com/actix/actix-web), one of today's fastest web frameworks. Enjoy **serving millions of requests concurrently** without breaking away from **familiar syntax**. You don't need to touch *Rust* or overcomplicate things to create **truly efficient services**. Here's a basic, typical example of a **Kito** application:

```ts
import { kito } from "kito"

const app = kito()

app.get("/", (req, res) => {
  res.send("Hello world!")
})

app.listen(3000)
```

Nothing else! It's that easy. **Kito** is initially available in *Deno* and *Bun*, due to technical implications, although support for *NodeJS* is being worked on.

---

## 📚 Documentation

All **Kito** documentation can be found on the [official website](https://kito.pages.dev). One of our biggest efforts is to always provide **detailed** and **up-to-date material**, so it's rare to see something undocumented.

---

## ⚡ Performance

**Kito**'s performance is **clearly exceptional**. After all, what is being measured is not a *TypeScript* framework, but a *Rust* one. It is arguably the **fastest in the ecosystem** without a doubt, as the [benchmarks](https://github.com/kitojs/kito/tree/main/bench) show.
