---
name: style-w-spark
description: Editing style W "spark" (ניצוץ) for 15s 9:16 promo videos — deep background, glowing accent, soft motion, decoded text, and a transition object (bouncing ball / spark) that links every scene. Use when the user asks for style W, "ניצוץ", a glowing tech/app promo, or object-morph transitions.
---

# סגנון W · ניצוץ

Deep background and glowing {accent}. Soft motion, with a transition object that links scenes. Load `adapt-editing-style` first and fill the roles.

## 1. Visual identity
- Background: deep {bg} with blurred light blobs, {glow} from below.
- Highlight: {accent} with {glow}. Text {ink}.
- Background shape: square with thick {radius}, blurred in a corner.

## 2. Motion graphics (fixed)
- **Decoded text:** grainy {ink} blocks resolve into letters in reading order; erase runs the reverse way.
- **Capsule / toggle:** off in {surface} → turns on in {accent} gradient with {glow} and sparks.
- **Ball:** rises, grows, squash & stretch, in {accent} or {accent-2}.
- **4-shape frame:** four overlapping shapes with {radius}, a spark traveling along the lines.
- **Particles:** fly in an arc and join into a word.
- **Card:** semi-transparent {surface}, with toggle, counter and progress bar; {accent} cursor that clicks.

## 3. Transition library
| Transition | Start → develop → end | Dur (s) | Sound | When |
|---|---|---|---|---|
| Ball that switches on | dot rises → squashes and drops → capsule lights, sparks fly | 0.7 | riser + thump | product reveal |
| Capsule → bubble → brackets → frame | compresses to bubble → opens to brackets → expands to 4 shapes | 0.6 | whoosh + riser | headline → number |
| Decode / erase | blocks → letters → erased reverse | 0.2–0.45 | typing | every text |
| Number → particles → word | strike line → number breaks and flies in arc → word pops | 1.0 | whoosh + thump | problem → solution |
| Blob → dot → window | light blob crosses → squashes to rising dot → opens to {radius} window | 1.3 | whoosh, riser, thump | into a brighter scene |
| Zoom through frames | zoom on detail → frames rush past accelerating (power 2.4) → 0.15 s freeze | 0.9 | riser + heavy thump | before ending |

## 4. Typography
- Keyword: heavy {font-display} in {accent} with {glow}. Rest of line {font-body} in {ink}.
- Numbers: {font-num} 150px. Popping word: each letter enters separately with back-ease and wobble.

## 5. Effects
- {glow}, sparks, glitch blocks, speed ramp, bright freeze, grain 6%.

## 6. Composition & camera
- Text centered; transition object (ball or spark) in top quarter. Camera: gentle drift ±4px, slight line tilt at the open.

## 7. Rhythm
- Soft and flowing: 1.5–2.5 s scenes, a transition object between every two scenes. Only one fast moment (the zoom).

## 8. Sound
- {sound-mood} soft ~100BPM. Typing on decode, thump on switch-on, whoosh on each transition, end tone (if allowed).

## 9. Design-system adaptation
- **Light brand:** {bg} = dark shade of brand color, or light {surface} with {glow} replaced by soft colored shadow. Grammar stays.
- **No-glow / flat brand:** {glow} = 0, replaced by 2px {accent} outline.
- **Dark {accent}:** ball and sparks in {accent-2} or white; lit capsule in {accent}.
- **No circles:** ball and dot become rounded squares with {radius}.

## 10. 15-second template
| Time | Scene | Skeleton |
|---|---|---|
| 0–2.45 | decoded line + capsule switches on | [הוק] |
| 2.45–3.05 | transition to frame | — |
| 3.05–5.2 | number in frame | [כאב במספר] |
| 5.2–7.6 | particles → solution word | [מילת פתרון] |
| 7.6–11.4 | window → card with toggle and counter | [מדד תוצאה] |
| 11.4–12.3 | zoom through frames | — |
| 12.3–15 | decoded {wordmark} + capsule | [כרטיס מותג] |
