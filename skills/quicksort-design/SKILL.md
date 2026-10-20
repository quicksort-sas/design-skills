---
name: quicksort-design
description: "Quicksort brand and design system. Use whenever you make anything for Quicksort, the AI strategy and engineering firm (a page, slide, deck, social post, event cover, chart, document or UI): it gives the colours, typefaces, logo, the lime pivot rule, icons, isometric figures, motion and voice, plus the asset files to use."
---

# Quicksort design system

Quicksort is named after the sorting algorithm: sort everything in one pass around a single pivot. The design works the same way. Put everything in order with ink, paper and stone, then mark the one thing that matters in lime.

## Rules that always apply

1. **The decision comes first.** Find the one point the piece must make before designing.
2. **One pivot per view.** Lime (#CCFF00) marks a single element per screen, slide or post: a dot, a bar, a button. Never two.
3. **Everything else in order.** Ink (#141414), paper (#F3F0E8) and the stone greys carry the rest.
4. **Numbers in mono.** Every figure is set in Martian Mono. Words are in Host Grotesk.
5. **Precision over decoration.** No gradients, shadows, glows, emoji or stock imagery.

## Colour

- Grounds: paper `#F3F0E8` (default, pages) or ink `#141414` (case studies, films, stages). Cards on paper use `#FAF8F3`.
- Text: ink on paper, `#FAF8F3` on ink. Secondary text `#55504A` on paper, `#9A968F` on ink.
- Lines: `#E4E1DB` / `#B8B4AD` on paper, `#2A2A2A` / `#3A3A3A` on ink.
- Lime `#CCFF00`: the pivot only. On paper, give lime shapes a 1.5px ink edge so they stay visible. Never set text in lime on paper.
- Typical page proportion: paper 60, ink 35, lime 5.
- All values: `assets/tokens.json` and `assets/tokens.css`.

## Typography

- **Host Grotesk** (Google Fonts) for headlines and text. **Martian Mono** for labels, numbers and the wordmark.
- Weights 400 and 500 only. Never bold. Sentence case everywhere.
- Scale (desktop px, line height, tracking): display 92/0.98/−4.5%, H1 64/1.04/−3.5%, H2 56/1.06/−3%, H3 32/1.15/−2%, H4 26/1.2/−1%, lead 20/1.5, body 17/1.5.
- Labels: Martian Mono 13px, uppercase, +6% tracking, stone colour, often with a lime dot before them.

## Logo

- The mark: a circle with a wedge cut out and a dot set apart. The wordmark "Quicksort" in Martian Mono, set to the right of the mark.
- Files: `assets/logo/quicksort-mark-ink.svg` (for paper grounds) and `assets/logo/quicksort-mark-paper.svg` (for ink grounds; the dot is lime).
- Clear space equals the diameter of the dot on all sides. Full logo at least 20px high; the mark alone down to 16px.
- Use the files as they are: don't rotate, stretch, recolour or add effects.

## Icons

Fifteen pixel icons on a 16×16 grid, in one colour; three of them (agents, chip, compass) carry a small lime pixel group. Use at 20, 24 or 28px, next to a word. Files in `assets/icons/`: agents, bank, calendar, chip, code, compass, database, diagnose, factory, headphones, insurance, newspaper, server, shield, team.

## Figures

Isometric line figures that each explain one idea, with the lime part as the decision. Use on service and case-study pages. Do not use them on event covers or in place of data. Files in `assets/figures/`: in-place-lime, in-place, one-pass, partition, recurse, tape-lime, tape.

## Event covers

Use the ticket: a wide 2:1 ink card. Left: logo and partner on top, title at the bottom ending in lime. Right: a darker stub with the event number, the day in large Martian Mono, the month in lime, then time and place.

## Charts and data

Bars and counters in ink or stone, with only the key value in lime. Numbers in Martian Mono. Every figure carries a source and date in a small mono label.

## Motion

Elements arrive in order and the lime pivot lands last with a small bounce: lines stagger 28ms, pivot 0.7s `cubic-bezier(.34,1.56,.64,1)`, charts grow 1.2–1.4s `cubic-bezier(.2,.7,.2,1)`. Loops only for films and social posts, always muted. Always respect reduced motion.

## Voice

Written for executives who have read every AI pitch. Short sentences, real numbers, no jargon, sentence case. Say what happens next.

- Write: "Credit review went from 45 minutes to 12, on the bank’s own servers."
- Not: "We leverage cutting-edge GenAI to unlock transformational efficiencies."

## Before you finish, check

- Only one lime element in view?
- Every number in Martian Mono?
- Only weights 400 and 500, sentence case?
- Logo from the files, with clear space?
- No shadows, gradients, emoji or stock imagery?
