# ELE3915 — 2025 Take-Home Exam Walkthroughs

Interactive companion reports for the ELE3915 (Excel Programming & Automation, BI Norwegian Business School) 2025 take-home exam. Self-contained HTML — open any file in a browser, no install, no network, everything renders offline.

## Contents

**Landing page**

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Orientation + navigation to all six reports, grouped by part. |

**Part 1 — Formulas & LAMBDAs (AIMODEL, MATH datasets)**

| File | Topic |
| --- | --- |
| [`part1_exercise1.html`](part1_exercise1.html) | Exercise 1: AIMODEL analysis with LAMBDA — FLOP per token, domain averages, rows-where-column-is-max, two-condition FILTER, dropdown-driven filtering. |
| [`part1_exercise2.html`](part1_exercise2.html) | Exercise 2: charts with log axes, `MAXFLOPS` / `TOTALFLOPS` per fiscal year, NVIDIA revenue comparison. |
| [`part1_exercise3.html`](part1_exercise3.html) | Exercise 3: `FINDBEST` LAMBDA over the MATH benchmark — `MAKEARRAY` helper, `ISOMITTED` defaults, score-vs-date scatter. |

**Part 2 — ExcelScript (BIKE dataset)**

| File | Topic |
| --- | --- |
| [`part2_task1.html`](part2_task1.html) | Task 1: dropdown setup, `userType` named range, new columns on the `BIKE` table. |
| [`part2_task2.html`](part2_task2.html) | Task 2: monthly averages two ways — pivot-table path and a LAMBDA formula path. |
| [`part2_task3.html`](part2_task3.html) | Task 3: dual-axis line chart driven by ExcelScript. |

## How to use

Open `index.html` in any modern browser. Click a card to open a report. Use the persistent top bar to jump between reports without going home first. Inside a report:

- **Table of contents** sits in a sticky sidebar; click any entry to jump, and the current section stays highlighted as you scroll.
- **Progress bar** at the top of the page, with a live percentage indicator in the corner.
- **Think-before prompts** (`Pause.`, `Predict.`, `Try it first.`) hide their walkthrough behind a button — click to reveal once you've taken a guess.
- **Glossary terms** — the first time a term appears in the body, it's a link that scrolls to its glossary entry and briefly highlights it.
- **Excel function names** in the glossary are dashed-underline links to the matching [ExcelJet](https://exceljet.net/) reference page; the `↗` arrow signals an external link.
- **Copy button** on every code block copies the exact formula or TypeScript snippet to your clipboard.

Every feature works offline. No tracking, no analytics, no remote fonts.

## Design system

Colour identity uses BI Norwegian Business School's brand blues — Strong Blue (`#002341`), Default Blue (`#093F82`), and Accent Blue (`#0A64FF`) from the [official BI brand book](https://design.bi.no/colour-2). The landing-page title flows in a horizontal gradient from Default Blue to Accent Blue. The persistent top navigation bar uses a horizontal gradient from Strong Blue to Default Blue; the table-of-contents sidebar uses the same colours running vertically.

Per-part accent colours signal which half of the exam you're reading:

| Context | Accent | Where it shows |
| --- | --- | --- |
| Part 1 reports | `#43c2c2` (brighter teal) | progress bar, TOC active state, section numbers, code-panel left edge, reveal glyph, glossary flash |
| Part 2 reports | `#5fcc8f` (light green) | same surfaces as Part 1, rendered in the Part 2 hue |

Each report's H1 title and page-subtitle render as a horizontal gradient from Default Blue to that part's accent colour, so the colour flow you see on the landing-page card carries straight over to the report you click into. The same gradient lands on the landing-page card titles themselves, providing visual continuity between hub and reports.

Fonts are DejaVu Sans for body and headers with DejaVu Sans Mono for code and numeric markers.

## For students

Each report is written for a bachelor student working through the exam on their own. They start with the exam wording in plain English, walk the canonical solution line by line, flag simpler partial-credit paths where they exist, and point back to the lecture sheet or worked exercise parallel where each pattern was originally taught. Every unfamiliar term is introduced inline the first time it appears, and a glossary at the end of each report captures the full vocabulary.

## Credits

Made by Vilijam Cekov (Teaching Assistant) for the course ELE3915 — Excel Programming & Automation for the students of Jonas Moss (Part I) and Adam Lee (Part II) at BI Norwegian Business School. Excel function references link to the excellent [ExcelJet](https://exceljet.net/) reference library.
