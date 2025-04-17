# Git Command Notes

## Reword previous commits
* `git rebase -i HEAD~n`
    * ex: `git rebase -i HEAD~2`
[reword]
* remove lines you don’t want to update
* `git push —force origin <branch>`

## Undo last commit
`git reset head~[n]`\
`git push —force`\
`git push -u origin HEAD`

## Reset branch to head (origin)
`git reset --hard origin/mybranch`

## Track remote branch:
`git fetch origin`  - Get current state\
`git branch -v -a`  - Lists branches\
`git switch -c {branch name} origin/{branch name}`
