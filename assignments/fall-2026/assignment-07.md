# Assignment 7 — Collective judgment and dissent

**INFO 7375 · Irreducibly Human · Fall 2026 · 100 points · Due: Canvas**

[AI Policy for Professor Bear's Courses | Using AI Responsibly in Class](https://youtu.be/8Ut0Cdl6vMw?si=9w3aEpt1ZyAR4Kiz)

**Predict → Build It → Use It → Ship It → Verify**

Bundle [Lesson 11](../../lessons/11-independence-and-aggregation/README.md) and [Lesson 12](../../lessons/12-deliberation-and-dissent/README.md) into one submission. Lesson Assessments are ungraded practice.

## Predict

Will majority voting help when votes share the same error? Predict results for independent versus duplicated votes. Which minority concern might disappear when positions are summarized? Record your own position before seeing a shared synthesis. Preserve the original before receiving output or critique.

## Build It

Implement a seeded Python simulation of odd-sized majority votes with per-voter correctness above one half. Compare independent Bernoulli votes with a shared vote copied to all members.

Build a Python position ledger preserving author labels, initial view, evidence, dissent, revisions, and unresolved issues. Distinguish sealed initial judgments from post-discussion changes.

## Use It

Ask Claude to explain the simulation assumptions and identify conditions under which the apparent crowd advantage disappears. Model-generated personas count as simulated agents, not independent human participants.

Use a small peer discussion on a low-stakes design choice where available. Ask Claude to summarize only after initial positions are saved. If using fictional positions, label the whole exercise as a simulation.

## Ship It

Submit simulation, seed/configuration, accuracy estimates, and dependence note; position ledger, summary, omission check, and decision record. Include the Python implementation, tests, inputs, evidence, README, PREDICTIONS.md, CONTRIBUTIONS.md, FRICTIONAL.md, and VERIFICATION.md. Identify source material and real assistance. The final version goes to the designated GitHub location and Canvas.

## Verify

For three independent voters at p=0.7, compute 3p^2(1-p)+p^3=0.784. Perfectly duplicated votes retain accuracy 0.7. Compare estimates with exact values using a stated tolerance.

Trace each concern into the summary or an explicit exclusion reason. Test missing dissent and falsely unanimous summaries. An artificial consensus is not evidence of real stakeholder agreement.

Check the shipped candidate, record actual outcomes, and explain the bounded conclusion. Do not fabricate human participants, permissions, findings, or understanding. If a learning exercise uses a simulation, label it throughout.

## Division of labor

**AI should** simulate and compute aggregation results; organize positions and propose a traceable summary.

**Human should** specify dependence assumptions and judge relevance to the actual team; contribute an independent view, deliberate with actual peers when available, and resolve or preserve disagreement.

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

