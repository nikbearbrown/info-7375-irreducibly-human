# Lesson 14 — Exposure is a measurement claim

**Predict → Build It → Use It → Ship It → Verify**

Reading: [08 conclusion.md](../../chapters/08-conclusion.md) — “Deprioritization is not deletion — at full stakes.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Would a different ability-to-tier mapping change an occupational exposure ranking? Predict the sensitivity before calculation. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Build a Python toy weighted index keyed by element_id, using explicitly synthetic abilities, weights, and exposure values. Version two alternative illustrative mappings and report coverage and ranking sensitivity. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/14-exposure-and-evidence/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to audit the index's interpretation. Compare a task-exposure statement with an unsupported job-loss prediction. Use the local research handoff only as a provenance lesson; do not modify its pending rubric or claim official ratification. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver synthetic index, two illustrative mappings, coverage table, and interpretation limits. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Hand-check a two-element weighted mean. Test missing element IDs, zero total weight, and duplicate records. Keep missing values distinct from zero. Do not substitute this toy mapping for rubric-v2-frozen. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Does a high task-exposure score predict a particular job loss?

<details>
<summary>Check your answer after responding</summary>

No. Exposure, adoption, substitution, demand, and employment outcomes are different quantities.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Branding and AI

[Companion reading](../../docs/reading-map.md#branding-and-ai): Chapter 18 on inspectable portfolio evidence. Make the explanation of your index's limits point to its actual inputs and calculations. Video is optional.

## Irreducibly Human

**AI should** compute and compare clearly labeled hypothetical indices.

**Human should** justify the construct, inspect coverage, and avoid claiming unratified research findings.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
