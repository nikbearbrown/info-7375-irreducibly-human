# Assignment 6 — Causal and counterfactual reasoning

**INFO 7375 · Irreducibly Human · Fall 2026 · 100 points · Due: Canvas**

[AI Policy for Professor Bear's Courses | Using AI Responsibly in Class](https://youtu.be/8Ut0Cdl6vMw?si=9w3aEpt1ZyAR4Kiz)

**Predict → Build It → Use It → Ship It → Verify**

Bundle [Lesson 9](../../lessons/09-causal-questions/README.md) and [Lesson 10](../../lessons/10-counterfactual-design/README.md) into one submission. Lesson Assessments are ungraded practice.

## Predict

Will a correlation in a synthetic dataset equal the effect of an intervention? Specify the causal assumption you are using. What extra assumptions are needed to compare two actions for the same case? Name what your observed data cannot settle. Preserve the original before receiving output or critique.

## Build It

Build a Python structural simulation with a common cause U affecting treatment X and outcome Y. Compare observational group means with an intervention that sets X while holding exogenous cases fixed.

Extend the structural simulation to compare two interventions using the same exogenous input. Build an experiment-plan validator for outcome, treatment, comparison, assignment rule, confounders, and limits.

## Use It

Ask Claude to explain the association and propose a causal claim. Compare the claim with the known synthetic generating equations. State that identification comes from assumed structure here.

Ask Claude for two possible study designs for a fictional process improvement. Compare assumptions and feasibility without recruiting participants or running a real intervention.

## Ship It

Submit simulation, equations, observational/interventional comparison, and assumptions; counterfactual pairs, study plan, validator, and identifiability note. Include the Python implementation, tests, inputs, evidence, README, PREDICTIONS.md, CONTRIBUTIONS.md, FRICTIONAL.md, and VERIFICATION.md. Identify source material and real assistance. The final version goes to the designated GitHub location and Canvas.

## Verify

Use U in {0,1}, X=U, Y=U: observational difference is 1 while do(X=1) versus do(X=0) changes Y by 0. Check the result by hand. Do not generalize this example to all causal questions.

Change the structural model and show that a different assumed mechanism can alter the counterfactual. Distinguish population effects from individual counterfactuals. No simulated study is real-world causal evidence.

Check the shipped candidate, record actual outcomes, and explain the bounded conclusion. Do not fabricate human participants, permissions, findings, or understanding. If a learning exercise uses a simulation, label it throughout.

## Division of labor

**AI should** implement the supplied equations and compare outputs; enumerate model consequences and design alternatives.

**Human should** state and defend the causal assumptions and scope; choose defensible assumptions and distinguish proposed studies from evidence.

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

