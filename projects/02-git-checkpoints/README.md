# P2 · Portfolio repo with an initial commit

Initialize Git in the portfolio folder and save its first snapshot. Start in the portfolio root created in P1.

## Goals

- Initialize a repository in the correct folder.
- Stage a project README and make the initial commit.
- Confirm the commit is in the repository history.

## Exercise

```sh
git init
printf '# Frontend Learning Portfolio\n\nA collection of small frontend projects.\n' > README.md
git status
git add README.md
git diff --cached
git commit -m "Create portfolio repository"
```

Inspect the saved snapshot and working tree:

```sh
git log --oneline
git status
```

## Try next

Add a short sentence to `README.md`. Run `git diff` to review it, then stage and commit the update separately. Keep the initial commit focused on establishing the portfolio.
