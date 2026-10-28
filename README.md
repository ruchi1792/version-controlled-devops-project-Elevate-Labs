# Version-Controlled DevOps Project with Git

## Project Overview

This project demonstrates Git and GitHub best practices for managing a DevOps project. It covers repository initialization, branching strategies, meaningful commits, pull requests, version tagging, and Markdown documentation.

## Objectives

- Manage source code using Git.
- Use `main`, `dev`, and feature branches.
- Follow a pull-request-based merge workflow.
- Maintain a `.gitignore` file.
- Document project activities using Markdown.
- Create and publish a version tag.

## Tools Used

- Git
- GitHub
- WSL Ubuntu
- Markdown

## Branching Strategy

- `main`: Stable, released project version.
- `dev`: Integration branch.
- `feature/*`: Branches for individual changes.

## Workflow

1. Create and clone the GitHub repository.
2. Create the development and feature branches.
3. Make changes and commit with meaningful messages.
4. Push feature branches to GitHub.
5. Create pull requests from feature branches into `dev`.
6. Review and merge `dev` into `main` using a pull request.
7. Tag the release as `v1.0.0`.

## Repository Structure

```text
version-controlled-devops-project-Elevate-Labs/
├── README.md
├── .gitignore
└── docs/
    ├── git-workflow.md
    └── task-log.md
```

## Useful Commands

```bash
git status
git branch -a
git switch dev
git switch -c feature/my-change
git add .
git commit -m "docs: describe change"
git push -u origin feature/my-change
git log --oneline --graph --all
git tag
```

## Release

- Version: `v1.0.0`
- Release branch: `main`

## Learning Outcomes

- Git repository and remote management
- Branch-based development
- Pull-request reviews and merges
- Commit history inspection
- Version tagging
- Markdown project documentation
