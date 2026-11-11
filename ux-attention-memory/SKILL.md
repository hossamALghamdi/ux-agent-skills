---
name: ux-attention-memory
description: Review or improve interfaces that overload memory, bury important information, overuse emphasis, or make interrupted tasks hard to resume. Apply Miller's Law, serial position, Von Restorff, and Zeigarnik effects.
---

# Attention & Memory

Help users recognize what matters, retain necessary information, and resume work without reconstructing context.

## Working approach

Identify the user's task, the information needed at each step, and what the interface currently requires users to remember. Inspect the relevant screen or flow. Distinguish observed recall demands from assumptions about user behavior.

For a review, recommend targeted changes. For a requested implementation, apply them within the existing design system and task flow. Do not create persistence or notification features merely because they might be useful.

## Apply the four laws

- **Miller's Law:** Reduce simultaneous recall demands by grouping information into meaningful chunks and keeping required context visible. Favor recognition through summaries, labels, and previously entered values. The historical approximation of **7 ± 2 chunks** concerns particular immediate-memory tasks; it is not a universal capacity or menu-size limit. Choose group sizes by meaning and task needs.
- **Serial Position Effect:** Consider placing information users must remember near the beginning or end of a sequence, while preserving sensible task order. First and last items can have a recall advantage, but presentation and delay affect it. Do not assume recall findings automatically predict clicks, conversions, or navigation success.
- **Von Restorff Effect:** Make a genuinely important item distinct relative to its surroundings. Reserve strong emphasis for a small set of meaningful priorities. When everything stands out, the intended contrast disappears. Use understandable labels and accessible cues; visual novelty alone does not establish importance or comprehension.
- **Zeigarnik Effect:** Treat unfinished-task recall as context-dependent, not a guaranteed motivation mechanism. Help users see what remains, preserve entered work where supported, and provide a clear resumption point. Do not manufacture incompleteness, fake progress, or attention traps to keep users engaged.

These effects do not supply universal numerical formulas or a combined UX score.

## Verify

Walk through the task and identify each place users must carry information across screens. Check whether important emphasis remains distinct and whether grouping has a meaningful label. For existing resumable workflows, inspect interruption, return, saved-data, and completion states; confirm progress reflects actual work. Use real data or user evidence when making claims about recall improvements. A walkthrough alone cannot prove a memory effect.

## Report

Describe the specific recall or attention demand, the applicable law, and the proposed or completed change. Include relevant state coverage and any unverified assumptions. Prioritize issues that cause lost work, missed requirements, or repeated information lookup over cosmetic emphasis changes. If the interface already supports the task well, avoid forced changes.

## References

[Miller's original paper](https://labs.la.utexas.edu/gilden/files/2016/04/MagicNumberSeven-Miller1956.pdf), [Serial Position Effect](https://lawsofux.com/serial-position-effect/), and [Zeigarnik Effect](https://lawsofux.com/zeigarnik-effect/). See [Laws of UX](https://lawsofux.com/) for Von Restorff's effect.
