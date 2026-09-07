# Lesson 2 — Measure when assistance helps

**Predict → Build It → Use It → Ship It → Verify**

Reading: [01 tier 1 pattern and association.md](../../chapters/01-tier-1-pattern-and-association.md) — “When human involvement turns net-negative.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Will human edits improve a baseline classifier on a frozen set of examples? State your expectation before seeing its errors. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Implement a small deterministic Python classifier and accuracy/confusion-count calculator. Define a held-out set and a documented override rule; preserve the pre-override predictions. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/02-pattern-baselines/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to propose improvements after the baseline is recorded. Compare baseline and revised results on frozen cases. Label a deterministic surrogate as a surrogate, not as Claude. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver baseline code, frozen cases, override record, and comparison. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Hand-check counts on four cases; test empty input and invalid labels. Report degradation as honestly as improvement. A small task does not establish general AI or human superiority. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Does adding a person always improve a system?

<details>
<summary>Check your answer after responding</summary>

No. Complementary evidence and actual measured effects matter.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Computational Skepticism

[Companion reading](../../docs/reading-map.md#computational-skepticism): apply the toolkit's concrete falsifier to one claim in this artifact. Name the observation that could count against it and the evidence needed to check it.

## Irreducibly Human

**AI should** suggest candidate rules and calculate comparisons.

**Human should** choose the test, justify each override, and interpret the bounded result.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
