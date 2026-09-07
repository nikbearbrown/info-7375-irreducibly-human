# Assignment 4 — Social language and human handoffs

**INFO 7375 · Irreducibly Human · Fall 2026 · 100 points · Due: Canvas**

[AI Policy for Professor Bear's Courses | Using AI Responsibly in Class](https://youtu.be/8Ut0Cdl6vMw?si=9w3aEpt1ZyAR4Kiz)

**Predict → Build It → Use It → Ship It → Verify**

Bundle [Lesson 5](../../lessons/05-social-language/README.md) and [Lesson 6](../../lessons/06-relationships-and-boundaries/README.md) into one submission. Lesson Assessments are ungraded practice.

## Predict

Will a warm response also respect the facts and boundaries of a fictional interaction? Predict a concrete failure. At which point should an assistant stop drafting and hand a decision to a person? Name the missing authority or context. Preserve the original before receiving output or critique.

## Build It

Build a Python response-review ledger for factual support, promises, uncertainty, tone observations, and escalation boundaries. Automated flags are review suggestions, not a measure of empathy.

Build a Python handoff state machine for a fictional service workflow: draft, review-needed, approved, or unresolved. Require an evidence reference and a designated human owner before marking a simulated approval.

## Use It

Ask Claude to draft a response to a fictional scheduling misunderstanding. Compare a polished but unsupported promise with a more limited accurate response. Do not use private conversations or clinical crises.

Ask Claude to challenge the handoff conditions. Have a classmate review a harmless fictional case if available; otherwise label the review as simulated and leave actual peer review status honest.

## Ship It

Submit fictional case, responses, review ledger, and annotated revision; handoff code, state trace, review conditions, and responsibility note. Include the Python implementation, tests, inputs, evidence, README, PREDICTIONS.md, CONTRIBUTIONS.md, FRICTIONAL.md, and VERIFICATION.md. Identify source material and real assistance. The final version goes to the designated GitHub location and Canvas.

## Verify

Test invented commitments, unsupported certainty, and valid bounded language. Do not treat a favorable rating as evidence that a model feels empathy.

Test absent approval, wrong case ID, and changed content after approval. A classroom record is not real customer consent. Never fabricate a person's reaction.

Check the shipped candidate, record actual outcomes, and explain the bounded conclusion. Do not fabricate human participants, permissions, findings, or understanding. If a learning exercise uses a simulation, label it throughout.

## Division of labor

**AI should** draft alternative wording and flag unsupported claims; prepare the handoff packet and identify missing information.

**Human should** decide what is appropriate in context and avoid attributing feelings or commitments without evidence; conduct any real interaction, secure actual permission when needed, and own commitments.

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

