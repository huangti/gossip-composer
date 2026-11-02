# Editorial Cartoon Illustrator v1.3

A reusable Skill for turning financial commentary, earnings developments, and investment theses into original, restrained, single-panel editorial cartoons with one integrated English caption.

The Skill produces a **complete English image-generation prompt** by default. It generates an image only when explicitly requested.

## What's new in v1.3

- **Principle-driven visual direction:** avoid generic or contextually irrelevant imagery without maintaining a blacklist of particular objects. Familiar objects are fine when they belong to the subject or carry an original metaphor.
- **Stable style, flexible storytelling:** preserve the established artistic identity while adapting scene construction, character count, background detail, and composition to the idea.
- **Feedback calibration:** distinguish enduring aesthetic preferences from one-off image defects, recurring quality problems, and topic-specific requests. Turn recurring problems into general craft principles instead of accumulating arbitrary bans.
- **Clearer quality checks:** prioritize an immediately readable visual contradiction, relevant details, and an original caption over decorative complexity.

## Preserved from v1.2

- Neutral black ink and gray wash on white or neutral ivory paper. **No sepia, warm tint, or color accents.**
- Visual simplification: strong hierarchy, economical character drawing, purposeful detail, and generous outer margins.
- A single 4:3 page including exactly one centered italic-serif English caption, visually integrated with the artwork.
- Accuracy to the source thesis, with no invented financial claims or implied certainty.

## Repository structure

```text
editorial-cartoon-illustrator/
  SKILL.md
  references/
    style-guide.md
    examples.md
    comparison-notes.md
README.md
```

`SKILL.md` is the main workflow and prompt template. `references/style-guide.md` is the visual quality guide. `examples.md` contains conceptual examples, and `comparison-notes.md` preserves the user's earlier image-comparison feedback.

## How to apply the v1.3 update

Replace these three files in `huangti/gossip-composer` with the files from the v1.3 update package:

1. `README.md` (repository root)
2. `editorial-cartoon-illustrator/SKILL.md`
3. `editorial-cartoon-illustrator/references/style-guide.md`

Leave `editorial-cartoon-illustrator/references/examples.md` and `editorial-cartoon-illustrator/references/comparison-notes.md` unchanged. The update package contains **only the three files that changed**, not a full copy of the repository.

## Version notes

- **v1.3:** Principle-driven creative direction and feedback calibration, preserving neutral monochrome and clean composition.
- **v1.2:** Simplified overcrowded scenes, enforced neutral grayscale, and integrated the caption into a single composed page; incorporated the user's comparative image feedback.
