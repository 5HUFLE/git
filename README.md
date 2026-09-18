# git

# git add (you added the new file in the repo but git doesnt know about it so you do git add filename to add it in tracking mode or git add .)

# git commit -m (after add you can save the changes to your local repository/ local pc using git commit -m "the changes you made")

# git push origin main (if you want to push the changes to online/github, you use git push, where **origin** is the link you cloned from and **main** is the name of the branch you want to push your code to)

# git push -u origin main (if you dont want to write git push origin main every time, you can create an upstream using -u which makes the push default to origin main, so you can just write git push from next time on)

# git init (if you created a new folder locally for your own project then you can first make git track it using git init)

# git remote add origin <-link-> (this will sync your local project to the repo you created and sets your origin to the link you put)
# git remote -v (to verify remote)

# BRANCHES IN GIT

# git branch (to check branch name)
# git branch -M <-branchname-> (to rename a branch name, this renames whatever branch you are in to branchname)
# git switch <-branchname-> (to switch to a different branch )
# git checkout -b <-branchname-> (to create a new branch, and you will be moved into that branch as well)
# git checkout -d <-branchname-> (to delete the branch)

# MERGING CODE IN GIT

# git diff <-branchname-> (check the diff between the current branch and the branchname )
# git merge <-branchname-> (merge the the code changes from branchname to your current branch)

# git pull origin main (to download the content from github to the local repo)

# UNDOING CHANGED
# FOR FOR ADDED NOT COMMITTED FILE
# git reset <-filename-> (to reset the file that has been added but not committed)
# git reset (to reset all the files)

# FOR COMMITTED FILE (most recent)
# git reset HEAD~1

# FOR COMITTED FILE (for many commits)
# git reset <-commitHash-> (commit hash is the commit you want to go to, you can find it in the git log)
# git reset --hard <-commitHash-> (to change the code itself inside vscode to the hash version)