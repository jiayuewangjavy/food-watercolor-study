---
name: food-watercolor-study
description: Transform a user-supplied food or drink photograph into a fresh, hand-painted watercolor study that isolates the edible subject, ignores incidental background, optionally arranges ingredient or cutaway details, and pairs it with a food-related philosophical English fortune. Use when users ask to stylize food photos as gentle watercolor illustrations, food diary art, recipe-card art, or an exploded food composition.
---

# Food Watercolor Study

## Overview

Create a quiet editorial watercolor illustration, not a photo filter or literal food-photo redraw. Preserve the recognizable prepared dish: its cooking state, main ingredients, and the basic serving relationship. Simplify repeated pieces, background, and incidental garnish, but never reduce a composed dish to an unrelated ingredient specimen.

## Workflow

1. Inspect the supplied image. Identify the prepared dish, its cooking state, its hero ingredient, and 1–2 essential pairings (for example, roasted squash with creamy dip; figs with cured ham and leaves; roasted cauliflower with onion and cream). Keep those relationships.
2. Choose a composition:
   - **Dish vignette (default for a composed plate):** keep a simplified pale bowl or plate with the cooked hero and essential pairing(s); reduce the portions and loose detail rather than removing the dish context.
   - **Food breakdown:** retain the simplified prepared dish plus 1–3 separate cut faces, ingredients, or process states only when they clarify it.
   - **Single study:** use only for a naturally standalone food or drink.
   Do not reproduce the exact food count, garnish arrangement, sauce pattern, or camera angle from the photo, but retain enough of the dish's structure that it is immediately recognizable.
3. Choose one layout from the layout system below. Vary it between outputs unless the user requests a placement.
4. Write one food-linked English fortune using the rules below. Do not reuse generic motivational copy.
5. Use image generation or image editing with the food photo as the reference. Do not retain the original background.
6. Check the result against the quality bar. Regenerate if the food is unrecognizable, the background competes, the texture looks digital, or too many objects remain.

## Layout System

Select one layout deliberately; never default to food in the lower-right with text in the upper-left.

- **Corner dialogue:** hero dish in either lower corner; fortune in the opposing upper area; one small ingredient bridges the diagonal.
- **Top shelf:** food spread loosely across the upper third; fortune low and offset; the lower page remains mostly open.
- **Bottom shelf:** low, centered dish with a small detail above; fortune sits beside—not directly over—the detail.
- **Side column:** a vertical run of two or three food studies on one side; fortune occupies the neighboring open column.
- **Floating constellation:** hero dish off-center with 1–3 small separated ingredients around it; fortune nests in the largest remaining calm area.
- **Centered pause:** a small centered or upper-centered dish, wide paper margins, and a discreet fortune near the lower edge.

Let the food's shape choose the layout: tall drinks suit side columns; round bowls suit bottom shelves or centered pauses; slices and ingredients suit floating constellations. Keep the fortune in a clear quiet area, but vary its alignment, vertical position, and line breaks. For a set of images, do not reuse the same layout twice in a row.

## Art Direction

- Use warm ivory, subtly fibrous watercolor paper with generous negative space.
- Paint with translucent layered washes, soft pigment blooms, slight uneven edges, occasional granulation, and restrained fine dark outlines only where they clarify form.
- Keep shapes simplified and slightly naive; use clear silhouettes and believable internal details such as seeds, rind, crumb, crema, layers, pulp, or ice.
- Work like a small visual poem: favor a pared-back but recognizable serving over a full plate reconstruction. Retain the dish's essential pairings; omit repeated pieces and decorative clutter.
- Use a fresh, low-saturation palette: warm paper `#F4F0E7`, mist blue `#A9BDD0`, washed cobalt `#4F84B8`, leaf green `#739B58`, citrus yellow `#E6C75A`, peach `#E8AD86`, soft terracotta `#B96A54`, cocoa `#775544`, and charcoal-brown `#3C3630`.
- Allocate one dominant food color, one cool accent, and one quiet neutral. Avoid glossy highlights, neon color, heavy black contouring, dense shadows, or a polished 3D-render look.

## Prompt Template

Adapt the bracketed fields; state the food identity before describing the style.

```text
Use the uploaded photo only as reference for [FOOD / DRINK]. Ignore and remove its background.
Create a hand-painted watercolor food study on warm ivory textured paper: [COMPOSITION].
Make [HERO SUBJECT] the focus while preserving its prepared-dish context: [1–2 ESSENTIAL PAIRINGS]
and a simplified pale [BOWL / PLATE] if present. Optionally include [1–3 SELECTED DETAILS]
only if they clarify the dish. Simplify repeated pieces and freely rearrange everything else,
but keep the cooking state, essential pairings, and broad serving relationship recognizable.
Do not recreate the exact food count, garnish layout, sauce pattern, or camera angle. Use translucent layered washes, subtle granulation, soft feathered edges,
and sparse brown ink-like definition. Palette: fresh muted [DOMINANT COLOR], mist blue,
leaf green, citrus yellow, peach, and warm neutrals. Airy editorial arrangement, generous
negative space, no original setting, no photorealism, no glossy 3D rendering, no clutter,
use the selected [LAYOUT] and reserve its largest quiet area for a short English fortune; no generated text, watermark, or logo.
```

## Food Fortune

Pair every composition with one original English line that feels like a gentle fortune-cookie note: concise, observant, slightly philosophical, and materially connected to the pictured food.

- Derive the thought from a real feature of the subject: ripening, seed, rind, sharing, warmth, melting, brewing, layers, fermentation, seasonality, patience, or transformation.
- Use 5–15 words, one sentence, present tense, and plain evocative English. Favor a calm insight over a joke, slogan, command, or pun.
- Do not make health, medical, moral, or factual claims. Do not use famous quotations or wording that closely resembles them.
- Generate the fortune before rendering. Return it in the response as `Fortune: “…”`.
- For a final image with reliable lettering, render the illustration text-free, then overlay the exact approved fortune afterward in a small typewriter-like or softly imperfect serif face, charcoal-brown, with ample breathing room. Never rely on an image model to spell the fortune correctly.

Examples: apple — “What ripens slowly remembers the sun.”; coffee — “Some answers arrive only after the water warms.”; kiwi — “Small seeds can make a bright beginning.”; bread — “Time gives warmth a place to rise.”

## Quality Bar

- The food is immediately recognizable and visually dominant.
- The image reads as a simplified visual interpretation, not an inventory or near-copy of the photo, while remaining identifiable as the original prepared dish.
- The source background is absent rather than merely blurred.
- A breakdown contains no more than three selected details and adds understanding instead of turning into a complete ingredient inventory; it does not replace the actual dish.
- Paper texture, translucent pigment, and imperfect wash edges are visible at normal viewing size.
- The layout is sparse, balanced, and uses the muted fresh palette.
- The layout is chosen from the layout system and does not mechanically repeat the lower-right-food / upper-left-text arrangement.
- The fortune is original, readable, 5–15 words, and clearly tied to the food rather than being a generic inspirational caption.
- Exclude illegible generated text, logos, UI fragments, frames, and accidental photorealistic debris.

## Example Direction

For a photo of a strawberry shortcake: make the plated slice the hero; surround it with a halved strawberry, a cream-and-sponge cross-section, and two loose crumbs. Keep the plate pale and translucent, the red as a softened strawberry wash, and leave most of the paper blank.
