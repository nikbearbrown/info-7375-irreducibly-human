# Lesson 3 — Keep the knowledge needed to check

**Predict → Build It → Use It → Ship It → Verify**

Reading: [01 tier 1 pattern and association.md](../../chapters/01-tier-1-pattern-and-association.md) — “The baseline-knowledge condition: you cannot audit what you do not know.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Which part of a small calculation can you explain unaided before and after AI assistance? Predict your transfer performance. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Implement a Python worked-example checker for a chosen arithmetic or text-processing mechanism. Solve one example yourself, then create a new transfer case with an independently calculated expected result. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/03-offloading-and-learning/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Use Claude to explain a confusing step and help revise your implementation. Attempt the transfer case before asking for its solution. Keep first attempts and assistance in the record. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver first attempt, assisted revision, transfer case, and learning note. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Compare your transfer explanation with actual execution. A single exercise is not proof of long-term skill gain or loss. Do not invent struggle if the work was straightforward. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. What distinguishes useful offloading from skipping the mechanism entirely?

<details>
<summary>Check your answer after responding</summary>

Retaining enough understanding to explain and check the result.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Irreducibly Human

**AI should** explain syntax, give hints, and check calculations after the attempt.

**Human should** attempt the mechanism, explain the transfer case, and report actual learning.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.

