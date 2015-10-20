# GitHub Tutorial

_by Luis Marin_

---
## Git vs. GitHub
__Git:__ Git is version control
 

__Github__:  Github stores your code in a cloud,in which you can   `pull` from any computer and `push` back to github so it can save your `commit`.  
It also allows for easy collaboration with other users, they can *fork* your repo and make their own changes and you can either accept or deny their pull requests, to accept or deny their changes to your repo.

 

---
## Initial Setup
_First steps:_  
1. Create a repository on github  
2. Then in any porgram on the command line type in `git init`  
3. Afterwards, type in `git config`  
4. It will show you a lists of commands in which you will type in `user.name(email) --global [insert name or email]`  
5. Then type in `git push -u [insert SSH/HTTPS url]` connect your computer to your repository on github then afterwards type in `git push` to send any commits back to your repository on github.
6. Once that is complete you must confirm that the program you are using is connected to the repository on github to `push` your changes back into the repository.




---
## Repository Setup

1. First, make sure you are in the correct directory to begin

2. Then type in `git init` to initialize git.

3. then make any changes you want to the file, or repository, then type in `git add [enter file name]`
* Or type in `git add .` to add all files changed to the "stage"


---
## Workflow & Commands
1. `git init` : initializes the git program.
2. `git add` : adds the changed files to the stage
3. type in `git status` to check what files you wish to add or that are changed
4. `git commit -m "enter message"` to save your changes and commit them so the next time you type in `git push` the changes will be added to your github repository
