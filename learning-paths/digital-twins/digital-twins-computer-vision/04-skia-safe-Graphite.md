# Module 04 — skia-safe & Graphite Basics
**Estimated time**: 32 hours (8 weeks @ 4 h/week)

### Goal
Master drawing with Skia through skia-safe, using the modern Graphite backend.

### Core Resources
- [rust-skia GitHub](https://github.com/rust-skia/rust-skia)
- [skia-safe docs](https://docs.rs/skia-safe)
- Official Skia docs: https://skia.org/docs/
- Graphite examples inside the rust-skia repository

### Week 24 (4 h)
**Theory (2 h)**
- What is Skia? What is Graphite vs Ganesh?
- Read the rust-skia README carefully (features, Graphite section)
- Chromium blog posts about Graphite

**Practice (2 h)**
- Add `skia-safe` with `graphite` + `metal` (or `vulkan`) features
- Run the official `metal-window-graphite` example
- Make a small change (different color / shape)

### Week 25 (4 h)
**Theory (1.5 h)**
- Graphite programming model: Context → Recorder → Recording → submit
- SkCanvas, Paint, Path, Surface

**Practice (2.5 h)**
- Create a Graphite Context and Recorder yourself
- Draw basic shapes (rect, circle, path) every frame

### Week 26 (4 h)
**Theory (1.5 h)**
- Text rendering with skparagraph / textlayout feature
- Font management

**Practice (2.5 h)**
- Draw high-quality text labels
- Experiment with different fonts and paragraph styles

### Week 27 (4 h)
**Theory (1 h)**
- Images, shaders, gradients, path effects

**Practice (3 h)**
- Load and draw images
- Create linear/radial gradients
- Apply a simple path effect

### Week 28 (4 h)
**Theory (1.5 h)**
- Transforms, clipping, layers
- Save/restore state

**Practice (2.5 h)**
- Implement zoom + pan using Skia matrices
- Clip a region and draw inside it

### Week 29 (4 h)
**Theory (1 h)**
- Performance considerations with Graphite
- Multi-threaded recording (concept)

**Practice (3 h)**
- Draw a more complex static schematic (tanks + pipes + valves) using paths
- Measure frame time

### Week 30 (4 h)
**Theory (1 h)**
- Backend textures and interop possibilities (preview for next module)

**Practice (3 h)**
- Create an offscreen Graphite surface
- Read pixels back or save to PNG
- Build a small “static plant diagram” renderer

### Week 31 (4 h)
**Practice heavy (4 h)**
- Integrate the Sensor Simulator from Module 01
- Color the tanks and pipes according to live values
- Add simple animated flow indicators using Skia paths + time

### Deliverable at end of Module 04
A Graphite-powered 2D schematic that reacts to live simulated data.
