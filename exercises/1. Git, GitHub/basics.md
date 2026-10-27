---
title: "Basic Git commands"
tags: ["exercise"]
---

## Initiate a new repository
Make a new folder for your Git exercises. In this document, it will be named git-exercises, but you can name it yourself. Place it where it makes sense in your computer’s file system, for instance in a code folder in your documents folder.

For Windows, right-click the folder icon for the git-exercises folder in the File Explorer and choose to open command prompt at folder (the actual phrase might be slightly diﬀerent in your menu).

In the Command Prompt, it should say “git-exercises” on the last line. If it does, then type:

```
git init
```

If you return to the File Explorer, you should see a .git folder added inside the git-exercises folder. For macOS, repeat the same steps but use the Terminal instead. In order to see the new .git folder when finished, press Shift + Command + “ . “ to see hidden folders and documents.

## The first commit
Applications like Command Prompt and Terminal can be referenced as Command Line Interfaces (CLI.) We will use the CLI for our first commit. Staying with the open CLI in the git-exercises folder, type this command:

```
git status
```

The status given in the message tells of changes made to the folder since the last commit. At this moment, the message you get back should tell of an empty change list. Let’s add a txt-file to the folder. Repeat the git status command (you can arrow key up and down to circle through previous commands in the CLI). You should now see the new file in the message. For the file to be added to a commit, you need to stage it:

git add filename.txt

You can also add all files by replacing the filename with a dot:

```
git add .
```

Again do the git status . Recognize that the file has changed status and is now ready for commit. The commit will take a snapshot of the present state of the repository and set the change status back to empty.

```
git commit -m “Add first textfile”
```

The command’s second part needs some explanation. You have a -m flag indicating that there will be a message and then there is a message. Once more, check the git status and see that it is empty. You can also check that the commit was registered:

```
git log
```

## Checkout an earlier version
- Create a new folder on your computer. Initialize a Git repository in it. 
- Add a text file. Paste some text of a 100 words size in it.
- Check the git status of the folder. 
- Add the new text file to a future commit (stage it.)
- Make a commit.
- Erase half of the text in the text file. 
- Stage the text file and make another commit.
- Bring up the git log and copy the id for the first commit. 
- Use this command to checkout the earlier version:

```
git checkout <id of the first commit>
```

See if the previous text is restored in the text file

## Reverting a commit
- From the previous state in step 1, add this command (main or master):
	
```	
git checkout main 
```

- The text file should be back to its reduced state, half of the text gone.
- Add some text to the file.
- Stage the text file and commit. 
- Do a git log and note down the id for the last commit. 
- Use this command to revert the previous commit:

```	
git revert <id of the last commit> —no-commit
git commit -m “Revert last commit”
```

- Do a git log and notice the new commit.
- Check the text file. 

## Add a gitignore file
- Add a file called settings.txt
- Open the file and enter some text
- Do a git status
- Add a file called .gitignore.
- Open the .gitignore file and enter the text file name
- Do a git status
