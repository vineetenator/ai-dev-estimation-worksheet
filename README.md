# AI-Assisted Development Estimation Worksheet

A fill-in-the-blanks spreadsheet for estimating engineering effort when your team uses AI coding tools like Claude Code, Cursor, or Copilot.

## The problem it solves

Asking an AI "how long will this take?" gives you a padded, generic number. The model has no idea who's on your team, how well they know the codebase, or what "done" means for you — so it defaults to a worst-case guess, and usually ignores headcount entirely.

This worksheet flips that around. It uses **your** judgment as the engine and treats AI as a multiplier, not an oracle.

## How it works

**1. Baseline** — Estimate the work as if there were no AI. This is your anchor.

**2. Buckets** — Split the work into three types, because AI doesn't speed everything up equally:
- Mechanical / boilerplate: ~3-5x faster
- Integration with existing code: ~1.5-2x faster
- Novel / ambiguous / judgment work: ~1x (no real speedup — the bottleneck is thinking, not typing)

**3. Add-backs** — Add back what AI does *not* compress:
- Code review (which grows, since more code gets produced)
- Scoping and discovery
- Integration friction and mid-build surprises

**4. Timeline** — Convert effort into a calendar estimate. Engineer-weeks isn't calendar-weeks until you know what can actually run in parallel.

## How to use it

1. Download `AI-Dev-Estimation-Worksheet.xlsx`
2. Open it in Excel or Google Sheets
3. Fill in the highlighted (yellow) cells — the rest calculates automatically
4. Adjust the multipliers over time to match your own team's observed data

The "How to use" tab inside the file explains the reasoning behind each step.

## A note on the numbers

The default multipliers are starting points, not laws. The honest result for most real projects lands around a 1.5-2x speedup once you account for review, scoping, and integration — excellent, but nowhere near the "AI makes it instant" claims. Calibrate to your own reality.

## License

Free to use and adapt. Attribution appreciated but not required.

---

Built by Vineet Arya — I write about AI-assisted engineering on LinkedIn: https://www.linkedin.com/in/vineet-arya/.
