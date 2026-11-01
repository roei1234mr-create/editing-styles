---
name: adapt-editing-style
description: Adapts any of the five editing styles (J2, B, D, K, W) to a given design system or brand. Use when the user asks to apply an editing style to a brand, map a design system to a video style, "תתאים את הסגנון למותג", "לפי הדיזיין סיסטם", or before building any video with the style-* skills.
---

# פרוטוקול התאמה · סגנונות עריכה למערכת עיצוב

The five styles are brand-free. Every visual value is a role in braces, e.g. {accent}. Always load this skill together with the chosen style-* skill, fill the roles from the user's design system, then build.

## 1. Role table

| Role | Job | How to pick from the system |
|---|---|---|
| {bg} | main background | brand background color |
| {surface} | surface / card / paper | one step above bg |
| {ink} | main text | main text color |
| {ink-2} | secondary text | muted text |
| {accent} | the single strong color: highlight, marker, keyword | strongest brand color passing 4.5:1 vs {bg} or {surface} |
| {accent-2} | secondary highlight (very little) | second brand color |
| {negative} | strike, "no", wrong | error color; else {ink} |
| {positive} | right / success / rising metric | success color; else {accent} |
| {glow} | glow (only styles that use it) | {accent} at 40–60% opacity |
| {font-display} | headlines, keywords | heading font, heaviest weight |
| {font-body} | sub lines | body font, regular |
| {font-num} | numbers, counters | tabular-figure font; else {font-display} |
| {font-alt} | contrast font (script / condensed / serif) | brand second font; else rule 3.3 |
| {radius} | corner radius | system card radius |
| {texture} | background texture | brand texture; else grain 5–10% |
| {logo-mark} / {wordmark} | end card | original marks, never recolored |
| {sound-mood} | sound mood | by brand tone (energetic / calm / premium) |
| {dir} | writing direction | rtl or ltr |

## 2. Process

1. Collect from the system: colors, fonts, radii, logo, textures, "forbidden" rules (e.g. no logo recolor, no circles). If the user gave no system, ask for it.
2. Fill the role table using the "how to pick" column. Show the filled table to the user.
3. Apply the general rules (section 3) and the style's own adaptation rules.
4. Fill the skeleton script (section 4) with the brand's content.
5. Build following the style's "15-second template".
6. Check against the pre-export checklist (section 5).

## 3. General adaptation rules

1. **Contrast:** {accent} must be 4.5:1 vs the surface it sits on. If not, swap {accent}/{accent-2}; if still failing, use {accent} as background with {ink} text on it.
2. **Dark-only / light-only brand:** every style defines a dark and light variant; pick the one matching {bg}.
3. **Single font only:** {font-alt} = {font-display} heaviest weight, horizontal squeeze 75–80%, negative tracking.
4. **Shapes:** if the system forbids a shape (e.g. circles), translate it to a square with {radius}. If the system demands sharp corners, {radius} = 0 everywhere.
5. **Direction:** with {dir}=rtl markers, strikes, slides and writing move right→left; ltr the opposite. Logo, numbers and codes always ltr.
6. **Color = meaning:** if the system assigns meanings (right/wrong/hint), they beat aesthetic choice.
7. **Logo:** never distort, recolor or break the logo itself. Animate only its container (enter, scale, reveal).
8. **Sound:** no pop/ding sounds if the system or brand forbids them.

## 4. Skeleton script (shared)

| Scene | Role | Neutral example |
|---|---|---|
| [הוק] | question or claim that stops the scroll | "כמה זה עולה לכם?" |
| [כאב במספר] | one big number | "X בחודש" |
| [רשימת כאבים] | 3–4 short items that get struck out | "א. ב. ג. ד." |
| [מילת פתרון] | one word that flips direction | "במקום ___, ___" |
| [מדד תוצאה] | number / percent that proves it | "עד Y%" |
| [כרטיס מותג] | {wordmark} + one sentence | "[שם] · [מה זה]" |

## 5. Pre-export checklist

- Exactly 15.0 s, 9:16, 30fps.
- {accent} only on what matters, not every frame.
- Every text readable ≥0.9 s (except deliberate hook cuts).
- Style recognizable (motion and transitions match the guide) and brand recognizable (colors, font, logo).
- No color, font or shape that doesn't come from the system or these rules.
