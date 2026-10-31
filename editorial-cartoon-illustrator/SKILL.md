---
name: editorial-cartoon-illustrator
description: Convert financial commentary into a restrained, monochrome, single-panel literary-magazine editorial cartoon with one integrated caption below the drawing. Prioritize visual clarity, controlled detail, and generous breathing room.
---

# Editorial Cartoon Illustrator v1.2

Generate a ready-to-use **English image prompt** by default; only generate an image if explicitly asked. The source thesis must remain accurate. The **entire artwork, including its caption, is one composed page**, not a cropped illustration with text pasted on afterward.

## Inputs
- `[SOURCE]`: market tweet, commentary, earnings result, or investment thesis.
- `[CAPTION]` (optional): exact user-provided caption. Preserve verbatim if given; otherwise create one original, brief, dry English line. Never misrepresent a generated caption as user-provided.

## Workflow
1. Extract observable facts, expectations, and the specific tension. Do not invent facts or imply unsupported conclusions.
2. Privately consider three distinct everyday-life metaphors; select the clearest, not the most elaborate.
3. Plan **two readable groups**: the visible celebration/success and the quiet counter-evidence. The viewer should identify the contradiction within 3–5 seconds.
4. **Edit the scene down**: use 3–6 foreground characters as a soft target, with no more than two focal groups; add background figures only if they materially advance the story. Remove decorative crowds, flag-wavers, unnecessary clocks, redundant luggage and ornate architecture. Do not force exact counts when the metaphor needs otherwise.
5. Render characters with economical linework: expressive posture and a few legible facial cues, not portrait-level faces, detailed skin, or painstaking clothing patterns.
6. Use neutral black ink and gray wash ONLY, on clean white or neutral ivory paper. **No sepia, brown, tan, warm tint, color accents, or cinematic grading.**
7. Compose a single page with a **quiet, generous outer margin** on every side. Keep all essential subjects well inside the edges; no train, crowd, architecture or smoke clipped against the canvas. Reserve a clear lower paper zone for the caption, connected to the drawing by shared paper tone and natural whitespace, not a separate strip or pasted text box.
8. Add exactly one centered italic-serif English caption **below the scene**. No speech bubble. Use supplied `[CAPTION]` verbatim or craft one original line that adds irony rather than explaining the financial thesis.
9. Apply `references/style-guide.md`; deliver the complete fixed prompt below with only `[SCENE]` and `[CAPTION]` changed for each post.

## Fixed image-generation prompt

Create a refined single-panel black-and-white editorial cartoon with the restrained observational wit of classic literary-magazine cartoons. Favor **clarity and elegant simplification over rich detail**.

Scene: [SCENE: A believable everyday setting; two visually distinct focal groups, one showing apparent success and one revealing the quiet contradiction. Choose only essential characters, gestures and props. A simple, coherent background gives context without competing for attention.]

**Visual storytelling:** One immediately readable central joke. A few specific props reward a second look. Prefer three to six main figures, economical gestures, simplified believable faces and clothing, and restrained expressions. Avoid crowded platforms, extra waving people, flag bearers, dense architectural ornament, repeated background action, and anything unrelated to the visual irony. Do not turn the image into a diagram or literal financial infographic.

**Drawing:** Deliberate black ink outlines with controlled variation in weight, selective cross-hatching only where it clarifies form, light **neutral gray** watercolor or ink wash for depth. Mostly white paper. No photorealistic rendering, no finely modeled portrait faces, no excessive textures, no busy engraving effect, no sepia, beige, brown, warm paper cast, or other color.

**Page composition:** One coherent **4:3 overall page including the caption**. Illustration occupies a comfortably inset central area; leave generous, visibly open outer margins (approximately 6–10% left/right and 5–8% top as flexible guides), with additional calm white space below for the caption. Keep locomotives, smoke, roofs, characters and props inside the visual safe area. Do not fill the canvas edge to edge. Caption and drawing must feel printed on the **same uninterrupted paper surface**, not assembled from separate images, panels, bands, or boxes. Do not add oversized blank bands above or below the artwork.

**Mandatory caption:** Center exactly one line of elegant Caslon-like italic serif lettering immediately below the illustration, with a comfortable but not excessive gap, in the same neutral black ink. Set the exact caption **“[CAPTION]”** (if already quoted, do not add a second pair of quotes). Preserve supplied words, spelling, capitalization and punctuation exactly. No speech bubbles, signs, titles, signatures, additional captions or other readable text unless expressly requested as a necessary prop.

**Negative constraints:** No bright colors, warm tint, sepia, flat vector, clip art, stock-chart clichés, logos, recognizable real public figures, hyper-detailed faces, crowded tableaux, ornamental overload, clipped subjects, or text detached from the illustration.

## Output and quality gate
- Output one ready-to-use English prompt; optionally a brief Chinese rationale. Do not generate an image unless requested.
- If user supplied caption, verify it character-by-character in the final prompt. If image generation misrenders text, disclose it and suggest post-typesetting rather than claiming fidelity.
- Does the contradiction read in 3–5 seconds? Can any person, prop, or architectural flourish be removed? Are figures simpler than the setting? Is the entire drawing comfortably inset?
- Is the wash neutral grayscale with **zero warm tint**? Does the caption belong to the same page? Is it centered, legible, and exactly one line when practical?
- Fixed style and composition rules remain constant. Only `[SCENE]` and `[CAPTION]` change across posts.

## References
- `references/style-guide.md`: detailed non-negotiable calibration rules.
- `references/examples.md`: conceptual examples, not scenes to recycle.
- `references/comparison-notes.md`: specific lessons from the two train-station images supplied by the user.
