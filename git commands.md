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

|| workflow  

git status || show untracked or staged files that are changed  
git add fileName || to add files to stage area  
git commit =m "your message here" || to commit changes and create a snapshot of files  
git commit -a -m "yout message here" || to commit all without staging them   
git rm filename || removing file in directory and staging area  
git mv aFilename to thisFilename || renaming files  
git diff || see changes of files contents  
git diff --staged ||see changes of files contents that are staged  
git log || to see history of the commits  
git show commit-hash || to see what has changed in this commit  
git show head~2 || to see what has changed in 2 commits before  
git show head~2:fileAdress || to see what has changed in a file in 2 commits before  
git restore --staged fileName || get a file changes out of the stagged area  
git checkout commit-hash || this will go back to a commite for you to checkout  
git checkout master || this will go to the last commit in master branch make it the head  

|| branches  

git branch || list all the branches  
git branch branchName || create another branch called branchName  
git checkout branchName || to move to another branch  
git merge branchName || to merge and bring all code from branchName to current branch  
git -d branchName || to delete a branch if it already has been pushed and merged with the remote branche  
git -D branchName || to delete a branch no matter what  
 
