# Week 6 – Enriching RoomPlan USDZ (Practice)

**Time:** 4 hours  
**Type:** Practice  
**Goal:** Take raw RoomPlan USDZ files and turn them into richer, more useful stages.

---

## Schedule

| Block                | Duration | Activity |
|----------------------|----------|----------|
| Inspect RoomPlan USDZ| 45 m     | Hierarchy exploration |
| Composition Practice | 1 h 45 m | References, layers, metadata |
| Integration in App   | 1 h 30 m | Load enriched stages in HomeTwin |

---

## Required Resources

- NVIDIA Learn OpenUSD (continue previous modules)
- Apple USD documentation
- Reality Composer Pro (for visual inspection)  
  https://developer.apple.com/documentation/realitycomposerpro

- Tools: `usdview` (if available) or Reality Composer Pro

---

## Tasks

1. Open several RoomPlan-exported USDZ files and document their hierarchy.
2. Create a simple composed stage that references multiple room USDZ files.
3. Add basic metadata (room name, area, scan date).
4. Experiment with a variant set (e.g. “empty” vs “furnished”).
5. Load the composed stage back into the HomeTwin app (even if only as a static preview).

---

## Success Criteria
- [ ] You can explain the prim hierarchy of a RoomPlan USDZ
- [ ] You have at least one multi-room composed USD stage
- [ ] The stage opens correctly in Reality Composer Pro / Quick Look

---

## Deliverable
Enriched multi-room USD stage + notes on the composition approach used.