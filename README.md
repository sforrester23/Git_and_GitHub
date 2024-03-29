# Git & GitHub

## Definitions

Git is a version control software, tracking changes made to source code.

GitHub is an online hosting service and sharing platform for Git repositories.

Git is the **tool** and GitHub is the **service** for projects that use Git.

GitBash is a way to use Git on Windows operating systems, providing an emulation layer for a Git command line environment.

## Main Commands

- $ pwd : Print working directory - shows the pathway to the current directory
- $ cd <directory_name> : change directory to a different directory
- $ ls / ls -a/ ll : list short/ list short -all/ list long - shows a list of local directories (can choose length of display)
- $ clear : clears the GitBash window
- mkdir <directory_name> : make directory <name> - makes a new directory
- $ touch <file.extension> : makes a new file in the current directory
- $ cd ~ : goes to the top of the directory
- $ rm <file.extension> : remove <file name> - removes file from directory
- $ rm -rf <directory_name> : remove directory through recursive force
- $ git remote add <remote_name> git@github.com:<GitHub_username>/<repository_name>.git : adds a remote connection to the repository from the directory of name <remote_name>
- $ git remote --v : displays the status of the remote, whether or not it exists
- $ rm remote <remote_name> -rf : removes a remote by recursive force
- $ git init : initialises the git tracking procedure, becoming the 'master' copy
- $ git add ./<file_name> : adds the altered version of the file to the working copy
- $ git commit -m "<detailed_comment>" : commits the new file in the working copy to the master, with a comment on what changes were made, input by the user
- $ git push <remote_name> master : pushes the working copy to the repository using the specified remote
- $ git log : shows a log of the commits made in this session on that remote
- $ git status : gives a status of current commits that are ready to be pushed to the repository
- git clone REPO_SSH_ADDRESS : clones an existing repository 

## Git.ignore file

A git.ignore file tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as compilation products, temporary files IDEs create, etc.
