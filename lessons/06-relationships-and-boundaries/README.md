# Lesson 6 — Design a handoff to a real person

**Predict → Build It → Use It → Ship It → Verify**

Reading: [03 tier 3 social and personal.md](../../chapters/03-tier-3-social-and-personal.md) — “How social intelligence is actually built — and how it is unbuilt.” Tools: Claude Code and Python standard library. Prerequisites: prior lessons and retained predictions/evidence. Suggested pacing: one class session plus practice; Canvas supplies dates.

## Predict

At which point should an assistant stop drafting and hand a decision to a person? Name the missing authority or context. Save an original expectation, confidence estimate, assumptions, and possible falsifier in PREDICTIONS.md before seeing the output. Add later observations without rewriting the original.

## Build It

Build a Python handoff state machine for a fictional service workflow: draft, review-needed, approved, or unresolved. Require an evidence reference and a designated human owner before marking a simulated approval. Make an initial attempt before requesting a complete solution. Work in learning-artifacts/06-relationships-and-boundaries/ with main.py, test_main.py, inputs, and outputs. Explain what the mechanism checks and what it cannot determine.

## Use It

Ask Claude to challenge the handoff conditions. Have a classmate review a harmless fictional case if available; otherwise label the review as simulated and leave actual peer review status honest. Record date, model identifier as displayed, relevant prompts, commands, and actual results. Label fixtures, simulated participants, and hypothetical decisions. Claude Code is assumed; direct API calls are optional and may require separate credits.

## Ship It

Deliver handoff code, state trace, review conditions, and responsibility note. Include a README with exact run/test commands and source credits, plus the [prediction, contribution, Frictional, and verification records](../../templates/README.md). Package a local candidate for inspection; the [Assignment map](../../assignments/fall-2026/README.md) specifies final delivery.

## Verify

Test absent approval, wrong case ID, and changed content after approval. A classroom record is not real customer consent. Never fabricate a person's reaction. Run checks on the packaged candidate. Record outcomes and remaining limits in VERIFICATION.md; revise and repeat Ship It → Verify when needed. Explain what changed in your understanding, without inventing difficulty or a required conclusion.

### Assessments — ungraded

1. Complete the five-stage artifact and its boundary checks.
2. Explain one calculation or mechanism independently of Claude's prose.
3. Why is a generated approval message insufficient?

<details>
<summary>Check your answer after responding</summary>

It does not establish that an authorized person reviewed and approved the specific action.

</details>

Practice Assessments are ungraded. The separate ten-day Assignment briefs use the 100-point rubric. Course readings are arguments to examine; agreement with a philosophical thesis is not a grading requirement.

## Conducting AI

[Companion reading](../../docs/reading-map.md#conducting-ai): Chapter 9 on handoffs. Identify what passes to the next person or tool, what it is trusted to mean, and the evidence that earns that trust. A generated message does not create permission.

## Irreducibly Human

**AI should** prepare the handoff packet and identify missing information.

**Human should** conduct any real interaction, secure actual permission when needed, and own commitments.

Record the actual split in CONTRIBUTIONS.md: what you did, what Claude contributed, what you accepted, changed, or rejected, and what still needs understanding or permission. A generated narrative does not establish human participation or consent.
