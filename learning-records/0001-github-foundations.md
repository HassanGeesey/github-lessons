# Learning Record: GitHub Foundations

## Context

Learning GitHub over 2–3 days (1.5 hr/day). Prior experience: moderate — can
init a repo and commit, but not comfortable with PRs, Actions, or Pages.

## Decisions

- **Curriculum structure**: 3 self-contained HTML lessons, each with a
  "Try this at home" checklist of 3–5 concrete actions.
- **Delivery mechanism**: GitHub Pages site at
  `https://hassangeesey.github.io/github-lessons/` — chosen because Telegram
  can't display HTML file attachments directly, but can show links.
- **Hands-on focus**: Each lesson ends with a real GitHub.com or CLI action.
  No passive reading beyond 30 min.
- **Time budget**: 1.5 hr/day strict — lessons are paced to fit.

## Key Insights

- The `gh` CLI is the fastest path to creating repos, PRs, and secrets.
- `gh repo create --source=. --push` is a massive time-saver for new repos.
- GitHub Pages via `gh api --method POST ... /pages --input file.json` works
  reliably when the source is passed as a JSON object, not a string.

## Next Steps

- Consider setting up a daily lesson delivery cron to Telegram at 9 AM UTC.
- Day 3 includes VPS deployment — verify the SSH action works with the user's
  actual VPS credentials.
