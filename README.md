#### NOISER lang

Noiser is a **Rust-like** language designed for **creative coding** and procedural generation. It is built to be embedded within Rust or C++ graphics engines and includes C bindings for broad compatibility.

**Key characteristics include:**

* **Core Domain:** It specializes in **linear algebra**, **noise functions**, and **agentic simulations** to define complex terrain, materials, and assets.
* **Performance & Embedding:** It generates high-performance scripts designed to be **embedded** in other languages and run in **parallel** (via NoiserWarp).
* **Architecture:** It compiles to a custom intermediate representation (NoIR), which is **JIT-compiled** (via Cranelift) or executed by a lightweight VM.
* **Syntax:** It features a modern, Rust-like syntax (including `let`, `match`, and `enum` ) combined with shader-inspired features like vector swizzling (`.xyz`, `.x0z`) and built-in math functions.
