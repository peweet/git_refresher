git reset --soft HEAD-1 - go back one commit

git init 
git status
git log
git ls-files

git add . 
git commit -m "message"

git branch -a -> See all branches (remote & local)

undo unstaged changes only in working directory:
reverts changes in tracked files
git checkout -- .
git restore filename or .

delete untracked files
git git clean -df (force delete)

undo staged canges

git reset filename & 
git checkout -- fimename
git restore --staged filename or .

Latest commits (undo latest commits -1
git reset --soft HEAD~1
git reset --hard HEAD~1

git ls-remote -> see all remote branches

git branch -a list all branches
git branch -r show remote tracking branches

git remote show origin -> show detailed configuration

git branch -vv list local tracking branches and their remotes

git stash apply -> temp storage for unstaged and uncommited chnages

git reglog -> a log of all project chaange included deleted commits

git switch -c

git merge --no-ff
no fast forrward merge

git diff
git rebase
