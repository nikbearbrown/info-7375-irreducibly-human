# Lesson 7 — Check confidence against outcomes

**Predict → Build It → Use It → Ship It → Verify**

Reading: [04 tier 4 metacognitive and supervisory.md](../../chapters/04-tier-4-metacognitive-and-supervisory.md) — “How metacognition is taught — and the transfer that never happens.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Will your higher-confidence judgments be more accurate? Record probabilities for several low-stakes factual or numerical cases before checking. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Implement Brier score in Python as the mean of (p-y)^2, with finite probabilities in [0,1], binary labels, equal lengths, and nonempty input. Preserve individual cases and counts. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/07-confidence-and-calibration/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to suggest alternative explanations for your errors after checking the cases. Separate your confidence, Claude's verbal confidence, and synthetic teaching probabilities. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver confidence ledger, scorer, hand calculation, and calibration note. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Check p=[0.9,0.8,0.4,0.1], y=[1,0,1,0]: Brier=0.255. Test endpoints, NaN, invalid labels, and empty input. A few cases do not establish population calibration. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Can confident language be used directly as a validated probability?

<details>
<summary>Check your answer after responding</summary>

No. Its interpretation and calibration require evidence.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Computational Skepticism

[Companion reading](../../docs/reading-map.md#computational-skepticism): apply the toolkit's concrete falsifier to one claim in this artifact. Name the observation that could count against it and the evidence needed to check it.

## Irreducibly Human

**AI should** compute scores and propose error patterns.

**Human should** record original confidence, verify labels, and interpret uncertainty.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
