# Module 07 — Interactive Scene & UX
**Estimated time**: 28 hours (7 weeks @ 4 h/week)

### Goal
Turn the technical prototype into a usable, pleasant digital twin interface.

### Week 46 (4 h)
**Theory (1.5 h)**
- UX principles for industrial / SCADA interfaces
- Information density vs clarity

**Practice (2.5 h)**
- Improve visual design of nodes (better icons / shapes / colors)
- Consistent status color language (green / yellow / red / gray)

### Week 47 (4 h)
**Practice (4 h)**
- Smooth camera controls (inertia, zoom-to-cursor, double-click fit)
- Minimap (optional but very useful)

### Week 48 (4 h)
**Theory (1 h)**
- Animation principles (easing, secondary motion)

**Practice (3 h)**
- Animated flow in pipes (using the flow component from Module 03 or pure Skia)
- Pulsing alarms
- Smooth value transitions

### Week 49 (4 h)
**Practice (4 h)**
- Properties / details panel (can be Skia-drawn or a simple egui/wgpu overlay)
- Ability to change setpoints (write back to the simulator)

### Week 50 (4 h)
**Theory (1.5 h)**
- Accessibility and readability (font sizes, contrast)
- Multi-monitor / HiDPI considerations

**Practice (2.5 h)**
- Make the UI look good at different scales
- Add keyboard shortcuts (space = fit, F = focus selected, etc.)

### Week 51 (4 h)
**Practice (4 h)**
- Historical mini-sparklines next to sensors (simple line charts drawn with Skia)
- Or a small time-series buffer per important property

### Week 52 (4 h)
**Practice heavy (4 h)**
- Full user journey test:
  1. Load a plant layout
  2. See live data
  3. Select equipment
  4. Observe alarms
  5. Change a setpoint
  6. Zoom / pan around
- Fix any friction points

### Deliverable at end of Module 07
A polished, interactive digital twin UI that feels usable.
