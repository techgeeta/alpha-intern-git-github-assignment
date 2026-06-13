# Assignment Solutions

## Day 1: Git Foundations

### Easy Level
## Git Version

git version 2.54.0.windows.1

## Commands Used To Configure Git

git config --global user.name "Geeta Mehra"

git config --global user.email "mehrageeta602@gmail.com"

---

## Git and GitHub

### Git
- Version control system
- Works locally
- Tracks file changes

### GitHub
- Cloud platform
- Stores repositories online
- Enables collaboration

---
### Medium Level
1. **Difference between Git and GitHub:**
   Git is the software installed on your computer to track versions. GitHub is the website/service where you store those versions online and collaborate with others.

## Output of git log --oneline
Example:

3039065 (HEAD -> master) Added practice file on feature branch
e07c4bc Added .gitignore and folder structure with .gitkeep
84632e6 Initial commit: Added README with introduction

---

## Branch Rename Command

git branch -m old_branch_name new_branch_name

---

## Merge Conflict Explanation

A merge conflict occurs when two branches modify the same lines in a file. Git cannot decide which changes to keep automatically. The conflict must be resolved manually.

---

## git diff

git diff shows the differences between the modified files and the last committed version.

---

## git stash

git stash temporarily saves uncommitted changes without committing them.

---

## Output of git tag

v1.0

---

## git reflog

git reflog tracks all HEAD movements and helps recover lost commits.

---

## Difference Between git fetch and git pull

### git fetch
Downloads changes from the remote repository but does not merge them.

### git pull
Downloads changes and merges them automatically.

---

## Open Source Contribution Flow

1. Fork repository
2. Clone repository
3. Create branch
4. Make changes
5. Commit changes
6. Push branch
7. Create Pull Request

---

## Upstream Remote Command

git remote add upstream https://github.com/sample/repository.git