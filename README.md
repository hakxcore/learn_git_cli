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

Please correct the mistakes if any 
<hr/>
<p align="center"><strong>GIT COMMANDS</strong></p>
<hr/>

## Git configurations

```bash
> git init To initialize the dir to git
> git remote add origin <url to your github account> #to create a new repo
> git config --global user.name "name_of_user" #To register a user on github
> git config --global user.email "user_email@xyz" #To register an email address of the user
> git config --global core.editor Vim #To select a different test editor
> git config --global color.ui true  #You can customize your Git output to view a personalized color theme
``` 

 <p>--global</p>
The global level configuration is user-specific configuration. User-specific means, it is applied to an individual operating system user. 
<br>
<br>
<p>--system</p>
The system-level configuration is applied across an entire system. The entire system means all users on an operating system and all repositories. The system-level configuration file stores in a gitconfig file off the system directory.
<hr/>

<br>
<br>

## Git creating a repository

```bash
> git init #To initialize a repository or dir to git
> git status  #check the status of git
```
<hr/>
<br>
<br>

## Git staging the files

```bash
> git add newfile.txt #to add a new file to a repo
> echo "# Dubby Dubby Dub" >> README.md #Write text to file manually
> git add .
> git add --all
> git add -A
> git add <file-name>
> git add <file-name> <another-file-name> <and-another-file-name>
> git rm --cached <file-name>
> git reset <file-name>
```
<hr/>
<br>
<br>

## Git pulling and cloning the repository

```bash
> git clone <url to your repo> #To clone a repository form github
> git pull origin #To pull a whole doc or repo from github
```

<hr/>
<br>
<br>

## Git pushing the repo to the remote server

```bash
> git remote add origin <link>
> git push origin #To push all the changes you have maked to the remote repo or to github
> git push origin -delete <branch name>   #You can delete a remote branch from Git desktop application.
``` 
<hr/>
<br>
<br>

## Git branching

```bash
> git branch  <branch name> #create a new branch.
> git branch --list or  git branch  #list all branches
> git branch -d <branch name>  #Delete a branch.
> git checkout <branch name> #Git allows you to switch between the branches without making a commit.
> git branch -m master #Switch to master branch
> git branch -m <old branch name> <new branch name> #rename the branch with the help of the git branch command.
> git merge <branch name> #merge the other branch with the currently active branch.
```
<hr/>
<br>
<br>

## Git committing 

```bash
> git commit -m "Your message here" #commit for the file for changes
> git commit --ammend #Overwrite the previous commit
> git log --oneline #checkout the log history
> git log -1 #show top commit
> git log -2 #show 2nd commit from top
> git log --oneline #show all commits in oneline
```
<hr/>
<br>
<br>

## Others

```bash
> git fetch #to fetch all the changes madded in the local repo
> git merge #to merge all the changes maded
```

<hr/>

`

`
