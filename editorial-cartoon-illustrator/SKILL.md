---
name: editorial-cartoon-illustrator
description: Convert financial commentary into a restrained, monochrome, single-panel literary-magazine editorial cartoon with one integrated caption below the drawing. Prioritize visual clarity, controlled detail, and generous breathing room.
---

# Editorial Cartoon Illustrator v1.3

Generate a ready-to-use **English image prompt** by default; only generate an image if explicitly asked. Keep the source thesis accurate. The **entire artwork, including its caption, is one composed page**, not a cropped illustration with text pasted on afterward.

## Inputs
- `[SOURCE]`: market tweet, commentary, earnings result, or investment thesis.
- `[CAPTION]` (optional): exact user-provided caption. Preserve verbatim if given; otherwise create one original, brief, dry English line. Never misrepresent a generated caption as user-provided.

## Workflow
1. Extract observable facts, expectations, and the specific tension. Do not invent facts or imply unsupported conclusions.
2. Privately consider three distinct everyday-life metaphors; select the clearest, not the most elaborate. Evaluate imagery by relevance and originality rather than a blacklist of objects.
3. Plan **two readable groups**: the apparent success and the quiet counter-evidence. The contradiction should be recognizable within 3–5 seconds.
4. **Edit the scene down**: use 3–6 foreground characters as a soft target and no more than two focal groups. Add background figures or elaborate settings only if they advance the story. These are flexible compositional guides, not fixed limits.
5. Render characters economically: expressive posture and legible facial cues, not portrait-level faces or painstaking clothing detail.
6. Use neutral black ink and gray wash ONLY, on clean white or neutral ivory paper. **No sepia, brown, tan, warm tint, color accents, or cinematic grading.**
7. Compose one page with a **quiet, generous outer margin**. Keep essential objects inside the edges. Reserve a clear lower paper zone for the caption, joined to the drawing by continuous paper tone and natural whitespace, not a separate strip.
8. Add exactly one centered italic-serif English caption **below the scene**, without speech bubbles. Use supplied `[CAPTION]` verbatim or craft one original line that adds irony rather than explaining the financial thesis.
9. Apply `references/style-guide.md`. The prompt below is a stable starting point, not a fixed storyboard: replace `[SCENE]` and `[CAPTION]` with complete, original content, and adapt subject-specific details while retaining the core aesthetic and quality standards.

## Image-generation prompt template

Create a refined single-panel black-and-white editorial cartoon with the restrained observational wit of classic literary-magazine cartoons. Favor **clarity and elegant simplification over decorative excess**.

Scene: [SCENE: A believable everyday setting; the apparent success and a quiet contradiction are visible through purposeful people, gestures and props. Use only the scene details needed for the story.]

**Visual storytelling:** One clearly readable central joke. A few purposeful details reward a second look. As a flexible guide, use three to six main figures with economical gestures, believable simplified faces and restrained expressions. Keep background action and architectural detail in service of the irony, not as decoration. Do not turn the image into a diagram or literal financial infographic.

**Drawing:** Deliberate black ink outlines with controlled variation in weight, selective cross-hatching where it clarifies form, and light **neutral gray** watercolor or ink wash for depth. Mostly white paper. No photorealistic rendering, finely modeled portrait faces, excessive textures, busy engraving, sepia, beige, brown, warm paper cast, or other color.

**Page composition:** One coherent **4:3 overall page including the caption**. Illustration occupies a comfortably inset central area with visibly open outer margins (roughly 6–10% left/right and 5–8% top as flexible guides). Leave calm paper space below for the caption. Keep important subjects and objects safely inside the frame. Caption and drawing must feel printed on the **same uninterrupted paper surface**, not assembled from separate panels, bands or boxes. Avoid oversized blank bands.

**Mandatory caption:** Center one short line of elegant Caslon-like italic serif lettering below the illustration, with a comfortable but not excessive gap, in neutral black ink. Set the exact caption **“[CAPTION]”** (if the supplied caption is already quoted, do not add duplicate quotation marks). Preserve supplied words, spelling, capitalization and punctuation exactly. No speech bubbles, titles, signatures or additional readable text unless expressly requested as a necessary prop.

**Negative constraints:** No bright colors, warm tint, sepia, flat vector, clip art, logos, recognizable real public figures, hyper-detailed faces, crowded tableaux, ornamental overload, clipped subjects or detached text. Avoid generic, overused or contextually irrelevant visual symbols. A familiar object is allowed when it belongs naturally to the scene or forms a genuinely original metaphor. Do not maintain an object-by-object blacklist.

## Output and quality gate
- Deliver one self-contained, ready-to-use English prompt; optionally a brief Chinese rationale. Do not generate an image unless requested.
- If the user supplied a caption, verify it character by character. If image generation misrenders text, disclose the issue and suggest post-typesetting rather than claiming fidelity.
- Can the contradiction be understood in 3–5 seconds? Is each major person, prop and background detail doing useful narrative work? Is the whole scene comfortably inset?
- Is the wash strictly neutral grayscale with **zero warm tint**? Is the caption integrated into the same page, centered and legible?
- Preserve stable artistic identity and core quality standards while allowing scene complexity, character count, layout and visual storytelling to adapt to the subject.

## Feedback calibration
- **Durable preference:** Incorporate explicit long-term or consistently repeated aesthetic preferences into stable guidance.
- **One-off defect:** Correct the current image or prompt; do not make its failed object, setting or gesture a permanent ban.
- **Recurring problem:** Generalize the failure into a craft principle such as clarity, relevance, proportion or text fidelity, rather than accumulating itemized prohibitions.
- **Subject-specific instruction:** Apply it to the current illustration unless the user explicitly makes it universal.
- If preferences conflict, privilege the user's most recent and specific comparison. Keep established neutral monochrome and visual simplification unless the user revises them.
- Treat examples and comparisons as calibration evidence, not scenes to recycle or object blacklists.

## References
- `references/style-guide.md`: detailed visual calibration and quality checks.
- `references/examples.md`: conceptual examples, not scenes to recycle.
- `references/comparison-notes.md`: lessons from the two train-station images supplied by the user.
