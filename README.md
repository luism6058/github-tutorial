# GitHub Tutorial

_by Luis Marin_

---
## Git vs. GitHub
__Git:__ Git is version control
 

__Github__:  Github stores your code in a cloud,in which you can   `pull` from any computer and `push` back to github so it can save your `commit`.  
It also allows for easy collaboration with other users, they can *fork* your repo and make their own changes and you can either accept or deny their pull requests, to accept or deny their changes to your repo.  

 

---
## Initial Setup:
_Github Account_:  
1.Create a [github](https://github.com) account to make your repositories and your remotes.  
2.Once you create your github account you go to "Your Profile" and click on the repositories tab.  
3.Once in the repositories tab, click on "New" and type in the name for the repository and then you can begin!
4. Endless Fun!

_First steps:_  
1. Create a repository on github  
2. Then in any porgram on the command line type in `git init`  
3. Afterwards, type in `git config`  
4. It will show you a lists of commands in which you will type in `user.name(email) --global [insert name or email]`  
5. Then type in `git push -u [insert SSH/HTTPS url]` connect your computer to your repository on github then afterwards type in `git push` to send any commits back to your repository on github.
6. Once that is complete you must confirm that the program you are using is connected to the repository on github to `push` your changes back into the repository.




---
## Repository Setup

1.Make sure you are logged in on github.  
2.Click on your profile 
3. Click "Your Profile" 
4. Create a new one or continue from an old one
5. connect your program to github.



---
## Workflow & Commands
1. `git init` : initializes the git program.
2. `git add` : adds the changed files to the stage
3. type in `git status` to check what files you wish to add or that are changed
4. `git commit -m "enter message"` to save your changes and commit them so the next time you type in `git push` the changes will be added to your github repository
