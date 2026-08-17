# Quick Reference — GitHub

## Key Concepts

| Term | Meaning |
|------|---------|
| Repository (repo) | A project's folder on GitHub; tracks all file versions |
| Commit | A snapshot of your changes saved to the repo history |
| Branch | An independent line of development |
| Merge | Combining one branch's changes into another |
| Push/Pull | Sync local repo ↔ remote (GitHub) |
| Fork | Your personal copy of someone else's repo |
| Pull Request (PR) | Proposal to merge changes; primary collaboration tool |
| Issue | A tracked task, bug, or discussion thread |
| GitHub Actions | CI/CD: runs workflows when you push/open PR/tag |

## Git Commands (CLI)

```
git init                    # create local repo
git clone <url>             # copy a repo to your machine
git add <file>              # stage a change
git commit -m "msg"        # commit staged changes
git branch                  # list branches
git switch -c <branch>     # create + switch to new branch
git merge <branch>          # merge branch into current branch
git push origin <branch>   # upload to GitHub
git pull origin <branch>   # download from GitHub
```

## gh CLI Commands

```
gh auth login               # authenticate with GitHub
gh repo create <name>       # create a repo on GitHub
gh repo clone <name>        # clone a repo
gh pr create                # open a PR from current branch
gh pr list                  # list PRs
gh issue create             # create an issue
gh issue list               # list issues
```

## GitHub.com UI Navigation

| Area | URL Pattern | Purpose |
|------|------------|---------|
| Repo home | `/<owner>/<repo>` | Overview, files, README |
| Code tab | `/<owner>/<repo>/CODE` | Browse files, branches |
| Issues | `/<owner>/<repo>/issues` | Tasks, bugs, discussions |
| Pull Requests | `/<owner>/<repo>/pulls` | Code review, merge proposals |
| Actions | `/<owner>/<repo>/actions` | View workflow runs, logs |
| Settings | `/<owner>/<repo>/settings` | Repo config, deploy keys, hooks |
| Branches | `/<owner>/<repo>/branches` | Manage branches |
| Wiki | `/<owner>/<repo>/wiki` | Documentation |
