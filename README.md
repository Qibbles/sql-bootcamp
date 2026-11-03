# SQL Bootcamp

A free, self-paced SQL refresher that runs entirely in your browser. No install, no sign-up, no server.

You practise on a realistic mock **payments database** (customers and cross-border transfers), so the questions look like the ones you'd get in a product ops, analyst or operations interview at a fintech.

## What's inside

- **Lessons written for beginners**: what a table is, then SELECT, WHERE, ORDER BY, GROUP BY, HAVING and more, with plain-English explanations.
- **"Try it" buttons** on every example that run it in a live console.
- **Auto-checked exercises** that tell you exactly what's wrong: wrong columns, too many rows, wrong order, which column differs.
- **Progressive help**: each wrong try unlocks more. First what's wrong and what to focus on, then a hint, then a plain-English plan, then a preview of the right result, then the answer one part at a time.
- **Specific diagnostics**: catches wrong capitals in text values ('failed' vs 'FAILED'), values that don't exist in the data, AND/OR without brackets, date ranges that miss the last day, COUNT where COUNT(DISTINCT) is needed, SUM vs AVG mix-ups, breaking the GROUP BY rule, and PostgreSQL gotchas.
- **Compare with the model answer**: a side-by-side, part-by-part comparison of your query and the model answer.
- **"Stuck? Common questions"**: a searchable FAQ that shows the questions most relevant to the exercise you're on.
- **Step-by-step answer explanations**, in the order the database actually runs the query.
- **Adaptive "Weak spots" practice** that tracks which skills you struggle with and gives you more questions on them, bringing back anything you got wrong until you get it right first time.
- **Try counts** on every question ("Solved in 3 tries").
- A read-only console, so you can't break the practice data.

Your progress is saved in your own browser (localStorage). Nothing is sent anywhere.

## Run it

**Option 1: just open it.** Download `index.html` and double-click it. It needs an internet connection the first time to load the SQL engine ([sql.js](https://github.com/sql-js/sql.js)) and fonts from public CDNs.

**Option 2: host it yourself.** It's one static file, so any static host works:

- **GitHub Pages**: fork this repo, then go to Settings → Pages → Deploy from branch → `main` / root.
- **Netlify / Vercel / Cloudflare Pages**: drag the folder in, or connect the repo. No build step.
- **Locally**: `python3 -m http.server` in this folder, then open http://localhost:8000.

## Curriculum

| Day | Topic | Status |
|---|---|---|
| 1 | SELECT, WHERE, ORDER BY, LIMIT, IN, BETWEEN, LIKE, NULL, dates | Ready |
| 2 | COUNT, SUM, AVG, GROUP BY, HAVING, grouping by month | Ready |
| 3 | CASE WHEN and rates | Coming |
| 4 | JOINs | Coming |
| 5 | Multi-table joins | Coming |
| 6 | Dates | Coming |
| 7 | Review | Coming |
| 8 | CTEs | Coming |
| 9 | Chained CTEs | Coming |
| 10 | ROW_NUMBER and ranking | Coming |
| 11 | LAG and running totals | Coming |
| 12 | NULLs and edge cases | Coming |
| 13 | Mock test 1 | Coming |
| 14 | Mock test 2 | Coming |

## Notes

- The practice database is **SQLite**, generated in the page from a fixed seed, so everyone gets the same data and the checker's answers are always consistent. Lessons point out where **PostgreSQL** differs.
- All data is made up.
- The "Ask Claude" tutor panel only appears when the page is opened inside Claude (claude.ai). Everywhere else it stays hidden and everything else works the same.

## License

MIT. Use it, fork it, adapt it for your own team or class.
