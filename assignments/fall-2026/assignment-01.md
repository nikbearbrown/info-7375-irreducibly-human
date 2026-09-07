# Assignment 1 — Task boundaries and pattern baselines

**INFO 7375 · Irreducibly Human · Fall 2026 · 100 points · Due: Canvas**

[AI Policy for Professor Bear's Courses | Using AI Responsibly in Class](https://youtu.be/8Ut0Cdl6vMw?si=9w3aEpt1ZyAR4Kiz)

**Predict → Build It → Use It → Ship It → Verify**

Bundle [Lesson 1](../../lessons/01-task-and-tier/README.md) and [Lesson 2](../../lessons/02-pattern-baselines/README.md) into one submission. Lesson Assessments are ungraded practice.

## Predict

Which parts of one familiar task would you delegate, supervise, or retain? Predict a failure condition for each. Will human edits improve a baseline classifier on a frozen set of examples? State your expectation before seeing its errors. Preserve the original before receiving output or critique.

## Build It

Build a Python task-map validator for task ID, human capacity, proposed tier, dated capability evidence, delegation choice, owner, and review condition. Keep the taxonomy separate from the changing capability assessment.

Implement a small deterministic Python classifier and accuracy/confusion-count calculator. Define a held-out set and a documented override rule; preserve the pre-override predictions.

## Use It

Ask Claude to critique your initial task map and propose a counterexample to one classification. Revise only with an explanation.

Ask Claude to propose improvements after the baseline is recorded. Compare baseline and revised results on frozen cases. Label a deterministic surrogate as a surrogate, not as Claude.

## Ship It

Submit task map, validator, evidence notes, and original prediction; baseline code, frozen cases, override record, and comparison. Include the Python implementation, tests, inputs, evidence, README, PREDICTIONS.md, CONTRIBUTIONS.md, FRICTIONAL.md, and VERIFICATION.md. Identify source material and real assistance. The final version goes to the designated GitHub location and Canvas.

## Verify

Test missing evidence, unknown tiers, and duplicate IDs. Show that a syntactically valid map can still contain a debatable classification.

Hand-check counts on four cases; test empty input and invalid labels. Report degradation as honestly as improvement. A small task does not establish general AI or human superiority.

Check the shipped candidate, record actual outcomes, and explain the bounded conclusion. Do not fabricate human participants, permissions, findings, or understanding. If a learning exercise uses a simulation, label it throughout.

## Division of labor

**AI should** organize task records and propose alternative classifications; suggest candidate rules and calculate comparisons.

**Human should** make the initial task decomposition, justify the boundary, and own the delegation decision; choose the test, justify each override, and interpret the bounded result.

## Rubric — 100 points

| Implementation criterion | Points | Full-credit evidence |
|---|---:|---|
| Prediction and acceptance contract | 8 | Specific original expectations, assumptions, and a measurable failure condition. A wrong prediction alone does not lose credit. |
| Python implementation | 22 | Working requested mechanisms with documented inputs, outputs, and meaningful boundaries. |
| Applied use and evidence | 12 | Actual application to the stated task, preserved outputs, and explicit fixture/live distinctions. |
| Verification | 12 | The specified hand checks and failure cases, reproduction of the shipped version, and candid limits. |
| Technical handoff and explanation | 6 | Explainable mechanisms, reproducible commands, credited sources, and a conclusion supported by the evidence. |
| **Implementation subtotal** | **60** | |
| [Frictional](../../prerequisites/frictional.md) | 10 | Honest effort and learning log. |
| [GitHub posting](../../prerequisites/github-submission.md) | 10 | Correctly delivered, identifiable version matching Canvas. |
| [Relative Quartile](../../prerequisites/relative-quartile.md) | 20 | Overall quality relative to peers after all submissions are reviewed. |
| **Total** | **100** | |

For implementation rows, award full points for complete evidence, proportionate partial credit for a documented partial implementation, and zero when the required evidence is absent. Explain deductions. The technical handoff row assesses usability and understanding; GitHub points assess delivery. Frictional assesses the actual process, not whether the result succeeded. A finding that survives the audit can earn full credit when checks are discriminating and scope is honest.

An explainer video or Brutalist production is optional and may support communication quality within Relative Quartile. It has no separate points; excellent written evidence can earn full credit. Claude Code is assumed; direct API calls and paid media tools are unnecessary.

