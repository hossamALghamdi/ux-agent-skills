---
name: ux-speed-decisions
description: Review or improve interaction responsiveness, target acquisition, and choice effort using the Doherty Threshold, Fitts' Law, and Hick's Law. Use for slow feedback, hard-to-reach controls, or difficult decisions in a UI flow.
---

# Speed & Decision-Making

Reduce avoidable waiting, movement effort, and choice effort in the user's task.

## Working approach

Trace the important interaction from intent through choosing, reaching a control, activating it, receiving feedback, and completing the operation. Identify the actual bottleneck before changing the interface. Use supplied measurements or collect evidence when tools permit; label estimates.

For reviews, recommend focused changes. For implementation requests, make the relevant changes and verify the affected interactions. Preserve required options, accuracy, and necessary decision context.

## Apply the three laws

- **Doherty Threshold:** Treat a response below roughly **400 ms** as a historical interaction guideline, not a universal boundary or guarantee of productivity. Give prompt, meaningful acknowledgment. If completion takes longer, show an honest pending state and preserve user control where appropriate. Distinguish time to feedback from time to actual completion. Do not claim a spinner makes the underlying operation faster or show success before it is known.
- **Fitts' Law:** Use the established model **T = a + b × log₂(1 + D/W)** to reason about target acquisition. **D** is movement distance; **W** is target width along the approach direction; **a** and **b** are empirically fitted constants. Bring frequently used controls closer to the likely starting position and enlarge usable hit areas where appropriate. Keep neighboring targets separable. Inspect pointer, touch, and keyboard operation as relevant; the pointing model does not describe every input method.
- **Hick's Law:** For equally likely alternatives, a common model is **T = a + b × log₂(n)**, where **n** is the number of alternatives and **a**, **b** are fitted constants. Reduce irrelevant alternatives, clarify labels, and organize choices around user intent. Use progressive disclosure when it reduces total effort. Do not hide essential choices or add navigation steps simply to reduce the number visible. Real decisions also depend on familiarity, probability, search, and complexity.

Without fitted constants and appropriate task conditions, use these equations directionally; do not invent millisecond savings or add model predictions into a fabricated total task time.

## Verify

Check the affected controls in representative layouts and input modes. Inspect hit areas, accidental neighboring activation, focus order, and feedback during delayed or failed operations. Where timing access exists, record the measured interval and conditions, and compare before and after consistently. For choice changes, consider total task steps, errors, and discoverability as well as visible option count. State what could not be measured.

## Report

State the bottleneck, evidence, applicable law, change, and verification. Separate measured performance from predicted benefit. Name unresolved tradeoffs, such as a shorter menu that adds an extra step, only when relevant to the proposed change.

## References

[Fitts' Law research](https://www.yorku.ca/mack/hci1992.html), [Hick–Hyman model application](https://www.yorku.ca/mack/hci3-2002.pdf), and [Doherty Threshold](https://lawsofux.com/doherty-threshold/).
