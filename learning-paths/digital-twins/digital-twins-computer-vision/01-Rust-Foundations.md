# Module 01 — Rust Foundations & Tooling
**Estimated time**: 24 hours (6 weeks @ 4 h/week)

### Goal
Become comfortable writing clean, idiomatic Rust code that will later handle GPU resources, lifetimes, and async.

### Week 1 (4 h)
**Theory (2 h)**
- Read: [The Rust Book – Chapters 1–6](https://doc.rust-lang.org/book/)
- Ownership, borrowing, slices, structs, enums

**Practice (2 h)**
- Install Rust via [rustup](https://rustup.rs)
- Complete first 15 exercises of [Rustlings](https://github.com/rust-lang/rustlings)
- Create a simple CLI that reads a JSON config (use `serde`)

### Week 2 (4 h)
**Theory (1.5 h)**
- Rust Book Chapters 7–10 (packages, modules, collections, error handling)
- Error handling with `Result` and `thiserror` / `anyhow`

**Practice (2.5 h)**
- Continue Rustlings (next 20 exercises)
- Build a small “Sensor Simulator” that generates random flow/level values every second and prints them

### Week 3 (4 h)
**Theory (2 h)**
- Rust Book Chapters 11–13 (testing, closures, iterators)
- Traits and generics

**Practice (2 h)**
- Add unit tests to the Sensor Simulator
- Implement a trait `TelemetrySource` with a mock implementation

### Week 4 (4 h)
**Theory (1.5 h)**
- Rust Book Chapters 15–16 (smart pointers, concurrency basics)
- `Arc`, `Mutex`, channels

**Practice (2.5 h)**
- Make the Sensor Simulator multi-threaded (producer thread + consumer)
- Use channels to send telemetry

### Week 5 (4 h)
**Theory (2 h)**
- Async Rust introduction: [Async Book](https://rust-lang.github.io/async-book/) (first half)
- `tokio` basics

**Practice (2 h)**
- Convert Sensor Simulator to async with `tokio`
- Add a simple HTTP endpoint with `axum` that exposes current values (optional but useful)

### Week 6 (4 h)
**Theory (1 h)**
- Cargo workspaces, features, and good project structure
- Review of lifetimes and when you actually need them

**Practice (3 h)**
- Reorganize the Sensor Simulator into a proper workspace
- Write a short design note: “How I will structure the digital twin later”
- Push everything to a private GitHub repo

### Deliverable at end of Module 01
A clean, async, multi-threaded telemetry simulator + solid Rust muscle memory.
