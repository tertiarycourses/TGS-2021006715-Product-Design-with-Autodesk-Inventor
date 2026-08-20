# Lab 5: Convert an Assembly to a Weldment

**Mapping:** LO4 · A6, A7 · K6  
**Estimated time:** 70 minutes  
**Scenario:** Prepare a small fabricated bracket assembly for welding, inspection and post-weld machining using supplied assembly components.

## Outcome

A weldment IAM showing preparation, weld and machining groups plus a fabrication-review sheet.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Open the copied Universal Joint.iam only as a component source and save a separate working assembly named Lab05-Welded-Bracket.iam.
2. Remove components that are not part of the fabricated bracket and position the remaining parts with clear joint access.
3. Assign candidate physical materials and compare weldability, strength, corrosion exposure, availability and cost.
4. Save a baseline copy, then choose Environments > Convert to Weldment and select the required standard and weld-bead material.
5. Enter the Preparations group and create the required edge chamfer, gap or relief before the joint is welded.
6. Enter the Welds group and create a fillet, groove or cosmetic weld that matches the joint design.
7. Set weld length, intermittent pitch or extent as required and confirm the weld direction and participating faces.
8. Enter the Machining group and add the specified post-weld face or hole operation.
9. Inspect the browser order and explain why preparation, weld and machining features must remain in sequence.
10. Check mass properties and BOM structure, then record whether the weldment reports as one fabricated item or individual components.
11. Create a drawing view and add the applicable weld symbol, material note and inspection requirement.
12. Review access for torch, fixture, inspection and post-weld tool; mark any design change needed.
13. Create a simple presentation or snapshot sequence that distinguishes before-weld, after-weld and post-machining states.
14. Save, reopen and update the weldment to confirm no failed group or missing component reference.
15. Capture preparation, weld, machining, drawing symbol and review notes for evidence.

## Acceptance criteria

- [ ] The working IAM is a weldment with correctly ordered preparation, weld and machining features.
- [ ] Material choice is justified using at least four relevant criteria.
- [ ] The drawing communicates weld type, extent and inspection intent under the selected standard.
- [ ] Fabrication access and post-weld operations have been reviewed and recorded.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
