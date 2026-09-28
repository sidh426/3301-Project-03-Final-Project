# Project Plan

## 1. Risk Analysis (TAME Framework)

Using the formula **Actual Risk = Impact x Probability** (each scored 1–5):

| Risk | Impact | Probability | Actual Risk | Classification | TAME Strategy |
|---|---|---|---|---|---|
| Losing work / files due to a Git mistake or crash | 4 | 2 | 8 | Moderate | **Mitigate** — commit frequently in small increments, push to GitHub often instead of working locally for long stretches |
| Not having enough time due to internship + coursework load | 5 | 3 | 15 | High | **Mitigate** — build in dedicated weekly time blocks early rather than relying on the weekend before deadlines |
| Site looks broken or inconsistent across pages (CSS not applying uniformly) | 3 | 2 | 6 | Low-Moderate | **Mitigate** — test both pages in the browser after every meaningful CSS change, not just at the end |
| GitHub Pages fails to deploy correctly | 4 | 2 | 8 | Moderate | **Mitigate** — deploy early with placeholder content to confirm the pipeline works, then iterate on real content |
| Scope creep (adding pages/features beyond the two-page requirement) | 2 | 2 | 4 | Low | **Accept** — low likelihood given the scope statement is already specific, but will revisit the scope doc if tempted to add features |

## 2. Work Breakdown Structure (WBS)

| Task | Description | Estimated Time |
|---|---|---|
| 1. Finalize documentation | Revise scope.md based on peer feedback | 1 hour |
| 2. Draft site structure | Wireframe homepage and about page layout | 1 hour |
| 3. Build homepage HTML | Semantic markup for index.html | 1.5 hours |
| 4. Build about page HTML | Semantic markup for about.html | 1.5 hours |
| 5. Build stylesheet | Write style.css, apply to both pages | 2 hours |
| 6. Cross-page testing | Test navigation, responsiveness, and layout on desktop/mobile | 1 hour |
| 7. Deploy to GitHub Pages | Publish live site, confirm URL works | 0.5 hour |
| 8. Write plan.md | Document risk analysis and this WBS | 1 hour |
| 9. Write README.md | Repository homepage with links to live site and docs | 0.5 hour |
| 10. Write retrospective.md | Final reflection after project completion | 1 hour |
| 11. Final review | Check all acceptance criteria from scope.md before submission | 0.5 hour |

**Total estimated time:** ~11.5 hours

## 3. Sequencing Notes
Documentation (scope, plan) is finalized before development begins so the build stays anchored to a clear definition of done. HTML structure is built before CSS styling to avoid styling content that later changes shape. Deployment happens early with placeholder content to catch GitHub Pages issues before they can block a last-minute submission, consistent with the mitigation strategy for that risk above.
