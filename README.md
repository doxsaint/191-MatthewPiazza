This repository was created as an exercise following multiple guides

#[Git Kata: 3-Way Merge](https://github.com/praqma-training/git-katas/tree/master/3-way-merge)

step 8:
* cba1464 (HEAD -> master) Added README.md
* 02cedff (greeting) Added greeting.txt

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

