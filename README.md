# CPKC Rules Trainer

Mobile-first practice-exam app for CPKC Conductor rules qualification (Alberta / Prairie Division).

**Live:** https://wilgnerch.github.io/cpkc-quiz/

## Other pages

- **Conductor Exam Drill** — https://wilgnerch.github.io/cpkc-quiz/exam-drill/ — 252 questions from the Part 2 Exam Review, Study Guide Quiz, Part 1 Review and the Part 2 Knowledge Checks (OCS, CTC, ABS, Interlocking), in the course-player layout.

## What it does

- **1,056 multiple-choice questions** built from the current CPKC rule set.
- **20 questions per test** (10 / 30 / 50 also available), randomised, with the answer order shuffled every time.
- **Instant feedback with the reference.** Every answer shows the document, rule/item number and effective date so you can go straight to the source.
- **Currency notes.** Where the new CROR or the Summary Bulletin changes older GOI / RBTE text, the question flags it — so you are never studying superseded information.
- **Topic filter** — Speeds, Securement, Air Brakes, Alberta Bulletin, Dangerous Goods, Currency & Precedence, and more.
- **Missed-question retry** and test history, stored locally in your browser.
- 70% to pass.

## Source documents and currency chain

| Document | Effective |
|---|---|
| CPKC Canadian Rail Operating Rules (CROR) | June 15, 2026 |
| CPKC CROR Transition Guide | June 15, 2026 |
| Alberta Summary Bulletin — Prairie Division | 0001 April 1, 2026 |
| CPKC General Operating Instructions, Sections 1–13 | current to April 1, 2026 (Section 11 → June 12, 2026) |
| CPKC T&E Safety Rule Book | April 2023 |

Precedence used throughout the bank:

**CROR (Jun 15, 2026) → Alberta Summary Bulletin (Apr 1, 2026) → GOI / T&E Safety Rule Book**

Under CROR Rule 83(c), operating bulletins of a previous date that are not included or referred to in the Summary Bulletin become void; Summary Bulletins take effect on the 1st of April and October. Every GOI section carries the note that it does not contain revisions issued after printing.

## Notes

- The source PDFs are **not** in this repository. They are confidential and are kept in the private repo `cpkc-quiz-source`.
- Study aid only. Always govern yourself by the current rule books, bulletins and time tables.

## Structure

```
index.html
css/styles.css
js/app.js
data/questions.json   1,056 questions
.nojekyll
```

No build step — plain HTML/CSS/JS served by GitHub Pages.
