---
name: 008-starryear-clean-absurd-stage
description: Transform one user-supplied photograph into a clean vertical 2×2 quartet with untouched evidence and three sparse, source-derived absurd stages, each using large negative space and one step of a shared scale or carrying paradox. Use for 干净荒诞四格、大片留白超现实、巨物微缩四拼, or Starryear-Clean-Absurd-Stage. Do not use for dense fantasy scenes, ordinary collages, four filters, maximalist imagery, horror, or full-frame stylization.
metadata:
  author: "Starryear年"
  version: "0.2.0-test-candidate"
  license: "Starryear Personal and Non-commercial Use License"
---

# Starryear-Clean-Absurd-Stage

Create one vertical 2:3 true 2×2 quartet from exactly one authorized photograph: `Evidence → Scale Slip → Carrier Reversal → Impossible Closure`. Panel 1 keeps actual source pixels. Panels 2–4 isolate the photograph's decisive subjects inside broad quiet fields and unfold one shared absurd sentence through three distinct consequences. The result feels strange because the relations are impossible, not because the cells are crowded.

## Workflow

1. Inspect the source once. Lock the primary subjects, meaningful count, identity cues, gesture, one support/contact relation, palette, light, and the quietest usable background color.
2. Read the Chinese full prompt by default or the English prompt when requested. Internally choose one `ABSURD SENTENCE` containing only source-derived nouns and one impossible verb.
3. Keep Panel 1 as the real photograph with proportional crop, scale, or source-colored padding only; never redraw, retouch, recolor, extend, or replace it.
4. Generate Panels 2–4 separately as equal vertical 2:3 cells. Each cell must contain 45–70% perceptual negative space, one flat or subtly textured source-colored field, one low ground/contact cue, and no scenic clutter.
5. Use one shared `ABSURD SENTENCE`: Panel 2 creates a restrained scale slip; Panel 3 reverses who or what carries whom; Panel 4 closes the relation into one impossible causal loop. Do not introduce a new symbol or subplot in later panels.
6. Use at most three actor groups per generated cell. Make every impossible relation credible through contact, weight, occlusion, perspective, cast shadow, and stable anatomy. Default to matte puppet-theatre or restrained practical-set realism.
7. Assemble the four cells deterministically into a clean 2×2 master with a 2–6 px source-colored divider. Review once; regenerate only a failed generated panel once.

## Fixed output

- One RGB/sRGB PNG, vertical 2:3, preferably 2048×3072 or larger.
- Four equal vertical 2:3 cells: Evidence top-left, Scale Slip top-right, Carrier Reversal bottom-left, Impossible Closure bottom-right.
- One shared absurd sentence, one focal relation per generated cell, at most three actor groups per cell, and no decorative subplot.
- Default to no typography, title, caption, logo, signature, watermark, UI, or pseudo-text.

## Guardrails

- Generated forms must trace to visible source subjects, clothing, objects, architecture, plants, or surfaces; invent relations, not unrelated symbols.
- Protect faces, species, meaningful counts, gestures, signature clothing, and object identity when they carry recognition.
- Keep every generated background quiet: no extra buildings, crowds, foliage, furniture, clouds, props, portals, celestial objects, ornamental collage, or dense atmosphere unless essential to the shared paradox.
- Prefer deadpan strangeness over spectacle. No gore, injury, exposed anatomy, distorted faces, extra limbs, melting bodies, or horror effects.
- Reject busy cells, sticker cutouts, floating fragments without contact, generic beige presets, dirty parchment, heavy grain, splatter, plastic gloss, dramatic glow, or deep cinematic scenery.

## Full prompts

- Chinese: [references/008-starryear-clean-absurd-stage-prompt.zh-CN.md](references/008-starryear-clean-absurd-stage-prompt.zh-CN.md)
- English: [references/008-starryear-clean-absurd-stage-prompt.en.md](references/008-starryear-clean-absurd-stage-prompt.en.md)

Keep [assets/examples](assets/examples) empty during drafting and testing. After Starryear年 explicitly accepts the tested Skill, add only final images supplied or approved by the user. Example images never authorize reuse of their subjects, palette, or composition.
