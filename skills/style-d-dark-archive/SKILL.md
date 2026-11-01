---
name: style-d-dark-archive
description: Editing style D "dark archive" (ארכיון כהה) for 15s 9:16 promo videos — classified documents under a moving light beam, typewriter text, stamps, slow mysterious pacing. Use when the user asks for style D, "ארכיון כהה", a classified-file / dossier / investigation look, or a slow mysterious promo.
---

# סגנון D · ארכיון כהה

Classified documents in a beam of light. Slow, mysterious pacing. Load `adapt-editing-style` first and fill the roles.

## 1. Visual identity
- Background: dark {bg} with subtle diagonal grid, warm moving light beam, heavy vignette.
- Documents: light {surface}, {ink} text, stamp in {negative} or {accent-2}.
- End screen: {surface} with scanlines.

## 2. Motion graphics (fixed)
- **Document lands:** rotateX −80° → 0 in 0.6 s, hinge at top of page.
- **Typing:** letter-by-letter with blinking cursor.
- **Color invert:** {ink} bar smears in {dir}; halfway the text flips to {surface}.
- **Stamp:** scale 2.6 → 1 in 0.15 s, with shake.
- **Converging letters:** scattered letters gather into a word, blur clears.

## 3. Transition library
| Transition | Start → develop → end | Dur (s) | Sound | When |
|---|---|---|---|---|
| Flying pages | pages fall in 3D → spin → document lands center | 2.0 | paper | opening |
| Document slide | previous doc slides aside rotating 18° → next lands | 0.45 | slide | between documents |
| Converging letters | cut to light screen → scattered letters → {wordmark} | 1.0 | tone | ending |

## 4. Typography
- Doc header: small bold {font-body}, divider line and file code.
- Body: {font-body} 34–40px. Keyword: {font-display} 80–220px in color invert.
- Numbers: {font-num}.

## 5. Effects
- Light beam rotating ±5° in screen blend, vignette, {texture} ~20%, shake only on stamp.

## 6. Composition & camera
- One document centered (~72% screen width). Handheld camera: ±6px sway, slow 4% push-in.

## 7. Rhythm
- Slow: a document every 2.5–3 s, one action per second.

## 8. Sound
- {sound-mood} dark ~76BPM. Typing, paper rustle, muffled landing, stamp, end tone.

## 9. Design-system adaptation
- **Light-only brand:** {bg} = medium-dark shade of brand color (not black); beam stays; docs {surface}.
- **No "stamp" color:** stamp in {accent}, frame with small {radius}.
- **Ending:** original {wordmark} revealed after letters converge; never break the logo itself — text letters converge and swap into it.

## 10. 15-second template
| Time | Document | Skeleton |
|---|---|---|
| 0–2 | flying pages | — |
| 2–4.4 | file: subject in color invert | [הוק] |
| 4.4–7.6 | report: lines + total | [רשימת כאבים] + [כאב במספר] |
| 7.6–10.6 | recommendation + stamp | [מילת פתרון] |
| 10.6–12.6 | forecast with number | [מדד תוצאה] |
| 12.6–15 | letters converge into {wordmark} | [כרטיס מותג] |
