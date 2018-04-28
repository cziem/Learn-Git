# Setting up the Git environment

> Follow the steps below

- Open your terminal `Ctrl` + `Alt` + `T`
- Make sure you are in the root `cd` + `~` and press enter.
- Type in the commond in the prompt ```sudo apt-get install git-core```
- Check out the version of your git ```git --version```

Now you are ready to use git in the shell. So go on and create a test directory named **test**, cd into it and create some files.

> Git commands

- Run ```git init``` to initialize the directory as a git project.
- Run ```git add <filename>``` to add your file to the staging area. *more on staging later*
- Run ```git status``` to see what is happening.
- Run ```git commit``` to make your first commit. Commits are messages that tell what you've done on a particular step.

You can always check what changes you've made.

### Changes in the Commit 

Changes in the commit can be checked with the ```git diff id1 id2```
To get the `id1` and `id2` type in `git log`
The *git log* command will display a log of commits, authors, ids and message. The id is what you are looking for, so you copy it with `shift`+`ctrl`+`c` and then paste it on the prompt. `$` with `ctrl`+`shift`+`v`


