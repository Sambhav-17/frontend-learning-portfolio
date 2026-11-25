# P4 · GitHub README and version tags

Document the portfolio repository on GitHub and create a lightweight version tag for a finished milestone.

## Goals

- Give visitors a clear overview and navigation in the root README.
- Write Markdown links to project folders.
- Create and push a version tag.

## Exercise

Edit the repository's root `README.md`. Include a short introduction, a numbered project list with links to each project folder, and instructions for opening the HTML/CSS exercises. Preview the Markdown on GitHub after pushing the update.

Once the README and projects are committed, tag the milestone:

```sh
git status
git tag -a v1.0.0 -m "First portfolio milestone"
git push origin main
git push origin v1.0.0
```

Check the tag and commit it points to:

```sh
git show v1.0.0 --no-patch
git tag --list
```

Use `v1.0.0` for the first stable milestone. Follow semantic versioning for later tags: patch for fixes, minor for backward-compatible additions, and major for incompatible changes.
