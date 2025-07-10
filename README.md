# 🧠 Git Skills Showcase

This repository demonstrates my practical knowledge of Git version control. It includes examples of key commands used in real-world workflows: branching, merging, resolving conflicts, working with history, stashing, resetting, rebasing, and more.

---

## 📁 Repository Structure

- demo.txt — the main file used to demonstrate all changes
- .gitignore — shows how to ignore files/folders
- multiple branches: feature/*, bugfix/*, stash-demo, rebase-demo, etc.

---

## 🧩 Git Skills Demonstrated

| Git Feature                 | Description                                                        |
|----------------------------|--------------------------------------------------------------------|
| git init                 | Initialize a new repository                                       |
| git add, git commit    | Stage files and create commits                                    |
| git branch, checkout   | Create and switch between branches                                |
| git merge                | Merge branches and resolve conflicts                              |
| git stash                | Save and restore uncommitted changes                              |
| git reset, revert      | Undo changes or revert to a previous state                        |
| git rebase               | Rewrite commit history                                             |
| git log, diff, status| View history, differences, and working directory status           |
| git tag                  | Create release tags                                               |
| git remote, push       | Connect to GitHub and publish the repo                            |
| git bisect               | Find the commit that introduced a bug                             |
| .gitignore               | Configure ignored files and folders                               |

---

## 📈 Branch Visualization

To view the branch and commit graph:

On GitHub:
- Go to Insights → Network in the repository
- Or visit: [https://github.com/<your-username>/<repo-name>/network](https://github.com/BDR-BED/git-skills-showcase/network)

Locally:
```bash
git log --oneline --graph --all --decorate
