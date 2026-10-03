# Module 02 — WebGPU / wgpu Fundamentals
**Estimated time**: 40 hours (10 weeks @ 4 h/week)

### Goal
Master the modern GPU programming model that Graphite is built around.  
By the end you can open a window, create a device, and draw continuously.

### Core Resource
- **Primary**: [Learn wgpu](https://sotrh.github.io/learn-wgpu/) by Ben Hansen (keep it open the whole module)

### Week 7 (4 h)
**Theory (2 h)**
- What is WebGPU / wgpu?
- Read Learn wgpu – Introduction + Windowing
- Watch: [Rust Graphics Programming from Scratch: wgpu for Beginners](https://www.youtube.com/watch?v=EiAMaHQiHN4) (first 30 min)

**Practice (2 h)**
- Follow Learn wgpu tutorial up to “Hello Triangle”
- Get a colored triangle on screen (native)

### Week 8 (4 h)
**Theory (1.5 h)**
- Buffers, bind groups, pipelines
- WGSL basics (variables, vectors, structs)

**Practice (2.5 h)**
- Complete Learn wgpu up to “Buffers and Indices”
- Draw a colored quad with vertex + index buffers

### Week 9 (4 h)
**Theory (1.5 h)**
- Textures and samplers
- Uniform buffers

**Practice (2.5 h)**
- Load a texture and display it
- Add a simple time-based uniform to animate color

### Week 10 (4 h)
**Theory (1 h)**
- Depth buffer and basic 3D concepts (even though we stay mostly 2D later)

**Practice (3 h)**
- Render two overlapping textured quads with depth testing
- Experiment with clear colors and surface configuration

### Week 11 (4 h)
**Theory (1.5 h)**
- Instance rendering
- Camera / orthographic projection for 2D

**Practice (2.5 h)**
- Draw 100–1000 small instances (good mental model for many digital-twin elements)
- Implement a simple 2D camera (pan + zoom with mouse)

### Week 12 (4 h)
**Theory (1 h)**
- Error handling and validation layers
- Surface recreation on resize

**Practice (3 h)**
- Make the application robust to window resize
- Add keyboard controls (WASD or arrows) for camera

### Week 13 (4 h)
**Theory (1.5 h)**
- Compute shaders introduction
- Storage buffers

**Practice (2.5 h)**
- Simple compute shader that updates particle positions
- Or a compute pass that generates a simple heatmap texture

### Week 14 (4 h)
**Theory (1 h)**
- wgpu on the web (WASM)
- Differences between native and browser

**Practice (3 h)**
- Follow Learn wgpu WASM section
- Deploy the current triangle/quad demo to the browser

### Week 15 (4 h)
**Theory (1 h)**
- Review of the whole pipeline model

**Practice (3 h)**
- Clean up the project structure
- Create a reusable `Renderer` struct that owns device, queue, surface, etc.
- Document the architecture in a short README

### Week 16 (4 h)
**Practice heavy (4 h)**
- Build a small “live data visualizer”:
  - Background grid
  - Moving colored circles whose positions come from the Sensor Simulator of Module 01
  - Use channels or shared state to feed data into the render loop

### Deliverable at end of Module 02
A robust wgpu application that can display live data, has camera controls, runs natively and in the browser.
