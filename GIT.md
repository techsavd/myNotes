1. To add all tracked files to the staging area use :git add -u
2. To record a merge conflict resolution use git rerere. To enable it use :git config rerere.enabled true
   Next time the same conflict is encountered, git will automatically apply it. You can view the diff of a merge with :git rerere
3. To switch between the previous branch you were on and the current branch use : git checkout -   
4. To rename a branch, while you are on that branch: git branch -m <new_branch_name>
5. To change the default editor where the git merge  message opens in use: update .gitconfig file and have editor = <your editor>
6. In order to garbage collect in git use: git gc
