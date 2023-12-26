<h2>Git</h2>
<p>Git is a distributed version control system that allows multiple developers to work on the same project simultaneously. It tracks changes in the source code during the development process.</p>

<h2>Github</h2>
<p>GitHub is a web-based platform that provides hosting for Git repositories. It enhances Git by providing features for collaboration, code review, and project management.</p>

<h2>Git commands</h2>

 <h3>Initialize a new Git repository:</h3>
 
 ```bash
  git init  
```

<h3>Clone a repository:</h3>

```bash
  git clone [repository_url]
```

  <h3>Check the status of your repository:</h3>
  
```bash
  git status
```

  <h3>Add changes to the staging area:</h3>
  
```bash
  git add [file(s)]
```

  <h3>Commit changes:</h3>

```bash
  git commit -m "Your commit message"
```

  <h3>Displays the commit history with commit IDs, authors, dates, and messages.</h3>
   ```bash
  git log
  ```

  <h3>Shows changes between commits, branches, or the working directory.</h3>
   ```bash
  git diff
  ```

  <h3>Lists local branches and highlights the current branch.</h3>
   ```bash
  git branch
```

  <h3>Creates a new branch.</h3>
   ```bash
  git branch [branch_name]
  ```

  <h3>Switches to the specified branch.</h3>
   ```bash
  git checkout [branch_name]
```

  <h3>Combines changes from the specified branch into the current branch.</h3>
   ```bash
  git merge [branch]
```

  <h3>Fetches changes from a remote repository and merges them into the current branch.</h3>
   ```bash
  git pull [remote] [branch]
  ```

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
