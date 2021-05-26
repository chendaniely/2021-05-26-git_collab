alskdjlkasdf
# 2021/05/26 Git Collaboration

- `git clone <URL>`: downloads the repo to current directory

## Branches

- `git branch <NAME>`: create branch <NAME>
- `git branch -a`: list all branches
- `git branch -d <NAME>`: delete <NAME>
    - `git branch -D <NAME>`: force delete <NAME>
- `git switch <NAME>`: switch to <NAME>
    - `git checkout <NAME>`: "older" way to switch branches
- `git switch -c <NAME>`: create and switch to branch 1 command
    - `git checkout -b <NAME>` same using checkout

## Pull Requests

- Also see branch delete above
- `git log --oneline --graph --all`: show you git history
- `git fetch --prune`: clean up your git history

## Conflicts

You won't know it's going to happen until it does.
- `git rebase <BRANCH>`: e.g., <MAIN> will update current branch
