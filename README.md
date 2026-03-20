# GSoC 2026 Proposal — Sugar Labs / Music Blocks

## About Me
- **Name:** Abhnish Kumar
- **Email:** abhnish.1289@gmail.com
- **GitHub:** https://github.com/abhnish
- **LinkedIn:** https://linkedin.com/in/abhnishkumar
- **Institution:** Maharaja Agrasen Institute of Technology, New Delhi
- **Time Zone:** IST (UTC +05:30)

---

## Project: Music Blocks Maintenance

**Mentors:** Walter Bender, Sumit Srivastava
**Length:** 350 hours

## Proposal
👉 [View Full Proposal (PDF)](./proposal.pdf)

---

## Summary

Music Blocks is an interactive web-based programming environment
used by students worldwide to learn computational thinking through
music. This project aims to systematically improve Music Blocks
across three pillars:

1. **Test Coverage** — Improve Jest branch coverage to 75%+ across
   all critical modules including turtle-singer.js, turtles.js,
   toolbar.js, and GraphicsBlocks.js
2. **Accessibility** — Complete WCAG 2.1 AA compliance including
   color contrast, focus traps, zoom support, and cross-browser
   screen reader testing
3. **Code Quality** — Fix ESLint violations, add JSDoc documentation,
   and create a contributor testing guide

---

## Pre-GSoC Contributions

### Testing (Issue #5945)

| PR | File | Before | After |
|---|---|---|---|
| #6065, #6275 | musicutils.js | ~45% | 78%+ |
| #6224 | NumberBlocks.js | 55.96% | 84.18% |
| #6278 | ActionBlocks.js | 56.62% | 92.05% |
| #6222 | DrumBlocks.js | 57.27% | 80%+ |
| #6217 | BooleanBlocks.js | 35.34% | 75%+ |
| #6220 | DictBlocks.js | 54.79% | 80%+ |
| #6218 | ExtrasBlocks.js | 57.95% | 80%+ |
| #6214 | OscilloscopeWidget | low | improved |
| #6307 | ProgramBlocks.js | 65.02% | 80%+ |
| #6280 | RhythmBlocks.js | low | improved |
| #6281 | LogoDependencies.js | 66.66% | 80%+ |
| #6008 | utils.js | low | improved |

### Accessibility (Issue #5948 — WCAG 2.1 AA)

| PR | Feature |
|---|---|
| #6187, #6309 | Aria-labels for toolbar icons |
| #6189, #6308 | High contrast mode toggle |
| #6196 | Skip link for canvas |
| #6195 | ARIA live regions |
| #6193 | Focus indicators |
| #6190 | Keyboard palette navigation |
| #6197 | Widget close buttons |
| #6198 | Aux toolbar accessibility |
| #6194 | Screen reader widget support |

### Code Quality

| PR | Description | Status |
|---|---|---|
| #5567 | Remove debug console statements from jseditor | Merged |
| #6008 | Fix utils.js test coverage | Close |

---

## GSoC Timeline (Summary)

| Phase | Period | Goals |
|---|---|---|
| Community Bonding | May 8 - June 1 | Setup, mentor discussions, codebase study |
| Phase 1 | June 2 - June 30 | toolbar.js, GraphicsBlocks.js, turtledefs.js, themebox.js |
| Phase 2 | July 1 - July 25 | turtle-painter.js, turtle-singer.js, turtles.js |
| Phase 3 | July 26 - Aug 18 | Accessibility completion, ESLint fixes |
| Phase 4 | Aug 19 - Sep 1 | Documentation, contributor guide, CI integration |

---

## Community Engagement

- Active contributor on **Sugar Labs Matrix** (@abhnish:matrix.org)
- Direct interactions with maintainers **sum2it**, **omsuneri**,
  **mahesh-09-12**, **lnuth0603**, and **Walter Bender**
- Delivered **video demo** of all accessibility features to sum2it:
  https://drive.google.com/file/d/1UHKiClCYWL5Z_gWsYKstio3lwWQGRZuO/view?usp=sharing
- Active participant in issue #5607 (Music Blocks test suite project)

---

## Feedback

I would really appreciate feedback from mentors on:
- Scope and prioritization of target files
- Timeline feasibility
- Alignment with Music Blocks Maintenance goals
- Any additional areas of focus for GSoC 2026
