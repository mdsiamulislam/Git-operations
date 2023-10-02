**Git Configuration:**
- `git config`: This command is used to configure Git settings.
- `git config --list`: This command is used to view all Git configurations.

**Initialization:**
- `git init`: Initializes a new Git repository in the current directory.

**Checking Status:**
- `git status`: Shows the status of your working directory, indicating which files are staged, modified, or untracked.

**Staging Changes:**
- `git add .` (or `git add -A`): Stages all changes in the current directory for the next commit.

**Committing Changes:**
- `git commit -m "Your commit message"`: Commits the staged changes with a descriptive message.

**Viewing Commit History:**
- `git log`: Displays a log of all commits in the repository.
- `git log --oneline`: Displays a simplified one-line log of all commits.

**Viewing Differences:**
- `git diff`: Shows the differences between the working directory and the last commit.

**Switching Branches:**
- `git checkout <branch_name>`: Switches to the specified branch.
- `git checkout master`: Switches to the master branch (or the main branch).

**SSH Key Generation:**
- To generate an SSH key: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- To display the generated public key: `cat ~/.ssh/id_rsa.pub`

**Pushing Code to GitHub:**
- Checking remote repositories: `git remote -v`
- Adding a remote repository: `git remote add origin <github_repository_url>`
- Pushing to the main branch: `git push -u origin main`
- Subsequent pushes to the main branch: `git push`

**Pulling Code from GitHub:**
- Pulling from the main branch: `git pull origin main`
- Subsequent pulls: `git pull`

**Branch Operations:**
- `git branch`: Lists all local branches.
- `git branch -r`: Lists all remote branches.
- `git branch -a`: Lists all branches, both local and remote.
- `git branch <branch_name>`: Creates a new branch with the specified name.
- `git checkout <branch_name>`: Switches to the specified branch.
- `git merge <branch_name>`: Merges changes from the specified branch into the current branch.
- `git branch -d <branch_name>`: Deletes the specified local branch.
- `git push -u origin <branch_name>`: Pushes changes to the specified branch on GitHub.
