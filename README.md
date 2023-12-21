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

  #Check the status of your repository:
  git status

  #Add changes to the staging area:
  git add [file(s)]

  #Commit changes:
  git commit -m "Your commit message"

  #Displays the commit history with commit IDs, authors, dates, and messages.
  git log

  #Shows changes between commits, branches, or the working directory.
  git diff

  #Lists local branches and highlights the current branch.
  git branch

  #Creates a new branch.
  git branch [branch_name]

  #Switches to the specified branch.
  git checkout [branch_name]

  #Combines changes from the specified branch into the current branch.
  git merge [branch]

  #Fetches changes from a remote repository and merges them into the current branch.
  git pull [remote] [branch]
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
