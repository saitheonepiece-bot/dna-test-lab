# ⚡ QuizGen AI

Make a quiz on **any topic** with built-in AI — plus ready-made science quizzes for grades 6–9. No sign-up, no API keys, no cost. Runs as plain files on GitHub Pages.

## Run it

Open `index.html` in any web browser (double-click it, or drag it into a browser tab).

## What's inside

- **✨ AI quiz generator** — type any topic **or add a picture** (the AI scans the image — notes, a diagram, a scene — and quizzes you on it), pick 5–10 questions and Easy/Medium/Hard. Powered by [Puter.js](https://developer.puter.com/) so it's free for everyone with no API key.
- **⏱ Timed play** — questions appear one at a time with a 15-second countdown each, then a full score + review.
- **Ready-made science quizzes** — 🧬 Biology · ⚗️ Chemistry · 🔭 Physics, a separate test for each grade 6–9 (12 quizzes).
- **Take mode** — answer, submit, and get an instant score with a right/wrong review.
- **Build mode** — add, edit, or delete questions on any quiz (including AI-generated ones).
- Everything saves to the browser automatically.

## Files

- `index.html` — home page with the AI generator and the subject × grade picker
- `test.html` — the quiz engine (reads `?subject=…&grade=…` or `?custom=1` for AI quizzes)
- `.nojekyll` — tells GitHub Pages to serve files as-is

Live site: https://saitheonepiece-bot.github.io/dna-test-lab/
