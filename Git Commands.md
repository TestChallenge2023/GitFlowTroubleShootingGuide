# Here are some common Git commands that you can use when working with branches on GitHub:

## 1. Creating a New Branch:

Create a new branch: git checkout -b new-branch-name

## 2. Switching Between Branches:

Switch to an existing branch: git checkout branch-name

## 3. Viewing Branches




:

List all branches: git branch
List remote branches: git branch -Rrrr
List all branches (local and remote): git branch -a

## 4. Committing Changes to a Branch:

Add changes: git add .
Commit changes: git commit -m "Commit message"

## 5. Pushing Changes to a Remote Branch:

Push changes to the current branch: git push origin HEAD
Push changes to a specific branch: git push origin branch-name

## 6. Merging Branches:

Merge a branch into the current branch: git merge source-branch
Merge a branch with a specific commit: git cherry-pick commit-hash

## 7. Deleting Branches:

Delete a local branch: git branch -d branch-name
Delete a remote branch: git push origin --delete branch-name

## 8. Viewing Changes in a Branch:

View the differences between branches: git diff source-branch target-branch

## 9. Pulling Changes from a Remote Branch:

Pull changes from a remote branch into the current branch: git pull origin branch-name

## 10. Creating and Applying Patches:

Create a patch from changes: git format-patch origin/main..your-branch
Apply a patch: git apply patch-file

## 11. Rebasing Branches:

Rebase a branch onto another branch: git rebase target-branch
