
# 1. git config --global user.name "Krishnakumar3k"
# 2. git config --global user.email "--------------"
# 3. git config --global core.editor "code --wait"
# 4. git config --global core.autocrlf "input"



 # 5. git log --oneline => To know  current status of saved points.
                K:\MERN STACK PROJECT\Git-Github> git log --oneline
                3e9d75f (HEAD -> main) 27 jan test 1030
                0297041 code now 04:56
                ff94b20 (origin/main) new
---------------------------------------------------------------------------------------------------
# 6. git reset --hard HEAD~1
- git reset --hard HEAD~1 moves the current branch one commit back and permanently discards the latest commit along with all its changes from the working directory and staging area.
# 7. git reflog 
- (Recovery) git reflog  If you did this by mistake:

-------------------------------------------------------------------------
## Status and Logs - 
# How to do initialize ? --------
# 7. git status -s
 - By using git cmd we can check which files on which stages 
# 8. git log --oneline   OR git log --oneline --graph
 -  Also we can do check how many checkpoint is that
 -