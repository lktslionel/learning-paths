# RoomPlan + USDZ Digital Twin Learning Path

**Pace:** 4 hours per week  
**Duration:** 12 weeks (≈ 48 hours total)  
**End Goal:** A production-ready prototype iOS app called **HomeTwin** that lets users:
- Scan multiple rooms with RoomPlan
- Merge them into a coherent structure
- View an interactive digital twin with measurements and object selection
- Export enriched USDZ files
- Share the twin

This path alternates **Theory** and **Practice** every week and builds one continuous product.

---

## Product Vision (HomeTwin)

A polished iOS/iPadOS app (LiDAR required) that produces usable digital twins of residential homes and small buildings.

**Core features of the final prototype:**
1. Guided multi-room scanning with continuous ARSession
2. Automatic merging via `StructureBuilder`
3. Interactive 3D viewer (RealityKit) with:
   - Room selection & floor switching
   - Dimension overlays
   - Object selection & info cards
4. USDZ export (parametric + model variants)
5. Basic project management (save / load / share)
6. Clean, production-quality UI and error handling

---

## Weekly Structure (4 hours)

| Type     | Time   | Focus                          |
|----------|--------|--------------------------------|
| Theory   | 1.5 h  | Concepts, docs, videos         |
| Practice | 2.5 h  | Coding & building the product  |

---

## Module Index

| Week | Module                                      | Type     | File                          |
|------|---------------------------------------------|----------|-------------------------------|
| 1    | RoomPlan Foundations                        | Theory   | [01_RoomPlan_Foundations.md](01_RoomPlan_Foundations.md) |
| 2    | Single-Room Scanner                         | Practice  | [02_Single_Room_Scanner.md](02_Single_Room_Scanner.md) |
| 3    | Multi-Room & StructureBuilder               | Theory   | [03_MultiRoom_Theory.md](03_MultiRoom_Theory.md) |
| 4    | Multi-Room Scanning Pipeline                | Practice  | [04_MultiRoom_Pipeline.md](04_MultiRoom_Pipeline.md) |
| 5    | OpenUSD Foundations                         | Theory   | [05_OpenUSD_Foundations.md](05_OpenUSD_Foundations.md) |
| 6    | Enriching RoomPlan USDZ                     | Practice  | [06_Enrich_USDZ.md](06_Enrich_USDZ.md) |
| 7    | RealityKit & Interactive Viewer             | Theory   | [07_RealityKit_Viewer_Theory.md](07_RealityKit_Viewer_Theory.md) |
| 8    | Interactive Digital Twin Viewer             | Practice  | [08_Interactive_Viewer.md](08_Interactive_Viewer.md) |
| 9    | Production Polish & Project Management      | Practice  | [09_Production_Polish.md](09_Production_Polish.md) |
| 10   | Custom Models & Advanced Export             | Theory + Practice | [10_Custom_Models_Export.md](10_Custom_Models_Export.md) |
| 11   | Testing, Edge Cases & Industrial Limits     | Theory + Practice | [11_Limits_Testing.md](11_Limits_Testing.md) |
| 12   | Final Integration & Release Candidate       | Practice  | [12_Final_Prototype.md](12_Final_Prototype.md) |

---

## Prerequisites
- Mac with Xcode (latest stable)
- LiDAR-equipped iPhone or iPad (iPhone 12 Pro or newer / recent iPad Pro)
- Basic Swift and SwiftUI knowledge
- Apple Developer account (free is enough for device testing)

---

## How to Use This Path
1. Create a new Xcode project named **HomeTwin** at the start of Week 2.
2. Work in the same project every week — the app grows end-to-end.
3. Commit after every practice week.
4. Keep a simple `NOTES.md` for learnings and decisions.