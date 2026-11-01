---
name: style-k-race
description: Editing style K "race" (מירוץ) for 15s 9:16 promo videos — fast manga look with halftone dots, speed lines, stacked condensed type, repeating "until today ___" structure with X strikes. Use when the user asks for style K, "מירוץ", a manga/anime/speed-lines promo, or a very fast energetic typographic video.
---

# סגנון K · מירוץ

Fast manga style with halftone, speed lines and a repeating structure. Load `adapt-editing-style` first and fill the roles.

## 1. Visual identity
- Colors: {accent} (main), light {accent} (30% tint), {surface}, {ink}.
- 12px halftone dots with diagonal gradient mask; speed lines from center.
- Background alternates per chapter between light {accent}, {accent}, {surface}.

## 2. Motion graphics (fixed)
- **Narrow lines:** built with top-to-bottom clip reveal, 0.15 s.
- **Contrast word:** {font-alt} revealed in {dir}, tilted −8°, skewed 12°.
- **Repeating structure:** fixed line + word swapping every 0.9 s + {negative} X that strikes it.
- **Word wall:** runs in background at 35% opacity.

## 3. Transition library
| Transition | Start → develop → end | Dur (s) | Sound | When |
|---|---|---|---|---|
| Stripe smear | 32 horizontal stripes smear in {dir} staggered → cover → leave | 0.36 | whoosh | between chapters |
| Word swap | X on word → short smear → new word and new background | 0.15 | brush | in the repeating structure |
| Expanding bar | tilted {accent} bar stretches from center → solution on it | 0.25 | thump | solution moment |

## 4. Typography
- Lines: heavy condensed {font-display} (scaleX 80%), negative tracking, line-height 0.92.
- Contrast word: {font-alt}, 130–230px.
- Giant numbers: {font-num} 220–330px, enter from scale 1.4.
- Brand: {wordmark}, revealed with closing letter-spacing.

## 5. Effects
- 10px screen shake on landings, flickering speed lines, 2% zoom breathing.

## 6. Composition & camera
- Centered vertical stack: small lines on top, giant word below.

## 7. Rhythm
- Very fast: an action every 0.3–0.5 s; the repeating structure 4 times mid-video.

## 8. Sound
- {sound-mood} energetic ~150BPM. Thump on every line, brush on every word, whoosh on smear.

## 9. Design-system adaptation
- **Dark {accent}:** its light tint made at 15–25% opacity on {surface}.
- **No {font-alt}:** contrast word in italic {font-display} (skew −12°), heavy and condensed.
- **Calm / premium brand:** same grammar, speed lines at 40% opacity and shakes at half strength.

## 10. 15-second template
| Time | Chapter | Skeleton |
|---|---|---|
| 0–1.7 | question with speed-line burst | [הוק] |
| 1.7–3.6 | number on {accent} | [כאב במספר] |
| 3.6–8.4 | repeating "עד היום ___" ×4 | [רשימת כאבים] |
| 8.4–10.6 | word wall + solution | [מילת פתרון] |
| 10.6–12.8 | giant number | [מדד תוצאה] |
| 12.8–15 | {wordmark} on {surface} | [כרטיס מותג] |
