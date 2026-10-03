# Week 10 – Custom Models & Advanced Export (Theory + Practice)

**Time:** 4 hours  
**Type:** Mixed  
**Goal:** Replace bounding boxes with detailed models and improve export quality.

---

## Schedule

| Block                    | Duration | Activity |
|--------------------------|----------|----------|
| Theory – Custom Catalogs | 1 h 15 m | ModelProvider & catalogs |
| Practice – Catalog       | 1 h 45 m | Create simple catalog |
| Practice – Integration   | 1 h      | Use in export pipeline |

---

## Required Resources

1. **Providing custom models for captured rooms and structure exports**  
   https://developer.apple.com/documentation/roomplan/providing-custom-models-for-captured-rooms-and-structure-exports

2. Related sample code (Room Plan Catalog Generator)

3. Reality Composer Pro for preparing simple models

---

## Tasks

1. Study how `ModelProvider` and catalog bundles work.
2. Prepare a small set of replacement models (e.g. chair, table, sofa, bed) — can be simple placeholders.
3. Integrate the catalog into the export path of HomeTwin.
4. Compare parametric vs model export side-by-side.
5. Document the workflow for adding new models in the future.

---

## Success Criteria
- [ ] Exported USDZ uses detailed models for recognized objects when available
- [ ] Fallback to bounding boxes still works
- [ ] Catalog is maintainable

---

## Deliverable
HomeTwin with improved visual quality on export + short catalog guide.