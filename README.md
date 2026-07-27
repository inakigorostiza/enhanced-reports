# MIDE — YoY Channel Performance

A 6-page **interactive infographic** analysing MIDE's year-over-year channel performance
(GA4, **28 Apr → 27 Jul · 2026 vs 2025**), built on the **LIN3S design system**.

**Powered by Coupler.io · Built with Claude Code.**

## What this is

A single, self-contained `index.html` — data, charts, images and narrative in one file,
with no external requests (fonts, imagery and SVG charts are all inlined). It is:

- **Web-based & interactive** — hover tooltips + crosshair on the charts, a live light/dark
  theme toggle, scroll-reveal motion, and section navigation.
- **On-brand** — Besley + Inter typography, monochrome editorial chrome, and charts drawn
  only from the LIN3S graphics palette (validated for contrast + colour-blind safety).
- **Story-first** — "The growth paradox": MIDE nearly doubled its audience (+92.8% users)
  while revenue slipped 5.9%, with Organic Search revenue down 74% on flat traffic.

## The pipeline

1. **Coupler.io** pipes MIDE's GA4 into the workflow (no manual exports).
2. **Claude Code** queries it live, applies the LIN3S design system, and hand-builds the
   6-page infographic.
3. A human framed the questions, set the brand, and verified every number.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The report — deploy this (fully self-contained). |
| `index.template.html` | Source template with `{{ASSET}}` placeholders (fonts/images injected at build). |
| `post.md` | Companion LinkedIn post. |

## Notes on the data

Figures come from a single GA4 property ("MIDE360 — MAIN"). Per-channel user counts are
summed across channel×day rows for a like-for-like comparison, so topline totals read
**directionally** rather than as de-duplicated uniques. The near-zero revenue on some paid
channels is flagged in-report as a **tracking/attribution question to investigate**, not a
settled conclusion.

---

*Powered by data. Driven by humans.*
