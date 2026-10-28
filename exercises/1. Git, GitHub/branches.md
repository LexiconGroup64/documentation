---
title: "Git branches"
tags: ["exercise"]
---

## Adding a branch
Take a folder from previous Git exercises, one that have several commits. Let us say it has five commits. Checkout an earlier commit, the third commit. 
You will get a message that you’re not on any branch. 
Use this command to create a new branch:

```
git branch <give the branch a name>
```

Go to the new brach:

```
git checkout <give the branch a name>
```

Add a new text file to the project folder. Stage all changes and commit.

## Repository overview
You can list all branches on the repository:

```	
git branch 
```

You can also expand the commit log view:

```
git log --oneline --decorate --graph --all
```