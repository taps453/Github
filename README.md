<h4>Git</h4>
<p>Git is a distributed version control system that allows multiple developers to work on the same project simultaneously. It tracks changes in the source code during the development process.</p>
<hr>
<h4>Github</h4>
<p>GitHub is a web-based platform that provides hosting for Git repositories. It enhances Git by providing features for collaboration, code review, and project management.</p>
<hr>
<h4>Git commands</h4>
<li>
  git init - Initializes a new Git repository.
</li>
<li>
  git clone [url] - Creates a copy of a remote repository on your local machine.
</li>
<li>
  git add [file] - Adds changes in the working directory to the staging area.
</li>
<li>
  git commit -m "message" - Records changes in the repository along with a descriptive message.
</li>
<li>
  git status - Shows the status of changes as untracked, modified, or staged.
</li>
<li>
  git log - Displays the commit history with commit IDs, authors, dates, and messages.
</li>
<li>
  git diff - Shows changes between commits, branches, or the working directory.
</li>
<li>
  git branch - Lists local branches and highlights the current branch.
</li>
<li>
  git branch [branch_name] - Creates a new branch.
</li>
<li>
  git checkout [branch_name] - Switches to the specified branch.
</li>
<li>
  git merge [branch] - Combines changes from the specified branch into the current branch.
</li>
<li>
  git pull [remote] [branch] - Fetches changes from a remote repository and merges them into the current branch.
</li>
<li>
  git push [remote] [branch] - Sends local commits to a remote repository.
</li>
<li>
  git remote -v - Lists all remote repositories.
</li>
<li>
  git fetch [remote] - Downloads changes from a remote repository without merging.
</li>
<li>
  git reset [file] - Unstages changes, or resets the file to the last commit.
</li>
<li>
  git revert [commit] - Creates a new commit that undoes changes made in a previous commit.
</li>
<li>
  git rm [file] - Removes a file from both the working directory and the staging area.
</li>
<li>
  git tag [tag_name] - Creates a lightweight tag for a specific commit.
</li>
<li>
  git stash - Temporarily saves changes that are not ready to be committed.
</li>

<hr>

# Git Commands Reference

This document provides a quick reference for commonly used Git commands.

## Configuration

### Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Set your name and email globally for Git.

### Repository Initialization

Create a New Repository

git init
Initialize a new Git repository in the current directory.

### Clone a Repository

git clone <repository-url>
Clone an existing repository to your local machine.


### Check Repository Status

git status
Show the status of changes as untracked, modified, or staged.

### Stage Changes

git add <file(s)>
Stage changes for the next commit.

## Commit Changes

git commit -m "Commit message"
Commit staged changes with a descriptive message.

## Branching
### Create a New Branch

git branch <branch-name>
Create a new branch for feature development or bug fixing.

### Switch Branch

git checkout <branch-name>
Switch to an existing branch.

### Merge Branches

git merge <branch-name>
Merge changes from one branch into the current branch.

### Delete a Branch

git branch -d <branch-name>
Delete a branch after its changes have been merged.

## Remote Repositories
### Add a Remote Repository

git remote add <remote-name> <repository-url>
Add a remote repository for collaboration.

### Fetch Changes

git fetch <remote-name>
Fetch changes from a remote repository.

### Push Changes

git push <remote-name> <branch-name>
Push local changes to a remote repository.

### Pull Changes

git pull <remote-name> <branch-name>
Pull changes from a remote repository into your local branch.

## History and Information
### View Commit History

git log
Show the commit history.

### Show Changes in a Commit

git show <commit-hash>
Display the changes made in a specific commit.

##View Differences

git diff
Show the differences between working directory and staging area.

## Undoing Changes
### Discard Unstaged Changes

git checkout -- <file(s)>
Discard changes in your working directory.

## Unstage Changes

git reset <file(s)>
Unstage changes but keep them in your working directory.

## Amend the Last Commit

git commit --amend
Add changes to the last commit.

## Revert a Commit

git revert <commit-hash>
Create a new commit that undoes changes made in a previous commit.

## Collaboration
###Create a Pull Request
Use your GitHub/GitLab interface to create a pull request.

### Fetch Pull Request Changes

git fetch origin pull/<pr-id>/head:<branch-name>
Fetch changes from a pull request on GitHub.

## Apply Pull Request Changes Locally

git checkout <branch-name>
git pull <remote-name> <branch-name>
Apply pull request changes to your local branch.

## Ignore Files
Create a .gitignore File
Create a file named .gitignore to specify files and directories to be ignored.

touch .gitignore
For example, add *.log to ignore all log files.

*.log
Miscellaneous
Show Git Version
bash
Copy code
git --version
Display the installed Git version.

vbnet
Copy code



