# Lesson 11 — Compare many judgments with one repeated judgment

**Predict → Build It → Use It → Ship It → Verify**

Reading: [06 tier 6 collective and distributed.md](../../chapters/06-tier-6-collective-and-distributed.md) — “What makes a group smart — and the friction the machine throws away.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Will majority voting help when votes share the same error? Predict results for independent versus duplicated votes. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Implement a seeded Python simulation of odd-sized majority votes with per-voter correctness above one half. Compare independent Bernoulli votes with a shared vote copied to all members. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/11-independence-and-aggregation/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to explain the simulation assumptions and identify conditions under which the apparent crowd advantage disappears. Model-generated personas count as simulated agents, not independent human participants. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver simulation, seed/configuration, accuracy estimates, and dependence note. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

For three independent voters at p=0.7, compute 3p^2(1-p)+p^3=0.784. Perfectly duplicated votes retain accuracy 0.7. Compare estimates with exact values using a stated tolerance. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Why does the independence assumption matter?

<details>
<summary>Check your answer after responding</summary>

Duplicating a shared error adds votes without adding information.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Irreducibly Human

**AI should** simulate and compute aggregation results.

**Human should** specify dependence assumptions and judge relevance to the actual team.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.

