---
name: ux-complexity-effort
description: Review or simplify product workflows and implementation tradeoffs using Occam's Razor, Pareto, Parkinson, Postel, and Tesler. Use for unnecessary steps, misplaced complexity, rigid inputs, or prioritization of UX improvements.
---

# Complexity & Effort

Reduce unnecessary work while preserving the information, choices, and safeguards required to complete the task correctly.

## Working approach

Identify the user outcome, mandatory requirements, and current steps. Distinguish essential task complexity from complexity introduced by the interface or implementation. Look for repeated entry, avoidable decisions, ambiguous inputs, and manual work the system could reliably handle.

For a review, recommend scoped changes. For implementation, apply requested changes and verify relevant outcomes. Simplification does not by itself authorize removing requirements, changing business rules, or performing external actions.

## Apply the five laws

- **Occam's Razor:** Among solutions that satisfy the task's requirements, prefer the one with fewer unnecessary assumptions, states, or moving parts. Consider total effort across the flow; a clean screen that hides essential controls or creates extra steps may be more complex in use. Preserve necessary validation and explanation.
- **Pareto Principle:** Look for a small set of problems or tasks with disproportionate impact. Use available frequency, severity, support, or usage evidence to prioritize. **80/20 is a heuristic, not a guaranteed distribution.** Without data, label priorities as hypotheses. Consider rare but severe failures rather than ranking solely by frequency.
- **Parkinson's Law:** Recognize that work can expand toward the time allocated. When planning requested UX work, define the outcome and a concrete completion criterion; separate required work from optional refinements. Do not use this principle to invent shorter deadlines, rush users, remove necessary checks, or claim a task's real duration equals its allowance.
- **Postel's Law:** Accommodate understandable input variation and produce consistent output. Normalize harmless formatting when meaning is clear, such as surrounding whitespace. Explain accepted formats and preserve user input on error. When interpretation changes meaning, ask or provide an explicit choice; do not silently guess ambiguous dates, amounts, or identifiers. Tolerance does not require accepting invalid or unsafe input or discarding information.
- **Tesler's Law:** For a fixed task, some complexity must be handled somewhere. Shift repetitive, predictable work to the system when it can do so reliably; keep users informed and able to correct consequential interpretations. **C_user + C_system = C_inherent** is conceptual bookkeeping, not a measured conservation equation. First remove accidental complexity; then decide who should handle what remains.

## Verify

Walk through the outcome with representative normal, invalid, ambiguous, and recovery cases as relevant. Check that simplification preserves required choices and information. For input changes, inspect normalization and error behavior. Compare user steps and effort with any added system burden. Tie prioritization to actual evidence where available and mark unmeasured benefits as expected.

## Report

Explain the unnecessary effort, applicable law, proposed or completed change, and evidence of preserved correctness. State the completion criterion and any material tradeoff. Avoid arbitrary 80/20 claims, invented complexity scores, and recommendations to delete functionality merely to reduce visible controls.

## References

[Laws of UX](https://lawsofux.com/) summarizes the five principles; see also [Postel's Law](https://lawsofux.com/postels-law/) and [Tesler's Law](https://lawsofux.com/teslers-law/).
