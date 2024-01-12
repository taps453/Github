### Git
- Git is a distributed version control system that allows multiple developers to work on the same project simultaneously. It tracks changes in the source code during the development process.

### Github
- GitHub is a web-based platform that provides hosting for Git repositories. It enhances Git by providing features for collaboration, code review, and project management.

### Git commands

##### Initialize a new Git repository
 
 ```bash
  git init  
```

##### Clone a repository

```bash
  git clone [repository_url]
```

  ##### Check the status of your repository
  
```bash
  git status
```

##### Add changes to the staging area
  
```bash
  git add [file(s)]
```

  ##### Commit changes

```bash
  git commit -m "Your commit message"
```

  ##### Displays the commit history with commit IDs, authors, dates, and messages.
  
```bash
  git log
```

  ##### Shows changes between commits, branches, or the working directory.
  
```bash
  git diff
```

 ##### Lists local branches and highlights the current branch.
  
```bash
  git branch
```

  ##### Creates a new branch.
  
```bash
  git branch [branch_name]
```

  ##### Switches to the specified branch.
  
```bash
  git checkout [branch_name]
```

  ##### Combines changes from the specified branch into the current branch.
  
```bash
  git merge [branch]
```

 ##### Fetches changes from a remote repository and merges them into the current branch.
  
```bash
  git pull [remote] [branch]
```

##### Sends local commits to a remote repository.

 ```bash
  git push [remote] [branch]
``` 

##### Lists all remote repositories.

```bash
  git remote -v
```

##### Downloads changes from a remote repository without merging.
  
```bash
  git fetch [remote]
```

##### Unstages changes, or resets the file to the last commit.

```bash
  git reset [file]
``` 

##### Creates a new commit that undoes changes made in a previous commit.

```bash
  git revert [commit]
```
  
##### Removes a file from both the working directory and the staging area.

```bash
  git rm [file]
```

##### Creates a lightweight tag for a specific commit.

```bash
  git tag [tag_name]
``` 

##### Temporarily saves changes that are not ready to be committed.

```bash
  git stash
```



