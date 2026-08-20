# Lab 8: Material, Automation and Final Design Review

**Mapping:** LO6 · A11 · K6, K8  
**Estimated time:** 75 minutes  
**Scenario:** Review an engine-block part against requirements, compare material options and encode a controlled design variant using named parameters and a simple rule.

## Outcome

A reviewed IPT variant, material decision matrix, parameter/rule evidence and signed design-review checklist.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Open Engine Block Review.ipt and use Save As to create Lab08-Engine-Block-Review.ipt.
2. Read the design brief and create a review matrix covering function, envelope, interfaces, material, manufacture, safety, service and evidence.
3. Inspect model health, feature naming, sketch constraint status and update warnings; record each issue before editing.
4. Create named user parameters for two dimensions that define a controlled product variant.
5. Set realistic minimum and maximum values from the brief and test both bounds for feature failure or impossible geometry.
6. Assign the first candidate material and update mass properties; record density, mass and relevant manufacturing implications.
7. Repeat for at least two alternative materials and compare strength, stiffness, corrosion, machinability, availability, cost and mass.
8. Select a preferred material and explain the trade-off rather than choosing only the lightest or strongest option.
9. Create a simple iLogic rule or parameter check that warns when a controlled dimension is outside the approved range.
10. Run the rule at nominal, minimum and maximum values and capture the result.
11. Inspect the precision drawing and identify which views, dimensions or tolerances must be reviewed after the design change.
12. Apply one approved improvement, update the model and drawing, and record the before/after evidence.
13. Complete a DFMA review covering part count, tool access, setup count, standard features, handling and service replacement.
14. Record the issue, decision, affected files, evidence, owner and approval status in the change log.
15. Save and reopen the part, run Update and confirm the final design review has no unresolved blocker.

## Acceptance criteria

- [ ] Review evidence addresses all stated requirements and clearly separates fact, assumption and recommendation.
- [ ] Material decision uses multiple performance and manufacturing criteria with traceable mass-property evidence.
- [ ] Named parameters and the rule control a valid range without failing the model.
- [ ] The approved change, affected drawing and DFMA implications are recorded before release.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
