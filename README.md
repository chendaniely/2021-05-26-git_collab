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

# Some additional notes and links

- Software Carpentry notes on basic git: https://swcarpentry.github.io/git-novice/
    - The setting up git has the commands to setup your name/email/editor: https://swcarpentry.github.io/git-novice/02-setup/index.html

- Git workflow notes and commands (to paste on your wall)
    - https://chendaniely.github.io/training_ds_r/help-faq.html

- Atlassian page on git workflows: https://www.atlassian.com/git/tutorials/comparing-workflows
    - The one we covered today was mainly the "Feature Branch Workflow": https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

- The atlassian page has more infor about "git flow", but this is also another top Google hit that I liked:
  - https://nvie.com/posts/a-successful-git-branching-model/

- Getting your (bash) terminal to show current path and other things:
    - Use this to create your PS1 variable: http://bashrcgenerator.com/

- Show git branch in terminal:
    - In addition you can write a function and put that in your PS1 to also show git branch
    - https://gist.github.com/joseluisq/1e96c54fa4e1e5647940
    
- Video I did with more forking related workflow: https://www.youtube.com/watch?v=uvWhSYBkZJ0

- Setting up ssh links: https://bi-sdal.github.io/training/ssh-keys.html
- https://happygitwithr.com/ (more rstudio specific workflows)

