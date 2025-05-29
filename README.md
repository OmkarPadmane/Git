Git 

- git init: It initializes a new Git repository in your current directory. It creates a hidden .git folder where Git will store all the history, versions, and configurations for your project.

- git status: It tells you the current state of your working directory and staging area. It shows you which files are new, modified, or deleted, which files are staged for the next commit, and which are untracked.

- git add f_name: It stages the specified file for the next commit.  

- git status: Shows the current status of the repository, including tracked, untracked, and modified files.

- git commit f_name -m "first file" :
This command saves the staged changes into the repository's history. The -m flag lets you add a commit message ("first file"), which is a short description of what changes you made in this particular save point.

- git remote -v:  This command lists the remote repositories that your local repository is connected to. The -v flag shows you the URLs for both fetching (downloading) and pushing (uploading) data.

- git remote set-url origin https://github.com/abc/Git.git : This command set the URL for an existing remote repository to your local repo.

- git push origin master
This command uploads your committed changes from your local master branch to the master branch of the remote repository. This makes your local commits available on the remote server (e.g., GitHub).

- git config --global credential.helper store :
This command configures Git to store your credentials (username and password/Personal Access Token) on your computer. The store helper saves them in plain text in a file on your system, so you don't have to enter them every time you push or pull.

- git branch: This command lists all the branches in your local repository. 

- git branch dev : This command creates a new branch named dev in your local repository. It is used to start working on a new feature or fix without affecting your main codebase.

- git checkout dev: This command switches your active branch to dev. Your working directory will now reflect the files and commits of the dev branch.

- git merge dev: It integrates changes from the dev branch into your current branch. So, if you were on master and ran git merge dev, all the changes from dev would be brought into master.

- git clone: This command copies an entire remote repository to your local machine. It creates a full local copy, including all branches and commit history.
