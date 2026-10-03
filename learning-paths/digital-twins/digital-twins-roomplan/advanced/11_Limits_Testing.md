# Week 11 – Testing, Edge Cases & Industrial Limits (Theory + Practice)

**Time:** 4 hours  
**Type:** Mixed  
**Goal:** Understand real-world limits and harden the prototype.

---

## Schedule

| Block                  | Duration | Activity |
|------------------------|----------|----------|
| Theory – Limits        | 1 h 15 m | Accuracy, size, multi-floor, industrial |
| Practice – Edge Cases  | 1 h 45 m | Stress testing on device |
| Documentation          | 1 h      | Limitations section + mitigation ideas |

---

## Key Topics to Research

- Maximum recommended area and room count
- Behavior with high ceilings, slanted walls, complex geometry
- Multi-floor realities
- Accuracy expectations for measurements
- When to switch to denser capture methods (Open3D, terrestrial LiDAR, etc.)

Useful starting points:
- Apple RoomPlan documentation (limitations sections)
- Community reports and blog posts about RoomPlan accuracy
- Open3D tutorials (for future hybrid pipelines)  
  https://www.open3d.org/docs/release/getting_started.html

---

## Tasks

1. Test HomeTwin in challenging environments (large rooms, poor lighting, clutter).
2. Document failure modes and current mitigations.
3. Add any missing guardrails in the app (warnings, size checks, tracking quality indicators).
4. Write a short “When to use HomeTwin vs other tools” guide.

---

## Deliverable
Updated app with better resilience + clear limitations documentation.