

## DevOps Team 6 Collaboration.

This repository is a **team 6 project** designed to practice GitHub collaboration, Git best practices, branch protection rules, pull requests (PRs), and code reviews.

---

### 📌 Objectives
- Learn and apply Git branching strategies.
- Use **feature branches** for individual contributions.
- Enforce **branch protection rules** on `main` and `develop`.
- Collaborate via **pull requests (PRs)** and **code reviews**.
- Maintain a clean and traceable **commit history**.

---

### 🏗️ Branching Strategy
- **main** → Protected branch, contains production-ready code only.
- **develop** → Integration branch where all features are merged before release.
- **feature/<name>-intro** → Each team member’s personal branch for contributions.

---

### 🔒 Branch Protection Rules
- No direct commits allowed to `main` or `develop`.
- At least **1 PR approval** required before merging.
- Force pushes are disabled.

---

### 👩‍💻 Team Member Tasks
1. **Clone** the repository  
   ```bash
   git clone <repo_url>
   cd devops-collab-workflow

>> Create a feature branch

Add your profile
Create a Markdown file in the team/ folder with:

Your name

Favorite DevOps tool

One Git command you learned

Commit & push changes

Open a Pull Request (PR) → from your feature branch into develop.

Review a teammate’s PR → Approve or request changes.

Merge your PR → After at least one approval and status


