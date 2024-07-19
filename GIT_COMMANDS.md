1. **`git --version`**: Displays the installed Git version.
2. **`git status`**: Shows the current status of the working directory and staging area.
3. **`git config --global user.email "your-email@example.com"`**: Sets the global email address for commits.
4. **`git config --global user.name "Your Name"`**: Sets the global username for commits.
5. **`git config --list`**: Lists all Git configuration settings.
6. **`git init`**: Initializes a new Git repository in the current directory.
7. **`git add <file> <file2>`**: Stages changes in specified files for the next commit.
8. **`git commit -m "commit message"`**: Commits the staged changes with a descriptive message.
9. **`git log`**: Shows the commit history.
10. **`git config --global core.editor "code --wait"`**: Sets the default editor for commit messages to VS Code.
11. **`git show -s --pretty=raw <commit-hash>`**: Displays raw information about a specific commit.
12. **`git ls-tree <tree-id>`**: Lists the contents of a specific tree object.
13. **`git show <blob-id>`**: Displays the content of a specific blob object.
14. **`git cat-file -p <commit-id>`**: Displays the content of a specified Git object.
15. **`git branch`**: Lists all branches in the repository.
16. **`git branch bug-fix`**: Creates a new branch named `bug-fix`.
17. **`git switch bug-fix`**: Switches to the `bug-fix` branch.
18. **`git switch master`**: Switches to the `master` branch.
19. **`git switch -c dark-mode`**: Creates and switches to a new branch named `dark-mode`.
20. **`git checkout orange-mode`**: Switches to the `orange-mode` branch.
21. **`git checkout main`**: Switches to the `main` branch.
22. **`git merge bug-fix`**: Merges changes from the `bug-fix` branch into the current branch.
23. **`git branch -m <old-branch-name> <new-branch-name>`**: Renames a branch.
24. **`git branch -d <branch-name>`**: Deletes a branch.
25. **`git diff`**: Shows differences between working directory and index.
26. **`git diff --staged`**: Shows differences between staged changes and the last commit.
27. **`git diff <branch-name-one> <branch-name-two>`**: Shows differences between two branches.
28. **`git diff <commit-hash-one> <commit-hash-two>`**: Shows differences between two commits.
29. **`git stash`**: Stashes the current changes in the working directory.
30. **`git stash apply`**: Applies the most recent stash.
31. **`git stash drop`**: Drops the most recent stash.
32. **`git stash clear`**: Clears all stashes.
33. **`git tag`**: Lists all tags.
34. **`git tag <tag-name>`**: Creates a new tag.
35. **`git tag <tag-name> <commit-hash>`**: Tags a specific commit with a name.
36. **`git tag -d <tag-name>`**: Deletes a tag.
37. **`git rebase main`**: Rebases the current branch onto `main`.
38. **`git add <resolved-files>`**: Stages files after resolving conflicts during a rebase.
39. **`git rebase --continue`**: Continues the rebase process after resolving conflicts.
40. **`git reflog`**: Shows the reference logs, tracking all changes to the HEAD.
41. **`git reflog <commit-hash>`**: Shows reference logs up to a specific commit.
42. **`git reset --hard <commit-hash>`**: Resets the working directory and index to a specific commit, discarding changes.
43. **`ssh-keygen -t ed25519 -C "your-email@chaicode.com"`**: Generates a new SSH key pair.
44. **`git remote -v`**: Lists the remote repositories.
45. **`git remote add origin https://github.com/hiteshchoudhary/chai-something.git`**: Adds a new remote repository.
46. **`git push origin main`**: Pushes changes to the `main` branch of the remote repository.
47. **`git fetch <remote-name>`**: Fetches changes from a remote repository without merging.
48. **`git pull origin main`**: Fetches and merges changes from the `main` branch of the remote repository.
