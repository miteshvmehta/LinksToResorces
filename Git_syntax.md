# LinksToResorces
Links to various Resources

## Git Cheatsheet

|Task | Command | Notes | 
|--|--|--|
|Clone Repo|`git clone <url-git>`  https://github.com/miteshvmehta/LinksToResorces.git | Create a working copy of a local repository|
|New branch and switch branch|`git checkout -b <branchname>`|Create a new branch and switch to it|
|New branch name|`git branch -m <old-branchname> <new-branchname>`|Change a name of branch and switch to it|
|Check local branch status|`git status`|List the files you've changed and those you still need to add or commit|
|View Differences|`git diff` or  `git diff -r`|View all the merge conflicts and changes|
|Add files into the staging|`git add <filename>`|After you have manually resolved any conflicts, you add the changed file into the staging area|
|Add all files into the staging area|`git add .`|After you have manually resolved any conflicts, you add the changed files/code into the staging area|
|Commit a change|`git commit -m "<commit message>"`|Commits the changes in the staging area locally|
|Pull changes|`git pull`|Fetch and merge changes on the remote server to your working directory|
|Fetch changes|`git fetch`|Fetch only changes of remote into local dir does not merge|
|Delete a branch|`git branch -d <branchname>`|Deletes a branch in local|
|Merge branch|`git merge <branchname>`|To merge a different branch into your active branch|
|Push changes|`git push <branchname>`|Push the branch to your remote repository, so others can use it|
|Get local branch updated with the remote pull|`git pull origin <branchname>`|To fetch and auto-merged the remote with the local branch; cluttered commits|
|Squash commits without code changes|`git reset --soft head~<commits number behind to reduce>`, `git rebase -i HEAD~3`|reduce the commit history for the working branch without changing the code|
|Remove staged changes|`git reset --hard head`|removed the add the files from staging to unstaged area|
|Rebase the branch|`git rebase <branchname>` or `git pull --rebase`|Same as git pull but places the commits and current branch as HEAD.|
|Stash your changes|`git stash`|Stash your changes for later use in the branch|
|Unstash your changes|`git stash <stash name>`|Unstash your changes for using in the branch|
|Log for commit history|`git log`|Log for the commit history of current branch|
|Remove the directories|`git clean -f -d`|removes directories and delete files|
|Checkout/revert to the commit|`git checkout [commit hash]`|checks back to the commit id of that branch|
| | | |


## CSS Links
https://demos.scotch.io/visual-guide-to-css3-flexbox-flexbox-playground/demos/     
https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties    
https://philipwalton.com/articles/normalizing-cross-browser-flexbox-bugs/    
https://css-tricks.com/snippets/   
https://css-tricks.com/centering-percentage-widthheight-elements/   
http://benjaminjshore.info/     
http://chir.ag/projects/name-that-color/#6195ED   


## JS Links
https://lodash.com/docs/4.17.10    
http://numeraljs.com/
https://momentjs.com/    

