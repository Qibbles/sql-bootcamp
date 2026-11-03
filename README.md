# SQL Bootcamp

### ▶ [Start practising now: qibbles.github.io/sql-bootcamp](https://qibbles.github.io/sql-bootcamp/)

Prefer your own copy, or want the built-in AI tutor? See [Run it](#run-it) for all three options.

A free, self-paced 14-day SQL course that runs entirely in your browser. No install, no sign-up, no server. Just open the link above and start Day 1.

You practise on a realistic mock **payments database** (customers, cross-border transfers, exchange rates and countries), so the questions look like the ones you'd get in a product ops, analyst or operations interview at a fintech.

**It learns from you.** Every answer you check is tracked by skill. The course itself is the same for everyone, but your practice isn't: the **Weak spots** mode keeps serving more questions on the skills you struggle with, brings back anything you got wrong until you get it right first time, and eases off the ones you've mastered. The more you practise, the more it's tailored to you.

## What's inside

- **Lessons written for beginners**: what a table is, then SELECT, WHERE, ORDER BY, GROUP BY, HAVING and more, with plain-English explanations.
- **"Try it" buttons** on every example that run it in a live console.
- **Auto-checked exercises** that tell you exactly what's wrong: wrong columns, too many rows, wrong order, which column differs.
- **Progressive help**: each wrong try unlocks more. First what's wrong and what to focus on, then a hint, then a plain-English plan, then a preview of the right result, then the answer one part at a time.
- **Specific diagnostics**: catches wrong capitals in text values ('failed' vs 'FAILED'), values that don't exist in the data, AND/OR without brackets, date ranges that miss the last day, COUNT where COUNT(DISTINCT) is needed, SUM vs AVG mix-ups, breaking the GROUP BY rule, and PostgreSQL gotchas.
- **Compare with the model answer**: a side-by-side, part-by-part comparison of your query and the model answer.
- **"Stuck? Common questions"**: a searchable FAQ that shows the questions most relevant to the exercise you're on.
- **Step-by-step answer explanations**, in the order the database actually runs the query.
- **Adaptive practice that learns from your progress and mistakes.** Every check is recorded against the skills that question tests (JOINs, HAVING, window functions…). The "Weak spots" view ranks your skills from "Needs work" to "Solid", and practice mode picks questions weighted toward your weakest ones, repeating missed questions until you get them right first time. The 14-day curriculum stays fixed; the practice adapts to you.
- **Try counts** on every question ("Solved in 3 tries").
- A read-only console, so you can't break the practice data.

Your progress is saved in your own browser (localStorage). Nothing is sent anywhere.

## Run it

There are three ways to use SQL Bootcamp. Pick the one that suits you.

| | Option 1: GitHub Pages | Option 2: Download and open | Option 3: Host it yourself |
|---|---|---|---|
| Setup | None | Download one file | A few minutes |
| New lessons appear automatically | Yes | No, download again | Only if you sync your copy |
| Works on phone | Yes | Not easily | Yes |
| You can edit the questions | No | Yes | Yes |
| Built-in AI tutor | No (copy-to-any-AI instead) | No (copy-to-any-AI instead) | Yes, if you host it in Claude |

### Option 1: use the GitHub Pages version (recommended)

Go to **https://qibbles.github.io/sql-bootcamp/** and start Day 1.

- **Nothing to install or download.** Works in any modern browser, on laptop or phone.
- **Always up to date.** New days and fixes show up as soon as they're published.
- **Your progress is kept** in your browser between visits.

Best if you just want to practise.

### Option 2: download and open

Download [`index.html`](index.html) (open it on GitHub, then click the download button) and double-click it to open it in your browser.

- **A copy that's yours.** It won't change unless you download a new version, and it still works if the hosted site is ever down.
- **Easy to tinker with.** Open the file in any text editor to change the questions, add your own, or translate it.
- It still needs an internet connection, to load the SQL engine ([sql.js](https://github.com/sql-js/sql.js)) and fonts from public CDNs.

Best if you want a fixed copy or plan to modify it.

### Option 3: host it yourself

It's one static file, so any host works. Pick one:

- **In Claude, as your own artifact.** This is the only way to get the **built-in AI tutor** that answers inside the page. See [Option 3 under the AI tutor section](#option-3-host-it-yourself-1) below for the steps.
- **GitHub Pages**: fork this repo, then go to Settings → Pages → Deploy from branch → `main` / root. You get your own `yourname.github.io/sql-bootcamp` link.
- **Netlify / Vercel / Cloudflare Pages**: drag the folder in, or connect the repo. No build step.
- **Locally**: run `python3 -m http.server` in this folder, then open http://localhost:8000.

Benefits:

- **Your own link** to share with a team, a study group or a class.
- **Your own version.** Customise the questions or data, and decide when to pull in updates from this repo.
- **The built-in Claude tutor**, if you host it in Claude.

Best for teams, teachers, or anyone who wants the built-in tutor.

## Ask an AI tutor while you practise

The page has an **Ask** panel beside the console for "why is the answer like this?" questions. What it does depends on which option you used above.

### Option 1: GitHub Pages version

The panel is called **Ask an AI**. Pick a question, or type your own, and click **Copy question for your AI**. It copies a ready-made prompt with:

- the question you're working on and the model answer
- your query and the feedback the checker gave you
- instructions to explain things simply, for a beginner

Paste it into **ChatGPT, Claude, Gemini** or any AI chat. Nothing is sent anywhere until you paste it yourself.

### Option 2: downloaded copy

Works exactly like Option 1: use **Copy question for your AI** and paste into any AI chat.

### Option 3: host it yourself

**On GitHub Pages, Netlify, Vercel, Cloudflare Pages or locally**, it works like Option 1: copy and paste into any AI chat.

**In Claude, you get a built-in tutor.** It answers inside the page, handles follow-up questions, and can run queries on the practice data to show you real results.

1. Download [`index.html`](index.html) (open it on GitHub, then click the download button).
2. Start a new chat in [Claude](https://claude.ai) and attach the file.
3. Send this message:

   > Publish this HTML file as an artifact exactly as it is, without changing the code. Enable the capability that lets the page ask Claude questions (the "sample" capability), so its Ask Claude panel works.

4. Open the artifact. The first time you ask a question, Claude asks your permission. Each question uses your own Claude usage, like a normal chat message.

This needs a Claude plan where artifacts can use Claude from inside the page. If the panel says "Ask an AI" with a copy button instead, that feature isn't available on your account, and copy and paste still works.

**ChatGPT and other assistants** can't run the built-in tutor, because it relies on Claude's artifact system. With them, use the **Copy question for your AI** button.

## Curriculum

All 14 days are ready. Each has a beginner-friendly lesson with runnable examples, auto-checked exercises, and extra practice questions that feed the adaptive Weak spots mode.

| Day | Topic |
|---|---|
| 1 | SELECT, WHERE, ORDER BY, LIMIT, IN, BETWEEN, LIKE, NULL, dates |
| 2 | COUNT, SUM, AVG, GROUP BY, HAVING, grouping by month |
| 3 | CASE WHEN, conditional counts and rates |
| 4 | JOINs: INNER vs LEFT, aliases, finding what's missing |
| 5 | Joining 3+ tables, currency conversion, checking joins |
| 6 | Dates and times: date parts, date arithmetic, durations |
| 7 | Review: choosing the right tool |
| 8 | CTEs and subqueries |
| 9 | Chaining CTEs, shares of a total, comparing periods |
| 10 | Window functions: ROW_NUMBER, RANK, top N per group |
| 11 | LAG, LEAD, growth, running totals, moving averages |
| 12 | NULLs and edge cases: COALESCE, NULLIF, division traps |
| 13 | Mock test 1 (timed, interview-style) |
| 14 | Mock test 2 (timed, interview-style) |

That's 75 auto-checked exercises plus 40 extra practice questions, every one with a hint, a plain-English plan and a step-by-step explanation of the answer.

## Notes

- The practice database is **SQLite** (with CTEs and window functions), generated in the page from a fixed seed, so everyone gets the same data and the checker's answers are always consistent. Lessons point out where **PostgreSQL** differs.
- All data is made up.
- The built-in "Ask Claude" tutor only works when the page is published as a Claude artifact. Everywhere else the panel becomes "Ask an AI", which copies a ready-made prompt for any AI chat.

## License

MIT. Use it, fork it, adapt it for your own team or class.
