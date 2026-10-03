# Week 4 – Multi-Room Scanning Pipeline (Practice)

**Time:** 4 hours  
**Type:** Practice  
**Goal:** Extend HomeTwin to support multi-room capture and merging.

---

## Schedule

| Block                | Duration | Activity |
|----------------------|----------|----------|
| Continuous Session   | 1 h 30 m | Implement continuous ARSession flow |
| StructureBuilder     | 1 h 30 m | Merge rooms into CapturedStructure |
| Export & Test        | 1 h      | Full multi-room USDZ + device test |

---

## Required Resources

- WWDC23 session (reference)  
  https://developer.apple.com/videos/play/wwdc2023/10192/

- StructureBuilder docs  
  https://developer.apple.com/documentation/roomplan/structurebuilder

- Previous single-room code from Week 2

---

## Tasks

1. Refactor scanning so the ARSession can continue across multiple rooms (`pauseARSession: false`).
2. Collect an array of `CapturedRoom`.
3. Use `StructureBuilder` to produce a `CapturedStructure`.
4. Export the merged structure as USDZ.
5. Add simple UI to:
   - Start new room
   - Finish structure
   - Preview / export
6. Test with a real 2–3 room space (e.g. living room + kitchen + hallway).

---

## Success Criteria
- [ ] Multiple rooms can be scanned without losing tracking
- [ ] Merged structure exports correctly
- [ ] Walls and openings align reasonably between rooms
- [ ] App recovers gracefully from tracking loss

---

## Deliverable
Multi-room capable HomeTwin + example merged USDZ of a real space.