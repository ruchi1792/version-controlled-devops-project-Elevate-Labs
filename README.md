# 🚀 Version-Controlled DevOps Project with Git & GitHub

![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Collaboration-181717?logo=github&logoColor=white)
![DevOps](https://img.shields.io/badge/Domain-DevOps-blue)
![Release](https://img.shields.io/badge/Release-v1.0.0-success)

## 📌 Project Overview

This project demonstrates Git and GitHub best practices for DevOps project management, including repository management, branching, commits, pull requests, merge workflows, `.gitignore`, documentation, and release tagging.

## 🎯 Project Objectives

- 📁 Manage a Git repository.
- 🌿 Use `main`, `dev`, and feature branches.
- 🔀 Review and merge changes using Pull Requests.
- 📝 Write meaningful commit messages.
- 🚫 Configure `.gitignore`.
- 📚 Maintain Markdown documentation.
- 🏷️ Use Git tags for release versioning.
- 📸 Document implementation with screenshots.

## 🛠️ Technologies and Tools

| Tool | Purpose |
|---|---|
| Git | Version control |
| GitHub | Remote repository and Pull Requests |
| Ubuntu on WSL | Development environment |
| Markdown | Documentation |
| Git tags | Release versioning |

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
main
└── dev
    ├── feature/project-documentation
    ├── feature/gitignore-setup
    ├── feature/add-screenshots-folder
    ├── feature/add-project-screenshots
    └── feature/professional-readme
```

- 🟢 **main:** Stable project branch.
- 🔵 **dev:** Integration branch.
- 🧩 **feature branches:** Individual changes and improvements.

## ⚙️ Project Workflow

1. Created and cloned the GitHub repository.
2. Created development and feature branches.
3. Added project documentation.
4. Configured `.gitignore`.
5. Committed and pushed changes.
6. Created and reviewed Pull Requests.
7. Merged approved changes into the relevant branches.
8. Created and pushed the `v1.0.0` tag.
9. Added screenshots as project evidence.

## 📁 Repository Structure

```text
version-controlled-devops-project-Elevate-Labs/
├── README.md
├── .gitignore
├── docs/
│   ├── git-workflow.md
│   └── task-log.md
└── Screenshots/
    ├── 01-github-repository.PNG
    ├── 02-git-branches.PNG
    ├── 03-merged-pull-requests.PNG
    ├── 04-git-commit-history.PNG
    ├── 05-gitignore.PNG
    ├── 06-task-documentation.PNG
    ├── 07-release-tag.PNG
    ├── 08-final-verification.PNG
    └── README.md
```

## 📸 Project Screenshots

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
# Check repository status
git status

# List local and remote branches
git branch -a

# Switch branches
git switch dev

# Create a feature branch
git switch -c feature/my-change

# Stage and commit changes
git add .
git commit -m "docs: update project documentation"

# Push a feature branch
git push -u origin feature/my-change

# View commit history
git log --oneline --graph --all

# List release tags
git tag
```

### Check Repository Status

- 📖 [Git Workflow](docs/git-workflow.md)
- ✅ [Task Log](docs/task-log.md)
- 📸 [Screenshots](Screenshots/)

## 🏷️ Release Information

- **Version:** `v1.0.0`
- **Release type:** Initial project release
- **Release branch:** `main`

## 🎓 Key Learnings

- Git branching and merging.
- Remote repository management.
- Pull Request reviews and conflict resolution.
- Commit history inspection.
- `.gitignore` configuration.
- Markdown documentation.
- Version tagging.

## 👩‍💻 Author

**Ruchita Deshmukh**

GitHub Profile: [@ruchi1792](https://github.com/ruchi1792)

[GitHub Profile](https://github.com/ruchi1792)

---

⭐ Explore the repository and its documentation to learn more about the project.
