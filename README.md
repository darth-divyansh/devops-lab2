# DevOps Lab 2
## Merging Two Files in Git

## Objective
To understand and practice merging branches in Git.

## Prerequisites
- A Git repository with multiple branches.

## Steps to Merge Branches in Git

### 1. Check Existing Branches
To list all branches in the repository:
```sh
git branch
```

### 2. Switch to the Target Branch
Move to the branch where you want to merge changes:
```sh
git checkout <target_branch>
```
Example:
```sh
git checkout main
```

### 3. Merge the Source Branch
Merge changes from the source branch into the target branch:
```sh
git merge <source_branch>
```
Example:
```sh
git merge feature-branch
```

### 4. Resolve Merge Conflicts (If Any)
If there are conflicts, Git will notify you. Open the conflicting files, resolve the differences, and stage the resolved files:
```sh
git add <resolved_file>
```
After resolving all conflicts, complete the merge with:
```sh
git commit -m "Resolved merge conflicts"
```

### 5. Push Merged Changes to Remote Repository
To update the remote repository with merged changes:
```sh
git push origin <target_branch>
```
Example:
```sh
git push origin main
```

## Conclusion
This lab covered the process of merging branches in Git, handling merge conflicts, and pushing the merged changes to a remote repository.

## Additional Resources
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/en)

