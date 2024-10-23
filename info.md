**GIT**
Git is a Version Control System (VCS) which is used to track changes in our file. It is open source and can be installed on our P.C. 


**GITHUB**
Github is a web-based hosting service for git repositories. It is an online platform that allows you to store code and share it with others. It a platform where developers can collaborate on projects and share code.


## DOWNLOAD GIT - 
https://git-scm.com/downloads. 

## GIT DOCUMENTATION - 
https://git-scm.com/docs

## GIT COMMANDS - 

<ol>
    <li>
        <b> Check git version :</b> 
        git --version
    </li>
    <li>
        <b> See the current state of your repository :</b>
        git status
    </li>
    <li>
        <b> Setup your email and username in this config file (globally) : </b>
        git config --global user.email "your_email"<br>
        git config --global user.name "your_username" (also we can use user.username)
    </li>
    <li>
        <b> To check git config settings :</b>
        git config --list
    </li>
    <li>
        <b> This command will create a new folder on your system and initialize it as a git repository. This adds a hidden .git folder to your project :</b>
        git init
    </li>
    <li> To add files : git add </li>
    <li> To commit files : git commit *-m* "message" </li>
    <li> To get logs : git log *--oneline* (shows only commit message, easier for reading)</li>
    <li> To change default code editor : git config --global core.editor "code --wait"</li>
    <li> To see all the branches : git branch</li>
    <li> To create a branches : git branch <branch-name></li>
    <li> To switch a branch : git switch <branch-name></li>
    <li> To create & switch a branch : git switch -c <branch-name></li>
    <li> To switch a branch : git checkout <branch-name></li>
    <li> To merge branch : git merge <branch-name></li>
    <li> To abort merge : git merge --abort</li>
    <li> To rename a branch : git branch -m <old_name> <new_name></li>
    <li> To delete a branch : git branch -d <branch_name></li>
    <li> Comparing Working Directory and Staging Area : git diff</li>
    <li> Comparing Staging Area with Repository : git diff --staged</li>
    <li> Comparing between branches : git diff <branch_one> <branch_two> (we can use .. instead of space)</li>
    <li> Comparing Specific Commits: : git diff <commit_hash_one> <commit_hash_two> (we can use .. instead of space)</li>
    <li> Comparing Specific Commits: : git diff <commit_hash_one> <commit_hash_two> (we can use .. instead of space)</li>
    <li> To save your changes in a temporary location : git stash</li>
    <li> To name your stash : git stash save "name"</li>
    <li> To list your stash : git stash list</li>
    <li> To apply your stash : git stash apply</li>
    <li> To apply a specific stash : git stash apply stash@{n}</li>
    <li> To apply and drop the stash : git stash pop</li>
    <li> To the stash : git stash drop</li>
    <li> To apply stash to a specific branch : git stash apply stash@{n} <branch_name></li>
    <li> To clear stash : git stash clear</li>
    <li> To create tag : git tag <tag_name></li>
    <li> To create a annotated tag : git tag -a <tag_name> -m "message"</li>
    <li> List all tags : git tag</li>
    <li> To tag a specific commit : git tag <tag_name> <commit_hash></li>
    <li> Push tags to remote repo : git push origin <tag_name></li>
    <li> Delete a tag : git tag -d <tag_name></li>
    <li> To rebase : git rebase <branch_name></li>
    <li> To resolve conflicts : git add <resolved-files> \n git rebase --continue <branch_name></li>
    <li> To view history of commits : git reflog</li>
    <li> For specifi commit  : git reflog <commit_hash></li>
    <li> Recover lost commits or changes : git reflog <commit_hash> \n git reset --hard <commit-hash> (or git reset --hard HEAD@{1})</li>



## GIT FILES - 
.gitignore - 
Gitignore is a file that tells git which files and folders to ignore. It is a way to prevent git from tracking certain files or folders. You can create a gitignore file and add list of files and folders to ignore.

.gitkeep -
Is is a file to track empty directories



GIT COMMIT : Commit is a way to save your changes to your repository. It is a way to record your changes and make them permanent.

**GIT FLOW**

- USUAL : 

WRITE -> ADD -> COMMIT

- COMPLETE

1. git init -> working dir
2. git add -> stagging area
3. git commit -> Repo
4. git push -> github


## REBASE : 
Git rebase is a powerful Git feature used to change the base of a branch. It effectively allows you to move a branch to a new starting point, usually a different commit, by “replaying” the commits from the original base onto the new base. This can be useful for keeping a cleaner, linear project history.


