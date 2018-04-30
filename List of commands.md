# Git commands

### This is a listing for major git shell line commands and what they do.

- ```git init``` -- Initializes a directory as a repository.
- ```git add``` -- Adds a file to the staging area ready to be committed. This can be said to mean tracking the file.
- ```git log``` -- Shows a log of all commits that have been made.
- ```git log --oneline``` -- Shows the commit ids and commit messages in the log history. It abstracts the author information, and oh... it displays these informations on one line at a time.
- ```git log --stat``` -- Shows the log history with attention drawn to what changes were made to the files.
- ```git log -p (--patch)``` -- Shows the log history with the actual code changes that were made and which lines they occur. Added lines of code are colored green while removed lines of code are red colored.
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
- ```git remote -v``` The `-v` flag shows more details about the address you are pushing to or pulling from
- ```git remote add <remote name (origin)> <url>``` -- Use this to add a remote to your repository.
- ```git show``` -- This command works like the ```git log -p``` already introduced at the beginning of this lesson.
- ```git tag <tag name>``` -- Used to add tags to commits to make them easier to track and remember. Think of tags as sign posts or callouts that give direction. You really don't want to tag all of your commits.
- ```git merge <branch_name1> <branch_name2>``` -- This merges the changes in one branch into the second parameter branch provided, usually it is the master.
> PS: Note that git will not merge two branches if they are conflicting. That is to say if sames lines of the branches to be merged were modified, git wouldn't know which line is correct or suitable for your code. So I would walk you through conflict resolution in this lesson [Conflict Resolution and Merging](https://github.com/phavor/Learn-Git/blob/master/lesson5.md). 

- ```git checkout <file_name>``` -- This removes a file from the staging index... Think of it as removing what you wouldn't want to commit into your repo.




