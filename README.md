# ⚡ Spark Science Lab

A single-file web app of **science quizzes for grades 6–9** — no server, no build step, no login.

## Run it

Open `index.html` in any web browser (double-click it, or drag it into a browser tab).

## What's inside

- **Three subjects:** 🧬 Biology · ⚗️ Chemistry · 🔭 Physics
- **A separate test for each grade, 6 through 9** — 12 ready-made quizzes in total
- **Take mode** — answer, submit, and get an instant score with a right/wrong review
- **Build mode** — add, edit, or delete your own questions for any test
- Switch subject and grade any time from inside the test
- Your changes save to the browser automatically (localStorage)

## Files

- `index.html` — home page with the subject × grade picker
- `test.html` — the quiz engine (reads `?subject=...&grade=...`)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

Live site: https://saitheonepiece-bot.github.io/dna-test-lab/
