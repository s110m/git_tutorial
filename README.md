# Git & GitHub Learning Repository

A practical and beginner-friendly repository for learning:

- Git
- GitHub
- Branching
- Merging
- Rebasing
- Pull Requests
- Forks
- Stash
- Reset vs Revert
- HEAD
- Working with old commits
- Team workflows
- GitHub collaboration

This repository is designed as a step-by-step educational guide with:

- explanations
- diagrams
- analogies
- workflows
- practical commands
- Q&A sections
- Jupyter notebooks
- cheatsheets

---

# Repository Structure

## Basics

| File | Topic |
|---|---|
| `01_basics.ipynb` | Basic Git concepts |
| `01_git_basics(1).ipynb` | Additional Git basics |

---

## Staging, Reset, Restore

| File | Topic |
|---|---|
| `02_store_vs_reset.ipynb` | Staging area, reset, restore |
| `07_git_checkout_vs_reset.ipynb` | Checkout vs reset |
| `08_git_switch_and_restore.ipynb` | Switch and restore |

---

## Branching & Merging

| File | Topic |
|---|---|
| `04_git_branching.ipynb` | Git branching |
| `05_git_merging_conflicts.ipynb` | Merge conflicts |
| `06_git_merging_conflict.ipynb` | Conflict resolution |

---

## Working with History

| File | Topic |
|---|---|
| `09_git_working_with_old_commits.ipynb` | Old commits and recovery |
| `10_git_HEAD.ipynb` | Understanding HEAD |

---

## GitHub Workflows

| File | Topic |
|---|---|
| `11_git_push_into_github.ipynb` | Push local repo to GitHub |
| `12_git_push_conflicts.ipynb` | Push conflicts and solutions |
| `13_git_pull_fetch.ipynb` | Pull vs fetch |
| `14_git_stash.ipynb` | Stash workflow |
| `15_git_rebase_vs_merge.ipynb` | Rebase vs merge |
| `16_git_pull_request.ipynb` | Pull requests |
| `17_git_fork.ipynb` | Fork workflow |
| `18_git_workflow_fork_pull_request.ipynb` | Full open-source workflow |

---

# Topics Covered

This repository explains:

- `git init`
- `git add`
- `git commit`
- `git status`
- `git log`
- `git diff`
- `git branch`
- `git switch`
- `git checkout`
- `git merge`
- `git rebase`
- `git stash`
- `git reset`
- `git revert`
- `git restore`
- `git fetch`
- `git pull`
- `git push`
- `git clone`
- `git fork`
- Pull Requests
- GitHub collaboration
- Merge conflicts
- Detached HEAD
- Team workflows
- Public vs private history
- Rebase safety
- Fork vs branch
- Open-source contribution workflows

---

# Educational Style

The notebooks use:

- simple explanations
- visual diagrams
- real-world analogies
- command-by-command workflows
- beginner-friendly descriptions
- practical team-development scenarios

Examples include:

- engineers editing blueprints
- company document workflows
- official vs private history
- collaboration scenarios

---

# Example Workflow Covered

```text
Fork
  ↓
Clone
  ↓
Create Branch
  ↓
Make Changes
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Review
  ↓
Merge
```

---

# Cheatsheet

This repository also includes a LaTeX Git/GitHub cheatsheet PDF source containing:

- common commands
- workflow summaries
- merge/rebase diagrams
- stash/reset/revert summaries
- pull request workflow
- GitHub collaboration notes

---

# Recommended Learning Order

## Beginner

1. Basics
2. Add / Commit / Status
3. Branching
4. Merging
5. Merge conflicts

---

## Intermediate

6. Reset vs Revert
7. Switch vs Restore
8. Working with old commits
9. HEAD

---

## Advanced

10. Rebase vs Merge
11. Fetch vs Pull
12. Stash
13. Fork workflow
14. Pull requests
15. Team collaboration

---

# How to Run

You can open the notebooks using:

- Jupyter Notebook
- JupyterLab
- VSCode
- Google Colab (after upload)

---

# Example Commands

## Clone Repository

```bash
git clone https://github.com/your-username/repository.git
```

---

## Create Branch

```bash
git switch -c feature
```

---

## Commit Changes

```bash
git add .
git commit -m "message"
```

---

## Push to GitHub

```bash
git push -u origin feature
```

---

# Target Audience

This repository is useful for:

- beginners learning Git
- students
- researchers
- developers new to GitHub
- people learning collaboration workflows
- open-source contributors

---

# Main Goal

The goal of this repository is not only to teach commands, but also to explain:

```text
WHY Git behaves the way it does
```

including:

- history safety
- collaboration
- branching philosophy
- merge conflicts
- rebasing risks
- GitHub workflows

---

# License

Educational use.

---

# Author

Seyed Ali Mousavi

---

# Final Note

Git becomes much easier once you understand:

```text
Git is mainly a history-management system
```

Most commands are related to:

- moving through history
- rewriting history
- preserving history
- safely combining histories
- collaborating on shared histories
