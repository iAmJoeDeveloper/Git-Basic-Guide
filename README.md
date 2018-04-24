# Git-Basic-Guide
Basic guide of commands of Git.

### Superlog
*git config --global alias.superlog "log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"*

## Reset

**git reset --soft**

git reset --soft sha-1


## Branchs
**Create branch**

git branch branchName



**Create and move to branch**

git checkout -b branch_name



**Move between branches**

git checkout master



**Delete a branch**

git branch -d branch_name



**Forced erasing**
git branch -D branch_name

*This command is used normally when the branch has commits inside her*



**See branches**

git branch -l



**Rename branch**

git branch -m branch_name new_name_branch


