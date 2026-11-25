# P3 · Feature-branch Git workflow

Make a portfolio change on its own branch, review the diff, and merge it back into `main`. This keeps unfinished work separate from the stable version.

## Goals

- Create and switch to a feature branch.
- Commit a small change without changing `main`.
- Merge the feature branch and confirm the history.

## Exercise

```sh
git switch -c feature/about-section
```

Add an About section to the portfolio README or page, then inspect and commit the change:

```sh
git status
git diff
git add README.md
git commit -m "Add portfolio about section"
git log --oneline --decorate
```

Merge the finished feature into `main`:

```sh
git switch main
git pull
git merge --no-ff feature/about-section
git push
```

## Try next

Push the feature branch with `git push -u origin feature/about-section` and open a pull request on GitHub before merging. For a solo local exercise, the merge commands above are enough. Delete the branch after merging with `git branch -d feature/about-section`.
