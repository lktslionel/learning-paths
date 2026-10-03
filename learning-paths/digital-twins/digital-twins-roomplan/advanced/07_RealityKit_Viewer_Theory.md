# Week 7 – RealityKit & Interactive Viewer (Theory)

**Time:** 4 hours  
**Type:** Theory  
**Goal:** Understand how to build an interactive digital-twin viewer with RealityKit.

---

## Schedule

| Block                  | Duration | Activity |
|------------------------|----------|----------|
| RealityKit Core        | 1 h 30 m | Entities, Components, Systems |
| Reality Composer Pro   | 1 h 15 m | Scene assembly concepts |
| Interaction Patterns   | 1 h 15 m | Selection, attachments, UI |

---

## Required Resources

1. **RealityKit Documentation**  
   https://developer.apple.com/documentation/realitykit

2. **Reality Composer Pro**  
   https://developer.apple.com/documentation/realitycomposerpro  
   https://developer.apple.com/reality-composer-pro/

3. Useful WWDC sessions (search Apple Developer):
   - Meet Reality Composer Pro (WWDC23)
   - Build spatial experiences with RealityKit

4. Entity-Component-System mental model (any good RealityKit intro article)

---

## Learning Objectives
- How to load a USDZ into a RealityKit scene
- Difference between ModelEntity, AnchorEntity, and custom components
- How to implement selection and highlight
- How to attach SwiftUI views to 3D entities
- Best practices for performance with multi-room models

---

## Deliverable
Architecture sketch for the HomeTwin viewer:
- Scene graph structure
- Selection system
- UI overlay approach
- Data flow between CapturedStructure and RealityKit entities