# 🚀 Version-Controlled DevOps Project with Git & GitHub

![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Collaboration-181717?logo=github&logoColor=white)
![DevOps](https://img.shields.io/badge/Domain-DevOps-blue)
![Release](https://img.shields.io/badge/Release-v1.0.0-success)

## 📌 Project Overview

This project demonstrates how to manage a project using **Git and GitHub** by implementing version control, feature branching, commits, pull requests, merging, repository documentation, and release tagging.

The project follows a structured Git workflow to maintain organized development, track changes, and improve collaboration.

## 🎯 Project Objectives

- Understand Git fundamentals and version control.
- Create and manage multiple Git branches.
- Follow a feature-branch development strategy.
- Track project changes through meaningful commits.
- Create and review GitHub Pull Requests (PRs).
- Merge feature branches into development and main branches.
- Use `.gitignore` to exclude unnecessary files.
- Organize project documentation and screenshots.
- Create and manage Git release tags.

## 🛠️ Technologies and Tools

| Tool | Purpose |
|---|---|
| Git | Version control and change tracking |
| GitHub | Remote repository hosting and collaboration |
| Git Bash / Ubuntu WSL | Command-line Git operations |
| Markdown | Project documentation |
| Git Tags | Version and release management |

## 🌿 Git Branching Strategy

This project uses a feature-branch workflow.

| Branch | Purpose |
|---|---|
| `main` | Stable project version |
| `dev` | Development and integration branch |
| `feature/*` | Individual features, changes, and documentation tasks |

### 🔄 Workflow

1. Create a feature branch from `dev`.
2. Make changes to the project files.
3. Stage and commit the changes.
4. Push the feature branch to GitHub.
5. Open a Pull Request from the feature branch into `dev`.
6. Review and merge the Pull Request.
7. Open another Pull Request from `dev` into `main`.
8. Merge approved changes into `main`.
9. Tag a stable version using Git tags.

## 📂 Project Structure

```text
version-controlled-devops-project-Elevate-Labs/
│
├── .gitignore
├── README.md
│
├── docs/
│   ├── git-workflow.md
│   └── task-log.md
│
└── Screenshots/
    ├── README.md
    ├── 01-github-repository.PNG
    ├── 02-git-branches.PNG
    ├── 03-merged-pull-requests.PNG
    ├── 04-git-commit-history.PNG
    ├── 05-gitignore.PNG
    ├── 06-task-documentation.PNG
    ├── 07-release-tag.PNG
    └── 08-final-verification.PNG
```

*Note: The structure above represents the intended project layout. Keep only paths and filenames that actually exist in your repository.*

## 📸 Project Screenshots

The following screenshots document the project setup, Git workflow, pull requests, commits, and release verification.

### 1️⃣ GitHub Repository

![GitHub Repository](Screenshots/01-github-repository.PNG)

### 2️⃣ Git Branches

![Git Branches](Screenshots/02-git-branches.PNG)

### 3️⃣ Merged Pull Requests

![Merged Pull Requests](Screenshots/03-merged-pull-requests.PNG)

### 4️⃣ Git Commit History

![Git Commit History](Screenshots/04-git-commit-history.PNG)

### 5️⃣ Git Ignore Configuration

![Git Ignore](Screenshots/05-gitignore.PNG)

### 6️⃣ Project Documentation

![Project Documentation](Screenshots/06-task-documentation.PNG)

### 7️⃣ Git Release Tag

![Git Release Tag](Screenshots/07-release-tag.PNG)

### 8️⃣ Final Verification

![Final Verification](Screenshots/08-final-verification.PNG)

## 💻 Useful Git Commands

### Initialize and Clone

```bash
git init
git clone <repository-url>
```

### Check Repository Status

```bash
git status
git branch
git log --oneline
```

### Create and Switch Branches

```bash
git switch dev
git switch -c feature/new-feature
```

### Stage and Commit Changes

```bash
git add .
git commit -m "feat: add new feature"
```

### Push a Branch to GitHub

```bash
git push -u origin feature/new-feature
```

### Pull Latest Changes

```bash
git pull origin dev
```

### Merge a Feature Branch

```bash
git switch dev
git merge feature/new-feature
```

### Create a Release Tag

```bash
git tag -a v1.0.0 -m "Version 1.0.0"
git push origin v1.0.0
```

*Note: Create a tag only if it does not already exist. The project already has a `v1.0.0` tag.*

## 📚 Documentation

- [Git Workflow](docs/git-workflow.md)
- [Task Log](docs/task-log.md)
- [Project Screenshots](Screenshots/)

## 🏷️ Release Information

- **Release Version:** `v1.0.0`
- **Versioning Tool:** Git Tags
- **Repository Status:** Managed using Git and GitHub

## 🎓 Key Learnings

Through this project, I practiced:

- Git version control and repository management.
- Branch creation, switching, and merging.
- Feature-based development workflows.
- Commit history tracking and meaningful commit messages.
- GitHub Pull Requests and merge-conflict resolution.
- `.gitignore` configuration.
- Markdown documentation.
- Release tagging and project verification.

## 👩‍💻 Author

**Ruchita Deshmukh**

GitHub Profile: [@ruchi1792](https://github.com/ruchi1792)

## ⭐ Conclusion

This project demonstrates a practical Git and GitHub workflow for managing development changes, organizing documentation, collaborating through Pull Requests, and maintaining a structured repository.

If you find this project useful, feel free to explore the repository and its documentation.

---

**Built as part of DevOps hands-on practice.** 🚀
