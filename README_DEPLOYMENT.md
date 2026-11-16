# JHS ALS A&E Reviewer LS 3 - Mathematics

## Deploy to GitHub Pages
1. Make a NEW repository such as `alskwela-ls3-mathematics-reviewer-jhs`.
2. Extract this ZIP and upload **all six files** at the root of the repository (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `.nojekyll`). Do not upload the ZIP itself.
3. Settings → Pages → Deploy from a branch → main → /(root).
4. In ALSKwela (Glide), add a card or button using Open Link to the HTTPS GitHub Pages address.
5. On Android, open the link directly in Chrome while online. Check "Offline files saved successfully", install/add to Home Screen, then test in Airplane Mode.

## Identity
- Installed name: JHS ALS A&E Reviewer LS 3 - Mathematics
- Short Home Screen name: JHS A&E LS3 Math
- Independent scope, storage keys, service-worker cache; does not interfere with JHS LS1 or LS2.

## Review behavior
- 120 unique original draft MCQs, 36 curriculum competencies; 3 fixed sets of 40.
- Fixed sets: each 20 Number/Algebra + 10 Geometry + 10 Data/Probability; 12 Easy + 20 Moderate + 8 Challenging.
- Random 40: one of three items from every competency plus 4 enrichment questions, maintaining domain/difficulty coverage.
- Feedback is professional Taglish and includes worked computation.
- After completion, generate a downloadable local PDF or use Print/Save as PDF. **Print/Save as PDF preserves mathematical symbols more faithfully; the lightweight downloaded PDF converts math symbols to ASCII equivalents**.
- All responses saved on the learner device; teachers receive them only after learners export/send the PDF.

## Quality and limitations
- This is an independent practice bank, **not an official BEA examination or verified forecast of 2027 questions**.
- Provisional difficulty labels. Review each mathematical expression, option, calculation and context before actual learner rollout, then pilot and do item analysis.
- Questions assessing graphs have descriptive textual representations. For later versions, embed accessible static graphs where they add real assessment value.
- File URL / standalone HTML is a backup, not a PWA install; publish over HTTPS for service-worker caching.
- App updates: change version in `sw.js` and `index.html` together to refresh cached content.
