# Git & GitHub

## Definitions

Git is a version control software, tracking changes made to source code.

GitHub is an online hosting service and sharing platform for Git repositories.

Git is the **tool** and GitHub is the **service** for projects that use Git.

GitBash is a way to use Git on Windows operating systems, providing an emulation layer for a Git command line environment.

## Main Commands

- $ pwd : Print working directory - shows the pathway to the current directory
- $ cd <directory> : change directory to a different directory
- $ ls / ls -a/ ll : list short/ list short -all/ list long - shows a list of local directories (can choose length of display)
- $ clear : clears the GitBash window
- mkdir <name> : make directory <name> - makes a new directory
- $ touch <file.extension> : makes a new file in the current directory
- $ cd ~ : goes to the top of the directory
- $ rm <file> : remove <file name> - removes file from directory
- $ rm -rf <directory> : remove directory through recursive force
- $ git remote git remote add origin git@github.com:<GitHub username/<repository name>.git : adds a remote connection to the repository from the directory of the name "origin"
- $ git remote --v : displays the status of the remote, whether or not it exists
- $ rm remote <remote name> -rf : removes a remote by recursive force
- $ git init : initialises the git tracking procedure, becoming the 'master' copy
- $ git add ./<file> : adds the altered version of the file to the working copy
- $ git commit -m "<detailed comment>" : commits the new file in the working copy to the master, with a comment on what changes were made, input by the user
- $ git push origin master : pushes the working copy to the repository using the remote
- $ git log : shows a log of the commits made in this session on that remote
- $ git status : gives a status of current commits that are ready to be pushed to the repository
- $ rm commit <commit code> : removes commits with code <commit code> obtained from git log, provided they haven't been pushed to repository
