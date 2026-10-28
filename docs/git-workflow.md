# Git and GitHub Workflow

## Branching Strategy

- main: Stable project branch.
- dev: Integration branch.
- feature/*: Branches for individual changes.

## Development Workflow

1. Switch to the dev branch.
2. Create a feature branch.
3. Make changes and test them.
4. Stage and commit changes with meaningful messages.
5. Push the feature branch to GitHub.
6. Create a pull request targeting dev.
7. Review and merge the pull request.
8. Create a pull request from dev to main for release.

## Useful Git Commands

- `git status`
- `git branch -a`
- `git switch dev`
- `git switch -c feature/my-change`
- `git add .`
- `git commit -m "docs: describe change"`
- `git push`
- `git log --oneline --graph --all`

## Version Tags

Use annotated tags to identify releases.

Example:

- `git tag -a v1.0.0 -m "Release version 1.0.0"`
- `git push origin v1.0.0`

Create release tags after the corresponding changes have been merged into main.
