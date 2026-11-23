#Git Starting

1. Open the VS code 
2. Press Control +J - Open the terminal
3. Check the git version - git --version

#Git configuration checking
#set the username
git config --global user.name "Manju Srinivasan"  

#email config
git config --global user.email "manjusriniv9@gmail.com" 
# command to keep always default main defaultBranch
git config --global init.defaultBranch main 
# config the editor for git commands even the error message
git config --global core.editor "code --wait" 

#check the config list
git config --global --list

#Download the latest information from the git
git fetch


#git commnands to know

git status #what's changed in repo
git init #start a repo
git clone # copy from github
git add #stage for commit
git commit -m "message" # save a snapshot
git log --oneline #history
git diff #unstaged
git diff --staged # staged changes
git restore  <file> # discard edits
git restore --staged <file> #unstage
git push/pull @ upload /Download