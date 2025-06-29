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


Now to get a file that was created in GitHub not in the worspace.
1) create a file in GitHub.
2) Then just RUN: git pull