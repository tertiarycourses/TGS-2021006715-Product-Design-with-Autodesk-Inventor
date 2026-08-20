# Lab 6: Production Drawing and GD&T Package

**Mapping:** LO5 · A9, A10 · K7  
**Estimated time:** 90 minutes  
**Scenario:** Create a release-ready drawing for an engine-block component using views, dimensions, tolerances and a functional datum reference frame.

## Outcome

A multi-view IDW drawing with section/detail views, dimensions, GD&T, notes and completed release checklist.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Activate the lab project and open the supplied Engine Block.ipt from the copied drawing-pack folder.
2. Review the part orientation, physical material, units and model status before creating the drawing.
3. Create a new IDW from the approved standard template and verify sheet size, projection convention, units and title block.
4. Place a base view at an appropriate scale and orientation, then create aligned front, top, side and isometric projected views.
5. Create a section view that exposes the critical internal passage or bore and label the cutting plane clearly.
6. Create a detail view for the critical fit or edge feature and set a scale that supports annotation.
7. Define a functional datum reference frame: identify the primary mounting plane, secondary locating feature and tertiary clocking feature.
8. Add general dimensions from the functional datums and remove any duplicate or non-manufacturing dimension.
9. Apply baseline or ordinate dimensions to coordinate features and use chain dimensions only where accumulation is acceptable.
10. Add size tolerances and the required feature control frame, datum identifiers and material-condition modifier where justified.
11. Add surface, hole/thread, material, finish and general-tolerance notes required by the design brief.
12. Check that every annotation is attached, legible, inside the printable area and consistent with the selected standard.
13. Change one model dimension, update the drawing and inspect every affected view, dimension and annotation for unintended movement.
14. Complete the release checklist covering title block, revision, views, scales, units, tolerances, GD&T, material, notes and approval.
15. Save the IDW and export a PDF; capture the datum scheme, feature control frame and final sheet for evidence.

## Acceptance criteria

- [ ] Base, projected, section, detail and isometric views are correctly aligned and readable.
- [ ] Dimensions are non-duplicated, trace to functional datums and avoid uncontrolled tolerance chains.
- [ ] GD&T is syntactically complete and the datum scheme reflects assembly or inspection function.
- [ ] The drawing updates associatively and passes the release checklist.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
