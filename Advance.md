- **Stash**: Temporarily save changes that are not ready to be committed.
  - **Save Changes**: `git stash`
  - **List Stashes**: `git stash list`
  - **Apply Stash**: `git stash apply`
  - **Drop Stash**: `git stash drop`
- **Tags**: Mark specific points in a repository’s history.
  - **Create Tag**: `git tag <tag-name>`
  - **List Tags**: `git tag`
  - **Push Tags**: `git push origin <tag-name>`

### Rebase and Reflog
- **Rebase**: Apply changes from one branch onto another.
  - **Start Rebase**: `git rebase <branch-name>`
  - **Abort Rebase**: `git rebase --abort`
  - **Continue Rebase**: `git rebase --continue`
- **Reflog**: Record of changes made to the tip of branches and other references.
  - **View Reflog**: `git reflog`