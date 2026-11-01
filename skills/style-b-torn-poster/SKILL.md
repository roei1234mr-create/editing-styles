---
name: style-b-torn-poster
description: Editing style B "torn poster" (פוסטר קרוע) for 15s 9:16 promo videos — grunge collage on one long board, stop-motion at 12fps, torn paper, slammed labels, ink marks. Use when the user asks for style B, "פוסטר קרוע", a grunge/collage/stop-motion promo, or torn-paper transitions.
---

# סגנון B · פוסטר קרוע

Grunge collage on one long board, in stop-motion. Load `adapt-editing-style` first and fill the roles.

## 1. Visual identity
- Background: {surface} with {texture}, thin grid, and a blurred moving blinds shadow.
- Paper scraps in {ink} and {accent}, torn edge and shadow.
- Marking color (marker circle and star): {accent-2}.

## 2. Motion graphics (fixed)
- **Stop-motion:** all motion stepped at 12fps, ±1° rotation jitter every ⅓ s.
- **Thrown paper:** enters from side with rotation, 0.34 s.
- **Label slam:** scale 2.2 → 1 in 0.17 s, tilted ±3–4°.
- **Ink marks:** {negative} strikes, {accent-2} hand-drawn ring, popping star.

## 3. Transition library
| Transition | Start → develop → end | Dur (s) | Sound | When |
|---|---|---|---|---|
| Camera jump on board | everything on one long board → camera jumps 900px with ±2° rotation → hard stop | 0.35 | whoosh | between chapters |
| Paper scrap covers | torn {ink} paper rises diagonally → covers → exits top | 0.7 | tear | topic change |
| Side paper | {accent} or {ink} strip thrown from side → becomes background of next word | 0.3 | tear | peak moment |

## 4. Typography
- **Labels:** heavy {font-display} inside {ink} or {surface} box with torn edge.
- **Giant headline:** {font-display} in {accent}, 170–280px, offset print shadow in {surface} and {ink}.

## 5. Effects
- Strong {texture} (grain 20–25%), blinds shadow, 8px screen shake on hard landings.

## 6. Composition & camera
- Overlapping stacked layers; one object half outside frame. Camera: slow drift ±6px, 3% push-in at each stop.

## 7. Rhythm
- Short and aggressive: chapter every 2.5–2.8 s, landing every 0.4–0.5 s.

## 8. Sound
- {sound-mood} fast ~170BPM. Thump on every label, paper tear on paper, marker on marks.

## 9. Design-system adaptation
- **Dark brand:** dark {surface}, scraps in lighter {surface} and {accent}. Print shadow stays.
- **No rough edges / clean brand:** the tear becomes a straight diagonal cut; rest of grammar unchanged.
- **No circles:** marker ring becomes a marker rectangle with {radius}.

## 10. 15-second template
| Time | Board area | Skeleton |
|---|---|---|
| 0–2.6 | question | [הוק] |
| 2.6–5.2 | number on {ink} paper | [כאב במספר] |
| 5.2–8 | label list + strikes | [רשימת כאבים] |
| 8–10.4 | solution on {accent} paper | [מילת פתרון] |
| 10.4–12.8 | number ringed in marker + star | [מדד תוצאה] |
| 12.8–15 | {wordmark} on {surface} scrap | [כרטיס מותג] |
