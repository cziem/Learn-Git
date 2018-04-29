# Git commands

### This is a listing for major git shell line commands and what they do.

- ```git init``` -- Initializes a directory as a repository.
- ```git add``` -- Adds a file to the staging area ready to be committed. This can be said to mean tracking the file.
- ```git log``` -- Shows a log of all commits that have been made.
- ```git status``` -- Shows the status of the repository... all staged / tracked files are colored green, while the unstaged / untracked files are colored red.
- ```git branch``` -- Shows what branch you are currently working on.
- ```git branch <branch_name>``` -- Create a branch off the master branch with the provided branch name.
- ```git checkout``` -- It also shows all modified files which have not yet been staged (added to the staging area.)
- ```git checkout <branch_name>``` -- Switches you to the given branch name.
- ```git checkout -b <branch_name>``` -- The `-b` flag allows to create a branch and check into it in one command.
- ```git commit``` -- Commits all your staged files to the repository branch you are on. You also have to write a message before you can commit.
> If you are on a terminal, the ```git commit``` will bring you into the **nano** editor. All you have to do is write in your message and then press `ctrl`+`x` to quit the menu, but the menu raises a prompt to save the commit, just press `y` (yes) and press enter. Git makes the commit for you.

To make a faster commit, use this...
- ```git commit -m "Your message"``` -- The `-m` flag allows you to write your commit message on the fly.
- ```git clone <url address> or <dir>``` -- To clone a repository from the web to your local machine or from a given dir to your repository.
- ```git push origin master``` -- Push your repository to an online domain.
- ```git pull origin master``` -- Pull your repository from an online domain to your local machine.
- ```git remote``` -- Displays the remote name you are working with.
- ```git remote -v``` The `-v` flag shows more details about the address you are pushing to or pulling from.




