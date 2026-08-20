# Lab 4: Top-Down Layout and Assembly Relationships

**Mapping:** LO3 · A4, A5 · K5  
**Estimated time:** 75 minutes  
**Scenario:** Control a universal-shaft variant from a master layout and compare that interface-driven approach with the bottom-up assembly.

## Outcome

A layout-controlled IAM variant with documented mate, insert and angle relationships.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Open Universal Shaft Start.iam from the copied layout-assembly folder and save it as Lab04-Layout-Controlled-Shaft.iam.
2. Create a layout sketch at assembly origin that defines the shaft centreline, joint centres and operating angle.
3. Name the governing dimensions ShaftSpacing and OperatingAngle and record their initial values.
4. Project or derive only the stable layout geometry required by the component interfaces.
5. Place or create the base component in context and align it to the master layout.
6. Place the remaining supplied components and apply mate/flush relationships to locate planar interfaces.
7. Apply insert relationships for pins and bores, checking that rotation is not removed unintentionally.
8. Apply the operating-angle relationship and set safe limits where appropriate.
9. Use the browser to rename relationships by function, for example PinAxis_Insert and YokeAngle_Limit.
10. Suppress one relationship at a time and observe the returned DOF; use the test to identify redundant constraints.
11. Change ShaftSpacing and OperatingAngle within the brief, update the assembly and repair any unstable reference.
12. Create a positional representation for the nominal configuration and another for the service angle.
13. Compare top-down and bottom-up approaches in the evidence sheet: ownership, change propagation, reuse and risk.
14. Create or update the assembly drawing so both configurations can be reviewed clearly.
15. Pack all dependencies in the lab folder and reopen the IAM to confirm portability.

## Acceptance criteria

- [ ] Named layout parameters control the key interfaces and update the assembly predictably.
- [ ] No redundant or conflicting relationship remains in the browser.
- [ ] Nominal and service positional representations are saved and demonstrably different.
- [ ] The comparison correctly distinguishes top-down interface control from bottom-up reuse.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
