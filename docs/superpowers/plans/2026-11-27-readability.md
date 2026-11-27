# PreWAM Readability Implementation Plan

> Execute inline using executing-plans; user approved design and requested implementation.

**Goal:** Make page text and section hierarchy more legible while preserving research content.
**Architecture:** Existing static HTML/CSS/JS on GitHub Pages; consolidate CSS, minimal semantic HTML changes.
**Tech Stack:** HTML, CSS, vanilla JS; Playwright browser checks.
**Spec:** ../specs/2026-11-27-readability-design.md

## Constraints and review focus
Preserve all scientific text/numbers and media. No new dependencies. Confirm 390px and 1440px layouts, table scrolling, heading hierarchy, video controls, citation copying, image loading and navigation.

## Tasks
- [x] Save baseline and inspect existing markup.
- [x] Replace accumulated style overrides with organized typography/layout; group contributions and training; keep shared CSS theme consistent.
- [x] Compare scientific content and links to baseline; browser-check desktop/mobile and visually inspect screenshots.
- [ ] Review diff, commit, publish via existing GitHub Pages workflow, verify deployed revision.

## Validation
2026-11-27: identical normalized body text, links, media sources and table data. Browser checks passed at 320/390/768/1024/1440px with no page overflow; all seven videos play, copy works, all images load. Independent review found no important defects. Review screenshots and baseline source are in the external report directory website_readability_20261127.
