# Global Enterprise Discovery — Cybersecurity Sales Engineer Simulation

An interactive, browser-based microlearning prototype that teaches new and developing **Sales Engineers** how to run technical discovery conversations with large, global enterprises — then lets them practice in a six-turn customer simulation and receive a competency-based scorecard.

Built as a single, self-contained `index.html` with vanilla HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies, no external assets.

> **Live demo:** _add your GitHub Pages URL here_ (e.g. `https://your-username.github.io/global-enterprise-discovery/`)

---

## About this project

This is a featured piece in a **Technical Instructional Designer** portfolio. It demonstrates end-to-end applied enablement design for customer-facing technical roles: a performance problem sourced from SME input, a teachable framework, guided practice, an authentic simulation, and evidence-based feedback.

The course player is an **original, Rise-inspired scrolling lesson** — cover, scroll-progress bar, stacked content blocks, and continue-gated reveals. It intentionally evokes a modern web-based learning experience without copying any proprietary authoring-tool chrome, fonts, or components; every interaction is hand-coded to show the underlying craft.

## What it covers

The lesson runs in six parts (about 10–15 minutes):

1. **Orientation** — the performance problem and the learning objective.
2. **The Sales Engineer's role** — what the SE owns vs. does not, with a knowledge check.
3. **The SCOPE framework** — a five-move discovery method (Spark, Context, Operating workflow, Pain and priority, Evidence and evaluation) with a matching activity.
4. **Plan your discovery** — a guided planner for a fictional account (hypotheses, priority questions, stakeholders, next action).
5. **The customer meeting** — an embedded six-turn roleplay against five customer personas, with progressive fact reveals and a live SCOPE coverage panel.
6. **Performance & next steps** — a seven-competency scorecard (out of 28), evidence-based feedback, a targeted retry, and completion.

## Key features

- **Applied simulation** — six-turn discovery conversation driven by local keyword/intent matching (no live AI, no network calls).
- **Adaptive feedback** — the customer reveals different facts based on what the learner actually asks; premature product pitches trigger coaching that redirects to discovery.
- **Competency scoring** — scope management, stakeholder awareness, workflow discovery, technical credibility, risk prioritization, solution restraint, and next-step alignment.
- **Guided practice** — knowledge check, SCOPE matching, and a discovery planner, each with inline feedback and retry.
- **Copy & restart** — learners can copy their scorecard and restart the lesson.

## Accessibility

- Semantic HTML landmarks and headings, with focus moved to each new section on reveal.
- Keyboard-operable throughout; visible focus states; a focus-trapped, Escape-dismissible contents menu.
- `aria-live` regions for dialogue, hints, and feedback.
- Respects `prefers-reduced-motion`.

## Run it locally

No server or build required. Either:

- Double-click `index.html` to open it in any modern browser, **or**
- Serve the folder (optional), for example:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push `index.html` (and this `README.md`) to a GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose your branch (e.g. `main`) and the `/root` folder, then **Save**.
5. Wait for the deploy to finish, then open the published URL.

Because the app is a single static file, it works on GitHub Pages as-is.

## Tech stack

- Vanilla HTML5, CSS3, and JavaScript (ES5-compatible, single file)
- System font stack only; no web fonts
- No frameworks, libraries, APIs, analytics, or build tooling

## Project structure

```
.
├── index.html   # the entire course player and lesson
└── README.md    # this file
```

## Instructional design notes

**Performance problem (SME-informed).** Developing Sales Engineers struggle with enterprise discovery because of stakeholder complexity, regional differences, hybrid environments, governance requirements, and competing priorities — and under pressure they tend to pitch a solution before understanding the problem.

**Design response.** The module works backwards from a single observable behavior — *does the learner discover before proposing?* — and builds toward it: teach a lightweight framework (SCOPE), rehearse it in low-stakes activities, then transfer it into an authentic conversation where pitching too early is visibly penalized and good discovery is rewarded with information. Feedback is criterion-referenced and specific ("You explored… / You did not yet ask about… / For your next conversation, try…") so it points to the next rep rather than a grade.

**Fidelity choices.** The simulation uses transparent local logic instead of a hosted model so the prototype is fully self-contained, private, and reviewable — appropriate for a portfolio artifact and safe to host anywhere.

## Disclaimer

Portfolio prototype. All organizations, personas, systems, metrics, and scenarios are **fictional**. No proprietary or customer information is included. The scenario is for instructional demonstration only.

## Author

_Your name_ — Technical Instructional Designer
_Add portfolio link, LinkedIn, or contact here._

## License

_Optional — e.g. released under the MIT License, or “All rights reserved.” Choose what fits your portfolio._
