Sample Git Project
Created the readme.md using touch README.md
Followed by cmd - git init

git add .  
----> Adds all the files in the local repository and stages them for commit

OR if you want to add a specific file

git add README.md 
----> To add a specific file

git status 
----> Lists all new or modified files to be committed

git commit -m "First commit"
----> The message in the " " is given so that the other users can read the message and see what changes you made

Uncommit Changes you just made to your Git Repo:
Now suppose you just made some error in your code or placed an unwanted file inside the repository, you can unstage the files you just added using:

git reset HEAD~1
----> Remove the most recent commit
----> Commit again!

For the first Time
git remote add origin remote_repository_URL
----> sets the new remote

git remote -v
----> List the remote connections you have to other repositories.

git push -u origin master 
----> pushes changes to origin