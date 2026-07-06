I'm a search consultant at CPI. I run a desk of active mandates placing investment professionals — PE, credit, real estate, hedge fund, VC, family office — and on any given day I'm juggling eight or nine live searches, dozens of candidates at different stages, and a stream of client feedback that lands over email and phone. My real problem isn't finding candidates. It's that everything I know is scattered: my raw call notes live in one place, my candidate tracker in another, the mandate list in a spreadsheet, and client feedback buried in my inbox. Every morning I rebuild the picture in my head of "what actually needs me today," and I lose the thread on searches that are quietly going sideways.

I've attached four files that represent my desk:
- `active-searches.csv` — my live mandates (client, role, strategy, stage, fee, target close date, status)
- `candidates.csv` — every candidate in play, which search they're on, their stage, last contact date, and interest level
- `candidate-call-notes.md` — my messy raw notes from screening calls, one per candidate
- `client-feedback.json` — what clients said about candidates they've interviewed

Using all four files, build me a single interactive HTML dashboard — my "search desk" — that I can open in a browser. It should include:

1. **A search pipeline board** — one card per active mandate, grouped or colored by status (On Track / At Risk / Overdue). Each card shows the client, role, strategy, stage, fee estimate, days until target close, and how many candidates are in that pipeline.

2. **A "Needs Me Today" action queue** — the single most important panel. Pull together, ranked by urgency: candidates with a client "Strong Yes" waiting on my next move, offer-stage candidates at risk of stalling, searches that are Overdue or At Risk with a thin pipeline, and any candidate I haven't contacted in 14+ days. For each item, say what the action is and why it's urgent — cross-referencing the call notes and client feedback, not just the tracker.

3. **A candidate table per search** — expandable, showing name, current firm/title, stage, interest level, whether they've been submitted to the client, and the latest client feedback rating if there is one.

4. **A few desk metrics up top** — total open searches, total fee value in play, count of candidates by stage, and number of searches at risk.

Use CPI-appropriate language (mandates, searches, candidates, submissions, placements) and make it clean and professional — this is a tool I'd actually keep open all day. Color-code status consistently so I can scan it in five seconds.

This isn't a summary — I need you to connect my call notes to the tracker to the client feedback and tell me where a placement is about to slip. Surface the two or three things that will cost me a fee if I miss them today.

After I see the first version, I'll want to refine it:
- Re-rank the action queue by fee value at risk instead of just urgency
- Add a "re-route" flag for candidates who are wrong for their current search but right for another one
- Filter the whole dashboard to just one strategy (e.g. only PE Buyout)

If I finish early, I want to try:
- Have you draft the client-nudge emails for every "Strong Yes waiting on me" item, in my voice
- Add a simple "days in stage" aging indicator so I can see which candidates are going stale
- Generate a one-paragraph Monday-morning status update I could send my team lead, straight off the dashboard data
- Ask you to rebuild this dashboard automatically every Monday from an updated set of these files
