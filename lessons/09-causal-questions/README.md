# Lesson 9 — Separate prediction from an intervention

**Predict → Build It → Use It → Ship It → Verify**

Reading: [05 tier 5 causal and counterfactual.md](../../chapters/05-tier-5-causal-and-counterfactual.md) — “Pearl's ladder, and the rung the machine lives on.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Will a correlation in a synthetic dataset equal the effect of an intervention? Specify the causal assumption you are using. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Build a Python structural simulation with a common cause U affecting treatment X and outcome Y. Compare observational group means with an intervention that sets X while holding exogenous cases fixed. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/09-causal-questions/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to explain the association and propose a causal claim. Compare the claim with the known synthetic generating equations. State that identification comes from assumed structure here. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver simulation, equations, observational/interventional comparison, and assumptions. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Use U in {0,1}, X=U, Y=U: observational difference is 1 while do(X=1) versus do(X=0) changes Y by 0. Check the result by hand. Do not generalize this example to all causal questions. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Why does observing X differ from setting X?

<details>
<summary>Check your answer after responding</summary>

Setting X breaks its generating relationship; observing it can retain confounding.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Computational Skepticism

[Companion reading](../../docs/reading-map.md#computational-skepticism): apply the toolkit's concrete falsifier to one claim in this artifact. Name the observation that could count against it and the evidence needed to check it.

## Irreducibly Human

**AI should** implement the supplied equations and compare outputs.

**Human should** state and defend the causal assumptions and scope.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
