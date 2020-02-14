# git 
### basic 

`git init`: starts a git tracker project in your directory 

`git status`: check which files have changed/ are being tracked 

`git add .`: add all the files in the directory to the git tracker 

`git commit -m "message"`: commit tracked changes 

`git push origin master`: push to github 

note: the `.gitignore` file lets you add "ignored" files and directories. ALWAYS add "node_modules" to `.gitignore`
(if you use `create-react-app`, it will automatically add "node_modules" to `.gitignore` for you)

### intermidiate level 

`git chechkout -b branch-name`: make a new branch 

`git merge branch-name`: merge your current branch with branch-name 

### pulling 

`git pull` : check out a branch 

### cool stuff 

`git clone https://...`: clone someone else's repo

`git remote set-url origin https://...`:  change the remote URL to your own github repo 