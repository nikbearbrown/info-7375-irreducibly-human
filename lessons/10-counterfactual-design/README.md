# Lesson 10 — Ask what would change under a different action

**Predict → Build It → Use It → Ship It → Verify**

Reading: [05 tier 5 causal and counterfactual.md](../../chapters/05-tier-5-causal-and-counterfactual.md) — “How the field teaches causation — and the error the teaching produces.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

What extra assumptions are needed to compare two actions for the same case? Name what your observed data cannot settle. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Extend the structural simulation to compare two interventions using the same exogenous input. Build an experiment-plan validator for outcome, treatment, comparison, assignment rule, confounders, and limits. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/10-counterfactual-design/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude for two possible study designs for a fictional process improvement. Compare assumptions and feasibility without recruiting participants or running a real intervention. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver counterfactual pairs, study plan, validator, and identifiability note. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Change the structural model and show that a different assumed mechanism can alter the counterfactual. Distinguish population effects from individual counterfactuals. No simulated study is real-world causal evidence. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Does a model's plausible counterfactual establish what would have happened?

<details>
<summary>Check your answer after responding</summary>

Only under a justified model and its assumptions; plausible prose alone cannot identify it.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Irreducibly Human

**AI should** enumerate model consequences and design alternatives.

**Human should** choose defensible assumptions and distinguish proposed studies from evidence.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.

