# Digital Twin UI Learning Plan
## Rust + skia-safe + Graphite + WebGPU/wgpu

**Goal**: Build a fully functional, production-ready digital twin UI prototype  
(interactive 2D process diagram with live data, zoom/pan, status overlays, native + WASM).

**Pace**: 4 hours per week  
**Total estimated effort**: ~220 hours  
**Estimated completion**: **55 weeks** (~1 year and 1 month)  
Starting from today (October 2026) → **finish around November 2027**.

### How to use this plan
1. Follow modules in order.
2. Each module alternates **Theory** and **Practice**.
3. Do not skip practice sessions — they compound into the final product.
4. Keep a personal journal (one file or notebook) of what you built each week.
5. The final prototype is progressively constructed across modules.

### End-to-End Scenario
We will build **"FlowTwin"** — a digital twin of a simple industrial water treatment process:
- Tanks, pumps, valves, pipes, sensors
- Real-time simulated telemetry (flow, level, pressure, status)
- Interactive schematic (zoom, pan, select, hover tooltips)
- Status colors, alarms, animated flow
- Data panel + historical mini-charts
- Runs natively (desktop) and in the browser (WASM)
- Clean architecture ready for real MQTT / OPC-UA later

### Module Overview

| Module | Title                              | Hours | Weeks |
|--------|------------------------------------|-------|-------|
| 01     | Rust Foundations & Tooling         | 24    | 6     |
| 02     | WebGPU / wgpu Fundamentals         | 40    | 10    |
| 03     | Advanced wgpu & Shaders            | 28    | 7     |
| 04     | skia-safe & Graphite Basics        | 32    | 8     |
| 05     | Graphite + wgpu Interop            | 24    | 6     |
| 06     | Digital Twin Core Architecture     | 32    | 8     |
| 07     | Interactive Scene & UX             | 28    | 7     |
| 08     | Production Hardening & Deployment  | 12    | 3     |
| **Total** |                                 | **220** | **55** |

### Recommended Weekly Rhythm (4h)
- 1.5–2 h Theory / reading / watching
- 2–2.5 h Hands-on coding / experimentation

### Tools you will need
- Rust (latest stable via rustup)
- Visual Studio Code or RustRover + rust-analyzer
- Git
- A modern browser with WebGPU support (Chrome/Edge recommended)
- Optional: wgpu validation layers, Metal/Vulkan SDK depending on OS

Start with **Module 01**.

Good luck — consistency beats intensity.
