# Branch Management Guide

## Creating and Managing Branches in Git

### 1. Creating a Branch
To create a new branch, use the following command:
```bash
git branch <branch-name>
```
**Example:**
```bash
git branch feature-xyz
```

### 2. Switching Branches
To switch to another branch, use the `checkout` command:
```bash
git checkout <branch-name>
```
**Example:**
```bash
git checkout feature-xyz
```
You can also combine this with the branch creation command:
```bash
git checkout -b <branch-name>
```
**Example:**
```bash
git checkout -b new-feature
```

### 3. Merging Branches
To merge changes from one branch into your current branch, use the `merge` command:
```bash
git merge <branch-name>
```
**Example:**
```bash
git merge feature-xyz
```

### 4. Rebasing Branches
Rebasing allows you to integrate changes from one branch into another. Use the command:
```bash
git rebase <branch-name>
```
**Example:**
```bash
git rebase feature-xyz
```

### Further Reading
- Official Git Documentation: [https://git-scm.com/doc](https://git-scm.com/doc)