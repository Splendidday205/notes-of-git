# Basic work flow of git
1. Use `git init` to create a repo. Then you will be the master of this repo. If this repo is shared by a group of people. You may use `git checkout -b <you_branch>` to create a independent branch for yourself to develop with out affecting the Master.
2. If you have add some new changes to your branch, you can use `git add <filename>` to make your change to the to-be-commiteed list. Before you deecide to actually commit it, it is highly recommended that you use `git diff` to check the changes. If this is exactly what you want to do, `git commit` is the next thing to do.
3. use `git push origin <your_branch>` to make your changes sent to the remote repo.
4. use `git pull origin <branch>` to update your local repo if there are changes in the remote repo created by your workmates.
> [!NOTE]
> `git checkout <branch>` can only check your local repo instead of remote repo. If you want to update the local repo and your disk, use `git pull origin <branch>`






