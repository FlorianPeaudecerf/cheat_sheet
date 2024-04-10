# GIT CHEAT SHEET ![curl -o badge.svg](https://img.shields.io/badge/GIT%20%20-orange?style=for-the-badge&logo=git)
## SETUP :  
| command |description |
|:-----------:|---------|
| ```git config --global user.name “[firstname lastname]”```            | set a name that is identifiable for credit when review version history        |
|   ```git config --global user.email “[valid-email]”```          |set an email address that will be associated with each history marker         |
|```git config --global core.editor subl```             |         |
| ```git config --global merge.tool filemerge```            |         |
|```git config --global color.ui auto```|set automatic command line coloring for Git for easy reviewing|
## SETUP & INIT
| command | description |
|:-------:|-------------|
|```git init```      |initialize an existing directory as a Git repository             |
|```git clone [url]```         |retrieve an entire repository from a hosted location via URL             |
## STAGE & SNAPSHOT
| command | description |
|:-------:|-------------|
|```git status```         |show modified files in working directory, staged for your next commit             |
|```git add [file]```         |add a file as it looks now to your next commit (stage)             |
|```git reset [file]```         |unstage a file while retaining the changes in working directory             |
|```git diff```         |diff of what is changed but not staged             |
|```git diff --staged```         |diff of what is staged but not yet committed             |
|```git commit -m “[descriptive message]”```         |commit your staged content as a new commit snapshot             |
## BRANCH & MERGE :
| command | description |
|:-------:|-------------|
|```git branch```         | list your branches. a * will appear next to the currently active branch            |
|```git branch [branch-name]```         |create a new branch at the current commit             |
|```git checkout```         |switch to another branch and check it out into your working directory             |
|```git merge [branch]```         |merge the specified branch’s history into the current one             |
|```git log```         |show all commits in the current branch’s history             |
## INSPECT & COMPARE
| command | description |
|:-------:|-------------|
|```git log```         |show the commit history for the currently active branch             |
|```git log branchB..branchA```         | show the commits on branchA that are not on branchB            |
| ```git log --follow [file]```        | show the commits that changed file, even across renames            |
|```git diff branchB...branchA```         |show the diff of what is in branchA that is not in branchB             |
|```git show [SHA]```         | show any object in Git in human-readable format            |
## TEMPORARY COMMITS
| command | description |
|:-------:|-------------|
|```git stash```         | Save modified and staged changes            |
|```git stash list```         |list stack-order of stashed file changes             |
|```git stash pop```         |write working from top of stash stack             |
|```git stash drop```         | discard the changes from top of stash stack            |
## SHARE & UPDATE
| command | description |
|:-------:|-------------|
|```git remote add [alias] [url]```         |add a git URL as an alias             |
|```git fetch [alias]```         | fetch down all the branches from that Git remote            |
|```git merge [alias]/[branch]```         |merge a remote branch into your current branch to bring it up to date             |
|```git push [alias] [branch]```         |Transmit local branch commits to the remote repository branch             |
|```git pull```       | fetch and merge any commits from the tracking remote branch          |
## TRACKING PATH CHANGES
| command | description |
|:-------:|-------------|
|```git rm [file]```         | delete the file from project and stage the removal for commit            |
|```git mv [existing-path] [new-path]```         |change an existing file path and stage the move             |
|```git log --stat -M```         |show all commit logs with indication of any paths that moved             |
## REWRITE HISTORY
| command | description |
|:-------:|-------------|
|```git rebase [branch]```         |apply any commits of current branch ahead of specified one             |
|```git reset --hard [commit]```         | clear staging area, rewrite working tree from specified commit            |
## IGNORING PATTERNS
| command | description |
|:-------:|-------------|
|```git config --global core.excludesfile [file]```      |system wide ignore pattern for all local repositories             |
|```logs/.notes pattern/```         |  Save a file with desired patterns as .gitignore with either direct string
matches or wildcard globs.
## ANOTHER COMMANDS 
| command | description |
|:-------:|-------------|
|   git cherry-pick <hash-du-commit>      |  Is a command used in Git to apply a specific commit from one branch onto another branch           |
|         |             |
|         |             |
### ⚠️Always commit before pushing/pulling or switching branches.


### 🚨Staging area : 
It's the area where you can add changes.
