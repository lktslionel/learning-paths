# Module 06 — Digital Twin Core Architecture
**Estimated time**: 32 hours (8 weeks @ 4 h/week)

### Goal
Design and implement a clean, extensible architecture for the digital twin itself (not just the renderer).

### Week 38 (4 h)
**Theory (2 h)**
- Digital twin concepts: digital model, real-time sync, bidirectional control
- Scene graph vs immediate mode for 2D industrial UIs
- Entity-Component ideas adapted to 2D schematics

**Practice (2 h)**
- Design the data model:
  - `Node` (tank, pump, valve, sensor…)
  - `Connection` (pipe)
  - `Property` (level, flow, status, alarm)
- Write it as Rust structs + enums

### Week 39 (4 h)
**Theory (1.5 h)**
- State management patterns in Rust (signals, channels, ECS-lite)
- Separation of Model / View / Controller

**Practice (2.5 h)**
- Implement a central `TwinState` that holds all nodes and connections
- Make it updatable from the telemetry simulator

### Week 40 (4 h)
**Theory (1 h)**
- Serialization (JSON / RON) for saving / loading plant layouts

**Practice (3 h)**
- Add save / load of the schematic definition
- Create 2–3 different plant layouts as data files

### Week 41 (4 h)
**Theory (1.5 h)**
- Spatial indexing for hit-testing (simple grid or R-tree)
- Transform hierarchy

**Practice (2.5 h)**
- Implement hit-testing: click on a tank → select it
- Highlight selected node

### Week 42 (4 h)
**Practice (4 h)**
- Build the “View” layer:
  - Given `TwinState` + camera, produce Skia draw commands
  - Different visual styles for normal / alarm / selected

### Week 43 (4 h)
**Theory (1 h)**
- Real-time data binding patterns
- Alarm logic

**Practice (3 h)**
- Connect live telemetry to node properties
- Trigger visual alarms when thresholds are crossed
- Add a simple alarm list panel (can be pure Skia or hybrid)

### Week 44 (4 h)
**Practice (4 h)**
- Implement basic interaction:
  - Select node
  - Show properties panel
  - Hover tooltips with live values

### Week 45 (4 h)
**Practice heavy (4 h)**
- Polish the core loop:
  - Telemetry update → state mutation → redraw
  - Keep it under 16 ms if possible
  - Add a debug overlay (FPS, node count, selected id)

### Deliverable at end of Module 06
A working digital twin core: data model + live updates + selection + visual feedback.
