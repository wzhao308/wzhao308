## Hi there 👋

## About Me

I build full-stack tools that solve problems from my own day-to-day as a student at the University of Illinois Urbana-Champaign — course tracking, study habits, and campus logistics.

### [Prioriton](https://github.com/wzhao308/Prioriton)
A student time and grade management app. Syncs assignments and grades from Canvas, Gradescope, and PrairieLearn, tracks study time per class with a start/stop timer, visualizes grade and study trends on an analytics dashboard, and uses an LLM to turn a week of that data into personalized, grounded study recommendations. Built with FastAPI, SQLModel, React, TypeScript, and the Anthropic API.

### [ManaPeer](https://github.com/wzhao308/ManaPeer)
A unified academic task tracker that automatically pulls assignments and due dates from Canvas, Gradescope, and PrairieLearn into one dashboard, calendar, and reminder system. Canvas connects Canvas's official API; Gradescope and PrairieLearn have no public API, so it drives a real browser session (Playwright) through a one-time interactive login, then reuses that session headlessly for periodic syncs. Built with FastAPI, SQLite, React, TypeScript, and Playwright.

### [PickILL](https://github.com/wzhao308/PickILL) — [live](https://pickill.vercel.app)
A live queue board for UIUC's 8 pickleball courts. Students join a court's line from a shared, real-time 2×4 map, and once at the front choose singles or doubles — the app auto-fills the rest of the match from whoever's next in that line. Built with Next.js and a Redis-backed API so the queue stays in sync across everyone using it.
