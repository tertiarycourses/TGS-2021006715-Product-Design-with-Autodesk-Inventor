# Lab 3: Bottom-Up Universal Joint Assembly

**Mapping:** LO3 · A4, A5 · K5  
**Estimated time:** 90 minutes  
**Scenario:** Assemble the supplied universal-joint components from proven part files and retain the mechanism's intended rotation.

## Outcome

A resolved IAM assembly, a DOF/constraint record and a basic assembly drawing.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Activate the lab project and copy the supplied universal-joint sample folder to a working folder before editing.
2. Open Universal Joint.iam and use Resolve Link only if Inventor reports a missing file; map references to the local working folder, never to the reference folder.
3. Inspect each placed component, its occurrence name and BOM structure; identify the base, yokes, connecting rod, pin and handle.
4. Ground the base occurrence at the assembly origin and confirm that it has no unintended motion.
5. Place any missing component from the working folder and orient it near its final position.
6. Apply the primary mate or flush relationship that locates the component against its functional mounting face.
7. Apply insert or concentric relationships to align pins and cylindrical bores while retaining intended rotation.
8. Use angle or joint limits only where the design brief defines a permitted range; avoid redundant relationships.
9. Use Degrees of Freedom or drag testing after each relationship to confirm which movement was removed.
10. Drive a suitable constraint or joint through a safe range and observe the universal-joint motion.
11. Run Interference Analysis and classify each result as intended contact, fastener engagement or unacceptable overlap.
12. Create a named design view that shows the complete mechanism clearly and save the camera orientation.
13. Create an assembly drawing with base, projected and isometric views plus a parts list and balloons.
14. Save the IAM and drawing, close Inventor, then reopen the IAM from the lab project to verify all references resolve.
15. Capture the browser relationships, interference result, driven motion and assembly drawing for evidence.

## Acceptance criteria

- [ ] All references resolve locally and the assembly opens without warnings.
- [ ] The base is grounded, required components are constrained, and intended rotation remains possible.
- [ ] Interference findings are reviewed and any unacceptable overlap is corrected.
- [ ] The assembly drawing includes views, parts list and balloons that agree with the IAM BOM.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
