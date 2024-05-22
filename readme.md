**Git Version Check:**

- `git --version`: This command is used to check git version.
-
- **Git Configuration:**

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

** Undo commit **
`git reset -soft commit ` : Uncomitted or Local Repository to back Staging area (back one by one commit)
`git reset -hard commit ` : Uncomitted or Local Repository to back Staging area (back hearder)
`git restore <file> ` : Back to unchanged file
`git restore <directory> ` : Back to unchanged directory
`git restore  ` : If you go to alreay staging area you can undo with this

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

**Git Clone From GitHub :**

- For clone a repository github to your computer: `git clone <repository name>`

**Branch Operations:**

- `git branch`: Lists all local branches.
- `git branch -r`: Lists all remote branches.
- `git branch -a`: Lists all branches, both local and remote.
- `git branch <branch_name>`: Creates a new branch with the specified name.
- `git checkout <branch_name>`: Switches to the specified branch.
- `git checkout -b <branch_name>`: Creates a new branch & Switches to the specified branch.
- `git merge <branch_name>`: Merges changes from the specified branch into the current branch.
- `git merge feature`: Merges changes three way.
- `git branch -d <branch_name>`: Deletes the specified local branch.
- `git push -u origin <branch_name>`: Pushes changes to the specified branch on GitHub.

**Branch stash:**

- `git stash`: New commited work hide from workspace.
- `git stash pop`: Get last stash work and delete from stash
- `git stash apply`: Get last stash work without delete from stash
- `git stash list`: See how many stash you have with stash@{n} type id
- `git stash pop stash@{3} / git stash apply stash@{1}`: Get spesific stash
- `git stash clear`: Clear tash
- `git stash drop stash@{n}`: Clear spasific tash
- `git stash -u`:

** Git reset **
- `git reset <commit_id>`: Delete commit
- `git reset <commit_id> --hard`: Delete commit
- `git revert <commit_id>`
- `git rebase main`
- `git merge new-feature --squash`

**Gitignor**
gitignor use for to ensure that certain files not tracked by Git remain untracked.

- Setp 01: creates a new file name with `.gitignore`
- Step 02: Write the file and if you want to hide spasific file then name the file name with extension and if you want to hide the folder then write the folder name and give a `/` last at folder name

## **How to wirte readme.md file **

- Use `#` for Heading we have # to ######
- Use `** ** ` For bold text
- Use ` ``` ``` ` For Code types
- Use ` ```html ``` ` For spesific Code types
- Use `-` For Unordered List
- Use `1/a` For ordered List
- Use `![alttext](src)` For Image show

- | Use ` | Text | Text |
  | ----- | ---- | ---- | ----------- |
  | One   | two  |      | ` For table |



##Git visualization

|Working directory | Staging Area | Local Repo | Remote repo|
|------------------|--------------|------------|------------|
|it status| | | |
|git add|git com |git push | |
|git diff|git reset -soft commit | | |
  
