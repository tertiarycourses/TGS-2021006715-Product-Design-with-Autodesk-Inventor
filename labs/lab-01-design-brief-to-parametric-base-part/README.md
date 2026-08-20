# Lab 1: Design Brief to Parametric Base Part

**Mapping:** LO1 · A1, A2 · K1, K2  
**Estimated time:** 75 minutes  
**Scenario:** Create a controllable base component for a compact universal-joint guard and prove that the sketch captures the design brief.

## Outcome

A fully constrained IPT part, a one-page design-intent note and evidence screenshots.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Read the functional brief and record the mounting envelope, interface faces, minimum wall, edge-clearance and service-access requirements.
2. Start Inventor and create or activate a single-user project whose workspace is this lab folder; confirm the project points to the local samples directory.
3. Open Base Form Start.ipt, use Save As to create Lab01-Guard-Base.ipt, and confirm millimetres are the active units.
4. Inspect the Origin folder and choose the XY plane as the primary sketch plane so the central symmetry of the part is stable.
5. Create a centre rectangle for the base footprint and constrain its centre coincident with the origin.
6. Add horizontal, vertical, equal and symmetry constraints before applying dimensions; drag the geometry and identify any remaining degrees of freedom.
7. Apply named dimensions for overall length, width and mounting-edge offset; use the Parameters dialog to rename them GuardLength, GuardWidth and EdgeOffset.
8. Finish the sketch and extrude the base using a named thickness parameter; set the operation to Join.
9. Create a second sketch for the mounting holes, project only the centre reference needed, and constrain the hole points symmetrically.
10. Use the Hole feature with the specified diameter and Through All termination; do not model holes as uncontrolled extruded cuts.
11. Add the required fillets and chamfers as finishing features after the primary form and holes.
12. Assign a provisional engineering material, then update mass properties and record the mass as baseline evidence.
13. Change GuardLength by 10 mm and update the model; confirm the holes and finishing features remain correctly located.
14. Rename sketches and features in the browser, resolve every warning, and save the file.
15. Capture the fully constrained sketch, final isometric view, browser tree and parameter table for the evidence checklist.

## Acceptance criteria

- [ ] Sketch reports Fully Constrained and is centred on stable origin geometry.
- [ ] Named parameters control the main dimensions without failed features.
- [ ] The IPT opens from the lab project with no missing reference or update warning.
- [ ] Evidence shows the requirement-to-feature rationale and a successful dimension change.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
