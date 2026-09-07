# Lesson 8 — Evaluate the checker

**Predict → Build It → Use It → Ship It → Verify**

Reading: [04 tier 4 metacognitive and supervisory.md](../../chapters/04-tier-4-metacognitive-and-supervisory.md) — “Plausibility auditing: the named skill no curriculum teaches.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

Which claim in a short source-based memo is most likely unsupported? Record the target before lookup. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Build a Python claim-to-evidence checker that identifies missing or mismatched source IDs without automatically declaring the claim true. Preserve unresolved cases. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/08-supervisory-checks/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to produce a memo from a small local source packet, then inspect its claims. Ask Claude for a critique only after your first pass and evaluate its findings too. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver claim ledger, source packet, checker, and finding dispositions. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Plant one wrong citation and one correct unusual claim in a labeled fixture. Check both false acceptance and false rejection. Two model opinions can share the same error. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. What makes verification more than asking the author to reconsider?

<details>
<summary>Check your answer after responding</summary>

A check that brings relevant evidence or an independently derived test to the claim.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Anthropics

[Anthropic: Demystifying evals for AI agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents), checked 2026-09-06. Compare the reported result with the outcome evidence your checker inspects. Evaluate the grader too. Our teaching checker is an adaptation, not Anthropic's implementation.

## Irreducibly Human

**AI should** propose checks and organize citations.

**Human should** choose the check, inspect support, and evaluate the evaluator.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
