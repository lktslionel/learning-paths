# Week 3 – Multi-Room & StructureBuilder (Theory)

**Time:** 4 hours  
**Type:** Theory  
**Goal:** Understand how to capture and merge multiple rooms into one coherent structure.

---

## Schedule

| Block          | Duration | Activity |
|----------------|----------|----------|
| Core Video     | 1 h 15 m | WWDC23 MultiRoom session |
| Documentation  | 1 h 30 m | StructureBuilder + continuous ARSession |
| Synthesis      | 1 h 15 m | Architecture notes for HomeTwin |

---

## Required Resources

1. **WWDC23 Session** (must watch)  
   Explore enhancements to RoomPlan  
   https://developer.apple.com/videos/play/wwdc2023/10192/

2. **StructureBuilder Documentation**  
   https://developer.apple.com/documentation/roomplan/structurebuilder

3. **CapturedStructure**  
   https://developer.apple.com/documentation/roomplan/capturedstructure

4. Related sample code mentioned in the WWDC session (Scan-merging sample)

---

## Learning Objectives
- Difference between independent room captures and continuous ARSession
- How `StructureBuilder` merges multiple `CapturedRoom` instances
- Coordinate system alignment and relocalization with `ARWorldMap`
- Practical limits (area, number of rooms, single-floor preference)
- What `CapturedStructure` contains after merging

---

## Deliverable
Update your notes with:
- Recommended scanning workflow for a 2–4 room home
- Decision: continuous ARSession vs ARWorldMap relocalization for HomeTwin
- Open questions about multi-floor support

---

## Next Week
You will implement the multi-room pipeline in the app.