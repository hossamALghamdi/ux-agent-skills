---
name: ux-visual-perception
description: Review or improve interface grouping and visual hierarchy using common region, Prägnanz, proximity, similarity, and uniform connectedness. Use for confusing layouts, unclear relationships, or inconsistent visual grouping.
---

# Visual Perception & Grouping

Make the relationships users perceive match the relationships the product intends.

## Working approach

Identify the user's task and which elements belong together before adjusting their appearance. Inspect the supplied screen, design, or implementation. If only a description is available, label conclusions as provisional; do not imply visual inspection.

For a review, identify specific mismatches and propose changes. For an implementation request, make the relevant changes within the existing design system. Preserve working patterns and avoid expanding a grouping fix into an unrelated redesign.

## Apply the five laws

- **Common Region:** Put genuinely related controls or content inside a shared boundary or background when spacing alone is insufficient. Avoid wrapping every element in a card; excessive boundaries obscure higher-level groups.
- **Prägnanz:** Prefer the simplest stable visual organization that preserves meaning. Remove competing alignments, unnecessary decoration, and redundant containers. Keep distinctions users need to understand the task.
- **Proximity:** Make spacing within a group visibly smaller than spacing between groups. Keep labels, help, and errors close to their controls. Check that wrapping and responsive reflow preserve those relationships.
- **Similarity:** Give elements with the same role consistent visual treatment. Distinguish different roles when shared styling would imply interchangeable behavior. Reinforce meaning with text, shape, or structure when color alone would be insufficient.
- **Uniform Connectedness:** Use lines, paths, or shared connectors to express an actual relationship, sequence, or dependency. A connector can override proximity or similarity; remove links that imply a relationship the product does not have. In interactive implementations, convey essential relationships beyond decorative graphics.

These are perceptual tendencies, not numerical formulas. When cues conflict, judge the combined result instead of assuming one law always wins.

## Verify

Inspect representative narrow and wide layouts and any affected error or expanded states. Check whether a first-time viewer can distinguish groups, associate labels with controls, and recognize repeated roles. When implementation access is available, compare the rendered result with the intended grouping and inspect relevant semantic relationships. Mark any inaccessible states as unverified.

## Report

For each material issue, state the location, misleading cue, likely user consequence, and proposed or completed change. Name the relevant law and explain why it applies. Report observed verification separately from expected benefits; do not invent user-testing results or compliance scores. If there is no material issue, say so.

## Reference

[Laws of UX](https://lawsofux.com/) provides the named principles. The rules above translate them into design decisions, not a validated scoring model.
