# Git Commands Summary
#### Full list available at: https://git-scm.com/cheat-sheet

| Command | Purpose |
|---------|---------|
| `git status` | Show working tree and staging area status |
| `git log --oneline` | Show git history |
|---------|---------|
| `git add .` | Stage all changes |
| `git add <file path>` | Stage selected file changes |
| `git restore .` | Undo all files from working tree |
| `git restore <file path>` | Undo selected files from working tree |
| `git restore --staged <file1> <file2> ...` | Undo selected files from stagging area |
|---------|---------|
| `git commit -m "<message>"` | Create commit with message |
| `git commit --amend -m "<message>"` | Update last commit changes and message |
| `git commit --amend --no-edit` | Update last commit changes (same message) |
| `git reset [--solf/--hard/--mixed] <commit_hash>` | Reset current branch (HEAD) to specified state,[--soft] to keep changes |
| `git revert <commit_hash>` | Revert selected commit from history |
| `git drop <commit_hash>` | Remove selected commit from history |
|---------|---------|
| `git push [-u] origin <branch>` | Upload branch to remote repository |
| `git pull [--rebase/--merge]` | Download and rebase/merge remote changes |
| `git fetch` | Download remote changes |
| `git checkout [-b] <branch>` | Switch to selected branch,[-b] to also create branch |
| `git rebase` | Rebase current branch onto selected branch |
| `git merge` | Merge selected branch into current branch |


#### GitOps Certificate ($250) with Learning Budget at: https://training.linuxfoundation.org/certification/certified-gitops-associate-cgoa/
