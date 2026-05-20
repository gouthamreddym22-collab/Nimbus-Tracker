# Nimbus — Progress Tracker

Single-file HTML view of progress toward Nimbus's **Phase 1 closed alpha** (50–100 invited users on working SaaS).

Investor-facing surface. Numbers are deliberately conservative: each module's percent folds in design completeness, build progress, and test confidence — untested work is heavily discounted.

**Nimbus is a working title** — final product name TBD before launch.

## Live

Hosted via GitHub Pages — `index.html` redirects to `tracker.html`.

## Local view

Open `tracker.html` directly in any browser — no server needed. All data lives in the `DATA` block inside `tracker.html`; edit it to refresh the view.

## Updating

```
git add tracker.html
git commit -m "tracker: <what changed>"
git push
```

Tracker pushes are batched at session-handoff alongside the sibling tracker repo. GitHub Pages re-deploys on every push.
