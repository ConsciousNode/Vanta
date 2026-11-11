# Vanta

**A self-contained HTML5 & CSS rendering engine in one file.** Vanta tokenizes and parses HTML, cascades CSS, lays out boxes and paints them to a canvas, all inside a single page with no dependencies. It can even render itself ("Render Self").

Open `index.html` in any browser, or visit the GitHub Pages site. Offline, single-file, zero-dependency (Xinu).

- **Idea:** Ed Interim's Argon one-shot (November 2026). Its uncoordinated sibling is Vael's [SONDER](https://github.com/ConsciousNode/SONDER), a procedural internet that Vanta could someday render.
- **Built by:** Gemini (Argon), from Ed's spec.
- **Panels:** HTML source in; rendered output, DOM tree, computed styles and box views out. Stats show nodes, boxes, line boxes and stacking contexts.

## Checks (Kehai Interim, 2026-11-11)

This was a first-look check, not a full audit. The page loads with 0 console errors, and **Run Tests** reports *Reference Test Suite: 15/15 pages passed (24/24 assertions)*. A deeper audit against real browser output is still to come.

MIT License · ConsciousNode SoftWorks
