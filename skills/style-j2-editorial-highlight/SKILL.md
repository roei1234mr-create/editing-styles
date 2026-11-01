---
name: style-j2-editorial-highlight
description: Editing style J2 "editorial highlight" (הדגשה עיתונאית) for 15s 9:16 promo videos — marker highlights, strike-throughs, newspaper-clipping cuts, font swapping. Use when the user asks for style J2, "הדגשה עיתונאית", a marker/highlighter editorial video, or a text-only typographic promo.
---

# סגנון J2 · הדגשה עיתונאית

Text, color and transitions only. One keyword highlighted with a marker per scene; everything else secondary. Load `adapt-editing-style` first and fill the roles.

## 1. Visual identity
- Background: {surface} with {texture} (original: crumpled paper).
- Only three colors on screen: {surface}, {accent} (marker), {ink}.
- One highlighted keyword per scene; the rest {ink-2} or blurred.

## 2. Motion graphics (fixed)
- **Marker:** {accent} bar stretches in {dir} behind a word, 0.25 s ease-out; text on it {ink}.
- **Strike:** 10px {negative} line stretches over the word 0.15 s after the marker ends.
- **Background clippings:** {font-body} lines in receding depth, blur 2/3/6/10px.
- **Counter:** count-up with ease-out, {font-num}.

## 3. Transition library
| Transition | Start → develop → end | Dur (s) | Sound | When |
|---|---|---|---|---|
| Marker fills screen | highlight bar on word → grows all directions → screen fully {accent} | 0.45 | whoosh | word → number |
| Surface wipe | {surface} bar enters from side → covers → new scene | 0.35 | whoosh | number → list |
| Opening mask | {ink} point at center → expands → {ink} screen | 0.35 | riser | before a turn |
| Rising surface | {surface} panel rises from bottom → covers | 0.35 | whoosh | back to light |
| Clipping cuts | clipping changes every 0.4 s with blur on first frame; keyword stays in place | 0.4 | tick | opening |

## 4. Typography
- {font-display} heavy for keyword, {font-body} for body, thin weight for sub lines.
- "Font swap" moment: the word changes font on every beat between {font-display}, {font-body}, {font-alt}; on the last beat colors invert ({accent} bg, {ink} text).

## 5. Effects
- 6px blur on first frame of every cut. Constant 3–5% push-in per scene. No glow, no shadows.

## 6. Composition & camera
- Keyword at optical center (47% of screen height). Slow zoom only; slight lateral drift on clipping cuts.

## 7. Rhythm
- Fast open (cut every 0.4 s), middle 2.5–3 s per scene, calm ending. One action per beat.

## 8. Sound
- {sound-mood} minimal ~100BPM. Tick on cuts, marker swipe on highlight, scribble on strike, whoosh on transition, end tone (if allowed).

## 9. Design-system adaptation
- **Dark brand:** {surface} = system dark surface, subtle {texture}; marker stays {accent}, text on it max contrast.
- **{accent} weak vs {surface}:** invert — keyword in {accent} on {ink} background.
- **No {font-alt}:** font-swap uses {font-display} weights (thin / regular / heavy / heavy condensed).

## 10. 15-second template
| Time | Scene | Skeleton |
|---|---|---|
| 0–3 | clippings + fixed highlighted word | [הוק] |
| 3–5.6 | {accent} screen + counter | [כאב במספר] |
| 5.6–8.4 | list highlighted and struck | [רשימת כאבים] |
| 8.4–11.2 | word swapping fonts | [מילת פתרון] |
| 11.2–13.4 | number revealed by marker | [מדד תוצאה] |
| 13.4–15 | {wordmark} + highlight bar | [כרטיס מותג] |
