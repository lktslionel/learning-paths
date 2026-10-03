# Module 03 — Advanced wgpu & Shaders
**Estimated time**: 28 hours (7 weeks @ 4 h/week)

### Goal
Gain enough shader and pipeline mastery to later create custom effects (flow animation, heatmaps, status pulses) that integrate with Skia Graphite.

### Week 17 (4 h)
**Theory (2 h)**
- Deeper WGSL: functions, control flow, textures sampling
- Read: [Tour of WGSL](https://google.github.io/tour-of-wgsl/) or WebGPU Fundamentals shader sections

**Practice (2 h)**
- Write a fragment shader that creates a simple animated gradient or noise

### Week 18 (4 h)
**Theory (1.5 h)**
- Multi-pass rendering
- Render targets / offscreen textures

**Practice (2.5 h)**
- Render the scene to an offscreen texture, then post-process it (blur or color grade)

### Week 19 (4 h)
**Theory (1.5 h)**
- Compute shaders for data processing
- Prefix sum / simple particle systems

**Practice (2.5 h)**
- Use a compute shader to update a large number of “sensor particles”
- Visualize them

### Week 20 (4 h)
**Theory (1 h)**
- Bind group layouts and pipeline layouts best practices
- Dynamic offsets

**Practice (3 h)**
- Refactor previous code to use cleaner bind group management
- Support multiple materials / pipelines

### Week 21 (4 h)
**Theory (1.5 h)**
- Instanced rendering + storage buffers
- Indirect draws (optional)

**Practice (2.5 h)**
- Draw 5 000+ simple shapes efficiently (prepare for dense digital twin diagrams)

### Week 22 (4 h)
**Theory (1 h)**
- Debugging techniques (RenderDoc, wgpu traces, validation)

**Practice (3 h)**
- Profile the current demo
- Fix any obvious performance issues
- Add a simple FPS counter

### Week 23 (4 h)
**Practice heavy (4 h)**
- Create a “Flow Field” prototype:
  - Animated lines or particles that represent flow in pipes
  - Controlled by simple uniforms
  - This will later become the animated flow in FlowTwin

### Deliverable at end of Module 03
Solid understanding of custom shaders and multi-pass techniques + a reusable flow animation component.
