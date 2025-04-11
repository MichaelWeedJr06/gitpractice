# Git/Github Notes

Note: use ctrl+shift+v to preview files in VS Code

## Basic Concepts

1. **Repository (repo)**
   A project folder that Git is tracking. Can be **local** (on your computer) or **remote** (like Github)
2. **Version Control**
   A system that tracks changes to code over time, letting you revert to previous versions or collaborate with others.
3. **Commit**
   A snapshot of your changes. Includes a message describing what was changed.
4. **Working Directory**
   The current state of your files on disk.
5. **Staging Area**
   Where you prepare changes before committing. You "stage" files that are ready to be committed.

---

6. `git init`
   Initializes a new Git repository in a folder.
7. `git status`
   Shows the current state of the working directory and staging area.
8. `git add <file>`
   Stages changes in a file for the next commit. (note you can `git add *` to stage all files in the working directory, while `git add .` does the whole repository)
