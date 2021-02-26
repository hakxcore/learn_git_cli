<p align="center">
  <img src="https://raw.githubusercontent.com/hakxcore/learn_git_cli/main/media/github.png" width="200" height="200"/>
</p>
<p align="center">
<a href="#"><img title="git_cli" src="https://img.shields.io/badge/-%20LEARN GIT CLI-green%3FcolorA%3D%2523ff0000%26colorB%3D%2523017e40"></a>
</p>
<p align="center">
  <a href="https://wa.me/+916006511429"><img title="Whatsapp" src="https://simpleicons.org/icons/whatsapp.svg" width="50" height="50"></a>
</p>
<p align="center">
<a href="https://github.com/hakxcore"><img title="Author" src="https://img.shields.io/badge/Author-mukesh%20kumar-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/hakxcore/followers"><img title="Followers" src="https://img.shields.io/github/followers/hakxcore?color=blue&style=flat-square"></a>
<a href="https://github.com/hakxcore/learn_git_cli/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/hakxcore/Anonymous?color=red&style=flat-square"></a>
<a href="https://github.com/hakxcore/learn_git_cli/network/members"><img title="Forks" src="https://img.shields.io/github/forks/hakxcore/Anonymous?color=red&style=flat-square"></a>
<a href="https://github.com/hakxcore/learn_git_cli/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/hakxcore/Anonymous?label=Watchers&color=blue&style=flat-square"></a>
<a href="#"><img title="UNMAINTENED" src="https://img.shields.io/badge/UNMAINTENED-YES-blue.svg"</a>
</p>
         
# learn_git_cli

Please correct the mistales if any <3

GITHUB COMMANDS FOR BEGINNERS



```bash
> git init //To initialize the dir to git//
> git remote add origin <url to your github account> #//to create a new repo//
> git config --global user.name "name_of_user" #//To register a user on github//
> git config --global user.email "user_email@xyz" #//To register an email address of the user//
> git config --global core.editor Vim #//To select a different test editor//
> git config --global color.ui true  #//You can customize your Git output to view a personalized color theme//
> git status  #//check the status of git//
> git clone <url to your repo> #//To clone a repository form github//
> git pull origin #//To pull a whole doc or repo from github//
> git branch  <branch name> #//create a new branch.//
> git branch --list or  git branch  #//list all branches//
> git branch -d <branch name>  #//Delete a branch.//
> git push origin -delete <branch name>   #//You can delete a remote branch from Git desktop application.//
> git checkout <branch name> #//Git allows you to switch between the branches without making a commit.//
> git branch -m master #//Switch to master branch//
> git branch -m <old branch name> <new branch name> #//rename the branch with the help of the git branch command.//
> git merge <branch name> #//merge the other branch with the currently active branch.//
> git add newfile.txt #//to add a new file to a repo//
> git commit -m "Your message here" #//commit for the file for changes//
> git commit --ammend #//Overwrite the previous commit//
> git log --oneline #//checkout the log history//
> git log -1 #//show top commit//
> git log -2 #//show 2nd commit from top//
> git log --oneline #//show all commits in oneline//
> echo "# wish-happynewyear" >> README.md #//Write text to file manually//
> git push origin #//To push all the changes you have madded to the remote repo or to github//
> git fetch #//to fetch all the changes madded in the local repo//
> git merge #//to merge all the changes maded//
```

## My Notes :)

1. git config --global user.name "name_of_user" //To register a user on github//
2. git config --global user.email "user_email@xyz" //To register an email address of the user//
3. git config --global core.editor Vim //To select a different test editor//
4. git config --global color.ui true  //You can customize your Git output to view a personalized color theme//

5. git clone <link_for_repo>
6. git status  //check the status of git//

         ##############GIT BRANCH COMMANDS################
5. git branch  <branch name> //create a new branch.//
6. git branch --list or  git branch  //list all branches//
7. git branch -d<branch name>  //Delete a branch.//
8. git push origin -delete <branch name>   //You can delete a remote branch from Git desktop application.//
9. git checkout <branch name> //Git allows you to switch between the branches without making a commit.//
10. git branch -m master //Switch to master branch//
11. git branch -m <old branch name><new branch name> //rename the branch with the help of the git branch command.//
12. git merge <branch name> //merge the other branch with the currently active branch.//
13. git add newfile.txt //to add a new file to a repo//
14. git commit -m " new commit made on the master branch." //commit for the file for changes//
15. git commit --ammend //Overwrite the previous commit//
16. git log --oneline //checkout the log history//
17. git log -1 //show top commit//
18. git log -2 //show 2nd commit from top//
19. git log --oneline //show all commits in oneline//


`
 --global
The global level configuration is user-specific configuration. User-specific means, it is applied to an individual operating system user. 

--system
The system-level configuration is applied across an entire system. The entire system means all users on an operating system and all repositories. The system-level configuration file stores in a gitconfig file off the system directory.
`


1. echo "# wish-happynewyear" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin https://github.com/hakxcore/wish-happynewyear.git
7. git push -u origin main

8 .git remote add origin https://github.com/hakxcore/wish-happynewyear.git //to create a new repo//
9. git branch -M main
10. git fetch //to fetch all the changes madded in the local repo//
11. git merge //to merge all the changes maded//
12. git push -u origin main
