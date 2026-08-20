# Lab 7: Exploded View, Storyboard and Animation

**Mapping:** LO6 · A6, A7 · K8  
**Estimated time:** 70 minutes  
**Scenario:** Explain the assembly and service order of a small engine using an exploded presentation and a concise animation.

## Outcome

An IPN presentation with trails, snapshots and storyboard plus an exported review video or image sequence.

## Before you begin

- Use Autodesk Inventor 2024 or later on Windows.
- Create or activate an Inventor project whose workspace is this lab folder.
- Work from a copy of the supplied sample files; preserve the originals for recovery.
- Keep every dependent IPT/IAM/IPN/IDW file inside this lab folder.

## Detailed procedure

1. Activate the lab project, open Engine.iam from the copied engine-presentation folder and confirm all component references resolve.
2. Create a new Standard.ipn presentation and insert Engine.iam as the source model for Scene1.
3. Set a clear isometric camera and create an initial snapshot view before applying any tweaks.
4. Group components by assembly sequence and plan explode directions that do not cause visually impossible intersections.
5. Apply component tweaks in logical order, keeping related fasteners and parts on consistent axes where appropriate.
6. Enable trails selectively so they clarify movement without turning the view into clutter.
7. Create intermediate snapshot views for the major assembly stages and give them descriptive names.
8. Create a storyboard and arrange tweak actions on the timeline in the intended assembly or service order.
9. Adjust duration and start time so the viewer can follow each major stage without unnecessary delay.
10. Add a restrained camera action only if it reveals a hidden relationship; do not use motion as decoration.
11. Play the storyboard, check for collisions, confusing paths and components that move before their fasteners.
12. Edit the timeline until the static snapshots and animated sequence tell the same assembly story.
13. Create a drawing from the IPN and place an exploded view with balloons or trail visibility as required.
14. Publish a video or sequential images using a clear resolution and neutral background.
15. Save the IPN and capture the scene browser, timeline, exploded snapshot and exported output for evidence.

## Acceptance criteria

- [ ] All presentation references resolve and the source IAM remains unchanged.
- [ ] Exploded paths are readable, non-colliding and consistent with a plausible assembly sequence.
- [ ] Storyboard timing and snapshots communicate the same ordered narrative.
- [ ] The exported output and drawing view are legible and suitable for stakeholder review.

## Evidence to submit

- The completed native Inventor file set in this lab folder.
- Screenshots named `evidence-01.png`, `evidence-02.png`, and so on, matching the acceptance criteria.
- A short `review-notes.md` stating the requirement, decision, result and any unresolved issue.

## Troubleshooting

- If a reference is missing, stop and resolve it to the local `samples/` or working folder; do not browse back to `reference/`.
- If an update fails, inspect the earliest failed feature or relationship in the browser before editing downstream items.
- If a drawing or presentation looks stale, update the source model first, then update the dependent document and re-check every affected view.
