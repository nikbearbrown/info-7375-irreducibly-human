# Assignment 5 — Calibration and checking the checker

**INFO 7375 · Irreducibly Human · Fall 2026 · 100 points · Due: Canvas**

[AI Policy for Professor Bear's Courses | Using AI Responsibly in Class](https://youtu.be/8Ut0Cdl6vMw?si=9w3aEpt1ZyAR4Kiz)

**Predict → Build It → Use It → Ship It → Verify**

Bundle [Lesson 7](../../lessons/07-confidence-and-calibration/README.md) and [Lesson 8](../../lessons/08-supervisory-checks/README.md) into one submission. Lesson Assessments are ungraded practice.

## Predict

Will your higher-confidence judgments be more accurate? Record probabilities for several low-stakes factual or numerical cases before checking. Which claim in a short source-based memo is most likely unsupported? Record the target before lookup. Preserve the original before receiving output or critique.

## Build It

Implement Brier score in Python as the mean of (p-y)^2, with finite probabilities in [0,1], binary labels, equal lengths, and nonempty input. Preserve individual cases and counts.

Build a Python claim-to-evidence checker that identifies missing or mismatched source IDs without automatically declaring the claim true. Preserve unresolved cases.

## Use It

Ask Claude to suggest alternative explanations for your errors after checking the cases. Separate your confidence, Claude's verbal confidence, and synthetic teaching probabilities.

Ask Claude to produce a memo from a small local source packet, then inspect its claims. Ask Claude for a critique only after your first pass and evaluate its findings too.

## Ship It

Submit confidence ledger, scorer, hand calculation, and calibration note; claim ledger, source packet, checker, and finding dispositions. Include the Python implementation, tests, inputs, evidence, README, PREDICTIONS.md, CONTRIBUTIONS.md, FRICTIONAL.md, and VERIFICATION.md. Identify source material and real assistance. The final version goes to the designated GitHub location and Canvas.

## Verify

Check p=[0.9,0.8,0.4,0.1], y=[1,0,1,0]: Brier=0.255. Test endpoints, NaN, invalid labels, and empty input. A few cases do not establish population calibration.

Plant one wrong citation and one correct unusual claim in a labeled fixture. Check both false acceptance and false rejection. Two model opinions can share the same error.

Check the shipped candidate, record actual outcomes, and explain the bounded conclusion. Do not fabricate human participants, permissions, findings, or understanding. If a learning exercise uses a simulation, label it throughout.

## Division of labor

**AI should** compute scores and propose error patterns; propose checks and organize citations.

**Human should** record original confidence, verify labels, and interpret uncertainty; choose the check, inspect support, and evaluate the evaluator.

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

