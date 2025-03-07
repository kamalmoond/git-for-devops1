

Initialize a new Git repository:
git init

Clone an existing repository:
git clone <repository_url>

Configuration

Set user name:
git config --global user.name "Your Name"

Set user email:
git config --global user.email "your.email@example.com"

Check configured settings:
git config --list

Staging and Committing

Check the status of files:
git status

Add a file to the staging area:
git add <file_name>

Add all changes to the staging area:
git add .

Commit staged changes:
git commit -m "Commit message"

Amend the last commit:
git commit --amend -m "New commit message"

Branching

List all branches:
git branch

Create a new branch:
git branch <branch_name>

Switch to a branch:
git checkout <branch_name>

Create and switch to a new branch:
git checkout -b <branch_name>

Delete a branch:
git branch -d <branch_name>

Merging and Rebasing

Merge a branch into the current branch:
git merge <branch_name>

Rebase the current branch onto another branch:
git rebase <branch_name>

Remote Repositories

Add a remote repository:
git remote add origin <repository_url>

View remote repositories:
git remote -v

Push changes to a remote repository:
git push origin <branch_name>

Pull changes from a remote repository:
git pull origin <branch_name>

Fetch updates from the remote repository:
git fetch origin

Undoing Changes

Discard changes in a file:
git checkout -- <file_name>

Reset a file to its last committed state:
git reset <file_name>

Reset the last commit:
git reset --soft HEAD~1

Hard reset (removes all changes):
git reset --hard HEAD~1

Logs and History

View commit history:
git log

View commit history in one line:
git log --oneline

Show changes between commits:
git diff

Stashing

Save changes for later:
git stash

Apply the latest stash:
git stash apply

List stashed changes:
git stash list

Drop the latest stash:
git stash drop

Tags

List all tags:
git tag

Create a new tag:
git tag <tag_name>

Delete a tag:
git tag -d <tag_name>

Push tags to remote:
git push origin --tags

Submodules

Add a submodule:
git submodule add <repository_url>

Initialize submodules:
git submodule init

Update submodules:
git submodule update

