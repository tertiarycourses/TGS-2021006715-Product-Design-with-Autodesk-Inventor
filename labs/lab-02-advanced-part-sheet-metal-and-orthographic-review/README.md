# Lab 2: Advanced Part, Sheet Metal and Orthographic Review

**Mapping:** LO2 · A3, A8 · K3, K4  
**Estimated time:** 90 minutes  
**Scenario:** Develop two alternative CAD models for a protective cover: a lofted solid concept and a manufacturable folded-sheet option.

## Outcome

A parametric lofted part, a sheet-metal part with flat pattern, and orthographic verification views.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Activate the lab project, open Loft Start.ipt and save a working copy named Lab02-Lofted-Cover.ipt.
2. Inspect the existing profiles and list the section order, plane offsets and intended symmetry before creating the loft.
3. Create or repair the required offset work plane and confirm its parent references are stable origin or named work features.
4. Project only the centre and boundary geometry required to position each new section; avoid projecting every visible edge.
5. Constrain and dimension each loft section; confirm there are no open loops or overlapping profiles.
6. Create the Loft feature, select sections in a consistent order and add a centreline or rail only when it improves control.
7. Use zebra/curvature or visual inspection to identify unwanted pinching; edit the section or rail instead of hiding the defect with a fillet.
8. Apply mirror or pattern features for repeated details and verify the feature count and direction.
9. Open Sheet Metal Start.ipt, save Lab02-Sheet-Cover.ipt and verify the sheet-metal rule, thickness, bend radius and relief settings.
10. Create the base face, add flanges and reliefs, and check bend directions against the design envelope.
11. Generate the flat pattern and inspect overlaps, bend lines, reliefs and material continuity.
12. Create an IDW drawing with front, top, right and isometric views for each concept; use equal scales and consistent orientation.
13. Compare the two concepts against mass, fabrication steps, service access and evidence clarity.
14. Update one governing dimension in each model and confirm the loft, flat pattern and drawing views update without error.
15. Save all files and capture the loft sections, flat pattern and orthographic sheet as assessment evidence.

## Acceptance criteria

- [ ] Loft sections are fully constrained and the resulting body has no visible discontinuity or failed feature.
- [ ] Sheet-metal thickness and bend rule are consistent and the flat pattern is valid.
- [ ] Orthographic views agree with the 3D models and show the intended geometry clearly.
- [ ] The design comparison explains why one modelling method is preferred for production.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
