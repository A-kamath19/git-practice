## Git Help
1. To display all the information about git <br>
`git help`
2. To display more specific git commands <br>
`git help -a` / `git help --all`

## Setup Git credentials for Git config
1. To set user's username in Git config <br>
`git config --global user.name "Username"`
2. To set user's email in Git config <br>
`git config --global user.email "EmailiD"`
3. To view the complete list of setting in Git Config<br>
`git config --list`

## Git repository
1. To initialise a git repository<br>
`git init`
2. To create a new file<br>
`touch <filename with extension>`
3. To check whether we linked our repository or not<br>
`git remote`/ `git remote -v`

## Directory Commands
1. Browse to the desired Directory in Git Bash<br>
`cd <path of directory>`
2. Create a New Directory using Git Bash<br>
`mkdir <folder name>`
3. to View all the Directories in Git Bash<br>
`ls`
4. Delete a directory<br>
`rmdir <folder name>`
5. To view content of directory along with hidden files<br>
`dir /ah`
6. To create a directory with more than one-word name, enter the name in quotes else two separate directories will be created.

## Clone a Repository
`git clone <URL>`

## Git Status
This command returns information about the current state of the repository. For e.g. a list of files changed, list of tracked changes on staging, untracked changes on local, and information about current branch & commits.<br>
`git status`

## Alter files in Git
1. To remove files<br>
`git rm <filename>`
2. To rename a file in git<br>
`git mv <original_file_name> <new_file_name>`

## Git Branch
1. To view local branches in Git<br>
`git branch`
2. To check all the branches (including remote branches)
`git branch -a`
3. To create a branch<br>
`git branch <branch_name>`
4. To switch branch<br>
`git checkout <branch_name>`
5. To Create and Switch a branch with a single Git command<br>
`git checkout -b <name_of_branch>`
6. To rename a branch<br>
`git -m <old_name> <new_name>`
7. To delete a branch<br>
`git branch -d <branch_name>`
8. To delete a remote branch<br>
`git push <remote_repo_name> --delete <branch_name>`
9. To recover the deleted branches<br>
`git reflog`
10. To merge a branch<br>
`git merge <branch_name>`

## Git commit
To restore from commit:
1. When the last commit is not the initial commit - No changes. i.e. execute:<br>
`git reset HEAD~`
2. When the last commit is the initial commit execute:<br>
`git update-ref -d HEAD`

## Main
1. Add changed files to staging<br>
`git add <filename>` / `git add .`
2. To remove file from staging area<br>
`git rm --cached <filename>`
3. Commit the changes<br>
`git commit -m "commit message"`
4. To link a repository<br>
`git remote add origin <URL>`
5. To push the changes<br>
`git push <remote_repo> <branch_name>`
