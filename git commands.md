#git commands

git --version || check if git exist in our machine and the version if it is the latest as said in git-scm.com

|| for configuration - who you are making these changes in repositories

git config --global user.name "yourname"
git config --global user.email "youremail"
git config --global core.editor "code --wait" ||make vs code default editor
git config --global -e ||open vs code to edit global git setting
git config --global core.autocrlf true or input ||if you use window set true if mac set input

|| initializing project

git init || this will make your directory a repository which means git will track any changes
