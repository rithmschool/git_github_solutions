# Git Branching + Merging Exercise

### Part I 

Answer the following questions:

- What does `git clean` do? **git clean removes files that have not been staged yet**
- What do the `-d and -f` flags for `git clean` do? **Remove untracked directories in addition to untracked files. If an untracked directory is managed by a different Git repository, it is not removed by default. Use -f option twice if you really want to remove such a directory.**
- What `git` command creates a branch? **git checkout -b**
- What is the difference between a fast-forward and recursive merge? **fast forwards can only happen if there have not been commits on the original branch while the new branch is being worked on**
- What `git` command changes to another branch? **git checkout**
- How do you remove **modified or deleted** files from the working directory? **git checkout**
- What `git` command deletes a branch? **git branch -D**
- What does the `git diff` command do? **shows you a difference between two different commits**
- How do you remove files from the staging area? **git reset HEAD name_of_file** or **git rm --cached name_of_file**
- How do merge conflicts happen? **When Git can not determine what file or folder to choose when merging since there have been different commits with changes to the same file**

### Part II

Create your own merge conflict! Work on the same file on two separate branches and merge the two branches together. Fix the conflicts and finish your merge. In the real world you will never intentionally try to create merge conflicts, but it is important to understand how and why they are created. Most importantly, it's important not to be intimidated by merge conflicts, and to be able to fix them with confidence!