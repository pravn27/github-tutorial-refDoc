# Temporarily store modified, tracked files in order to change branches
### Use case of below commands during
> After making some changes in files, and want to switch to different feature branch, with below commands save modified files and get back those modified files based on your needs.

| Command | Description |
| --- | --- |
| git stash save ["name"] | Save temporarily modified file in name given |
| git stash list | List all stashed items |
| git stash pop ["name"] | Get modified files back with respect to feature branch and deleted from stash items  |
| git stash apply ["name"] | Get modified files back stash list & applied, but will not deleted from stash items |
| git stash drop stash@{1} | Delete / Remove particular stash (1st item) item from list |
| git stash drop | Discard the changes from top of stash stack |