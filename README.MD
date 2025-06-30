1) git config user.name "githubusername"
2) git config user.email "githubemail@gmail.com"
3) create a repository in github and create a file in it or Leave it Empty.
4) Now clone that repository with its link and clone it to our workspace.
    COMMAND To Clone: git clone https://github/clone/repository/link

5) The repository will be cloned.
6) Now create a new file in the cloned repository in the workspace.
7) At first the file will be having a "U" at its side and the file will be in green color.

8) RUN:    git status
    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        test.txt    ⬅️This means that this file was newly created and it needs to be updated in the repository.

9) To update that file RUN: git add test.txt
10) Now if we check the status by,
    RUNNING:    git status
        Changes to be committed:
        (use "git restore --staged <file>..." to unstage)
            new file:   test.txt

11) Now the newly created file is ready to be Updated in our repository.
12) Now commit the changes in the repository by,
    RUNNING:   git commit -m "Message to everyone who see the file in GitHub"

13) To finally push or save changes in our repository,
    RUN:    git push origin main


IN SIMPLER Terms:   INSERT -> ADD -> COMMIT -> PUSH


Now to get a file that was directly created in GitHub but not in VS CODE Workspace.
1) create a file in GitHub.
2) Then just RUN: git pull

To add a repository from the workspace:-
1) Manually create a new repository in github.
2) Now create a folder in Workspace with the same name with that repository.
3) now change directory to the newly created folder in Workspace using terminal: cd Current-Working-Directory
4) now RUN: git init
5) RUN : git add
6) RUN git commit -m "description"
7) Now we have to change the origin, because currently the origin is pointed to our old Working File.
8) To poin origin to new Working Directory. RUN: git remote add origin "link of new repository from github".

9) To check the branch of the director. RUN: git branch
10) To point the branch to "main". RUN: git branch -m main
11) Now push out Directory to github with: git push origin main

Ckecking and Creating a GITHUB BRANCH:-
1) To check all the available branches> RUN: git branch -a
2) Create a Branch manually in GitHub.
