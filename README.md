# Git_Basics

Getting started with Git and Github (bare minimum)

### Resources:
1.https://www.youtube.com/watch?v=SWYqp7iY_Tc
2.http://rogerdudler.github.io/git-guide/
3.https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf
4.https://help.github.com/articles/git-and-github-learning-resources/

### Recorded terminal sessions:

Recorded Terminal Sessions are stored as .cast files.
To play 'em
		&nbsp; &nbsp;1.View these .cast videos online at [asciinema.org](https://asciinema.org/~sharansundar).
                &nbsp; &nbsp;2.For installing asciinema  -  [installation](https://asciinema.org/docs/installation)(apt-get for Ubuntu).
                &nbsp; &nbsp;3.Open terminal and type -  **asciinema play filename.cast**.


### Setting up git
https://help.github.com/articles/set-up-git/


#### Local Repo Operations
1. *cd project_folder*
2. *git init* - Initializes Local Repo - .git hidden folder appears.
3. *git add <filename>,rm --cached files* - Add files to staging(git add . to add all files).
4. *git status*  - Reports files that have changed.
5. *git commit* - Goes to vim,nano editor kind of mode.
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; * *Vim* - Press I for insert mode and type in commit message. Esc+:wq takes you out.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *  *Nano* - Ctrl+X and Enter.
*git commit -m "Message"* to skip all the vim,nano stages.
6. *.gitignore* - Folder/Document that contains filenames to be ignored.
&nbsp;&nbsp;&nbsp;&nbsp;*touch .gitignore* - Open it and put all filenames which have to be ignored.


#### Branches
1. *git branch branchname* - To create a new branch.
2. *git checkout branchname* - To switch branches.
3. *git merge branchname* - To megre branch with master.
4. Make changes in branches and merge finally with the master branch.


#### Remote Repo-github

1. Create repo in github - Try .edu accounts
2. *git remote add origin 'url'* - Add remote repo with 'url' being the 'Clone with HTTPS' on the repo in github.
3. *git push -u origin master* - To push contents from local repo to remote repo
4. *git pull origin master* - To reflect changes made by others contributors on your local repo.

