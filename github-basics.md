# Github Basic Commands
- ### To set up initially in local machine
    - Set / Config your user name, email globally in local machine
        ``` 
        git config --global user.name "test"
        git config --global user.email "test@test.com"
        ```
    - Check your current user name, email in git config
        ```
        git config user.name
        git config user.email
        ```
    - Once inside the respective directory / folder, to initialize the git
        ```
        git init
        ```
- ### Basics Commands
| Command | Description |
| --- | --- |
| git clone [remote_url] | Clone the entire repository from a remote / hosted location via URL |
| git branch | List your branches |
| git checkout [branch_name] | Switch to branch specified |
| git checkout -b [branch_name] | Create new branch & switch to branch specified |
| git branch [branch_name] | Create new branch specified |
| git status | Show the modified files in working directory |
| git log | Show all commits history |
| git add [path_of_files] | Adding modified files to staging |
| git commit -m ["Proper_Commit_Message"] | Committing staged files with commit message |
| git commit --amend | To update the very latest commit message |
| git push origin [branch_name] | Pushing the changes to remote branch |
| git merge [branch_name] | Will merge specified branch into current branch |
| git reset --hard | Will discard all local changes, and take till recent commit history |
| git cherry-pick [commitId] | Get specific commit changes from other branch to current branch and merged |
| git revert [commitId] | To revert specific commits changes after committed |