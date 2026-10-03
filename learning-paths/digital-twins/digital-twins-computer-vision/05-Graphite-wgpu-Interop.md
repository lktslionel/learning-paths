# Module 05 — Graphite + wgpu Interop
**Estimated time**: 24 hours (6 weeks @ 4 h/week)

### Goal
Combine the best of both worlds: use wgpu for windowing / modern effects and Skia Graphite for high-quality 2D UI / diagrams.

### Week 32 (4 h)
**Theory (2 h)**
- How Graphite and wgpu can share textures / surfaces
- BackendTexture concepts in skia-safe
- Platform-specific interop (Metal / Vulkan / Dawn)

**Practice (2 h)**
- Study existing rust-skia Graphite + window examples
- Identify the points where a wgpu texture can be wrapped

### Week 33 (4 h)
**Theory (1.5 h)**
- Creating a shared Metal / Vulkan texture
- Synchronization considerations

**Practice (2.5 h)**
- Create a wgpu texture and attempt to wrap it as a Graphite BackendTexture (or vice-versa)
- Document what works on your platform

### Week 34 (4 h)
**Theory (1 h)**
- Alternative architectures:
  1. Skia draws everything
  2. wgpu draws background / effects, Skia draws UI on top
  3. Hybrid with multiple passes

**Practice (3 h)**
- Choose one architecture and implement a minimal hybrid renderer
- Clear with wgpu, then draw Skia content

### Week 35 (4 h)
**Practice (4 h)**
- Render the plant schematic with Skia Graphite
- Overlay a wgpu-based animated flow effect or particle system
- Keep camera / transform in sync

### Week 36 (4 h)
**Theory (1.5 h)**
- Performance comparison: pure Graphite vs hybrid
- Memory and synchronization costs

**Practice (2.5 h)**
- Profile both approaches
- Decide the architecture you will use for the final FlowTwin

### Week 37 (4 h)
**Practice heavy (4 h)**
- Clean architecture:
  - `WgpuContext`
  - `SkiaGraphiteContext`
  - Shared camera / transform
  - Single render loop that orchestrates both

### Deliverable at end of Module 05
A working hybrid renderer (wgpu + Skia Graphite) that can display the schematic with animated effects.
