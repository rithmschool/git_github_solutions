# Advanced Git Exercise

### Part I 

Answer the following questions:

- What is the difference between `git reset` and `git revert`. When would you use one over the other? **When working with others, git revert is much safer as it undoes a commit, but it also generates a new commit that undoes all of the changes introduced in a previous commit and applies it to the current branch. Git reset simply undoes a commit which can be difficult to reconcile when working with others**.
- What is the difference between `git merge` and `git rebase`. When would you use one over the other? **They are both essential when working on a team. Rebasing is helpful to maintain a cleaner commit history, but should never be done on a branch that has others working on it (since you can easily mess up their commit history)**.
- What is the difference between `git stash pop` and `git stash apply`. When would you use one over the other? **git stash pop will return the latest value from the stash, but will remove it. Git stash apply will return the latest value but still maintain it in the stash**.
- What kinds of things can you do in `interactive` mode when rebasing? **You can amend commit messages, edit commits, squash or combine commit messages, remove commits and even execute shell commands**

### Part II

It's time to practice some more with everything you have learned. 

- Create a local repository from the command line.
- Add and commit files.
- Push your repository up to GitHub.
- Fork and Clone [https://github.com/rithmschool/learn_forking](https://github.com/rithmschool/learn_forking).
- Add and commit some changes and submit a PR.
- Change to a different branch and add some files and merge into master when you are done.
- Practice using `revert` to undo commits and `rebase` with interactive mode for a better commit history.
- Submit another pull request, with squashed commits.

By now you should feel pretty comfortable working with Git, so push yourself to keep learning more! Start by reading the [Advanced Overview](https://www.atlassian.com/git/tutorials/advanced-overview/) on Atlassian and learn about the inner workings of Git and other advanced commands and flags that we have not shown you. Most of all, keep up the good work!