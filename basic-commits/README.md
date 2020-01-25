This repository was created as an exercise following multiple guides

[Git Kata: Basic Commits](https://github.com/praqma-training/git-katas/tree/master/basic-commits)

1. git status
```
On branch master
Your branch is up to date with 'origin/master'.
```
2. git log
```
Author: Matthew Piazza <m21career@gmail.com>
Date:   Fri Jan 24 15:46:42 2020 -0800

    Added to README.md

commit cba14642a0d1d67cdc3ee252d8fb4eaa0dabf01c
Author: Matthew Piazza <m21career@gmail.com>
Date:   Fri Jan 24 15:42:30 2020 -0800

    Added README.md

commit 02cedff1f52726b74cb00267cc04ca81da7c5b06 (greeting)
Author: Matthew Piazza <m21career@gmail.com>
Date:   Fri Jan 24 15:39:39 2020 -0800

    Added greeting.txt
```
3. create a file
4. git status
```
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        file.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
5. git add {file}
6. git status
```
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   file.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md
```
7. commit file.txt
8. git status
```
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```
9. edit file.txt
10. 
```
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md
        modified:   file.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
11. git add file.txt
12. git status
```
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   file.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md
```
13. edit file.txt
14. git commit -m ...
15. git status, git log --oneline --graph --all
```
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md
        modified:   file.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
```
* d0f5068 (HEAD -> master) Updated file.txt
* fba75f5 Created file.txt
* 448c974 (origin/master) Added to README.md
* cba1464 Added README.md
* 02cedff (greeting) Added greeting.txt
```
16. commit
