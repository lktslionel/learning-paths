# Week 8 – Interactive Digital Twin Viewer (Practice)

**Time:** 4 hours  
**Type:** Practice  
**Goal:** Build the core interactive viewer inside HomeTwin.

---

## Schedule

| Block              | Duration | Activity |
|--------------------|----------|----------|
| Load & Display     | 1 h      | Show merged structure in RealityView |
| Selection System   | 1 h 30 m | Tap to select walls / objects |
| UI Overlays        | 1 h 30 m | Dimensions + info cards |

---

## Required Resources

- RealityKit docs  
  https://developer.apple.com/documentation/realitykit

- Previous multi-room export from Week 4
- Your architecture notes from Week 7

---

## Tasks

1. Create a dedicated Viewer screen that loads a `CapturedStructure` or USDZ.
2. Implement basic camera controls (orbit / pan / zoom).
3. Add tap-to-select for surfaces and objects.
4. Show a simple info card (name, category, dimensions) when an element is selected.
5. Display overall room / structure dimensions.
6. Support switching between individual rooms if the structure contains several.

---

## Success Criteria
- [ ] Multi-room model loads and renders smoothly
- [ ] User can select walls, doors, windows, and furniture
- [ ] Relevant dimensions appear on selection
- [ ] Viewer feels responsive on device

---

## Deliverable
Interactive viewer integrated into HomeTwin.