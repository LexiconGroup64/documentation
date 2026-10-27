---
title: "Git install"
tags: ["exercise"]
---

## Download and install Git

### For Windows
[Git link](https://github.com/git-for-windows/git/releases/download/v2.53.0.windows.1/Git-2.53.0-64-bit.exe)

### For macOS
[Git link](https://git-scm.com/install/mac)

The options for macOS involves some service that will manage the running
of Git. Consult the page and choose one option. The Homebrew option is a
popular choice. Use the Terminal app and run the command given on the
linked page there.

## Verify install
Open the Command Prompt app in Windows or the Terminal app in macOS.
Check the version of Git installed with:

```
git --version
```

If the command gets an “unrecognized command” response, then the
install failed. A correct install should return a version number.

## Initiate a new repository
Make a new folder for your Git exercises. In this document, it will be
named *git-exercises*, but you can name it yourself. Place it where it makes
sense in your computer’s file system, for instance in a code folder in your
documents folder.

For Windows, right-click the folder icon for the git-exercises folder in the
*File Explorer* and choose to open command prompt at folder (the actual
phrase might be slightly diﬀerent in your menu).

In the *Command Prompt*, it should say “git-exercises” on the last line. If it
does, then type:

```
git init
```

If you return to the *File Explorer*, you should see a .git folder added inside
the git-exercises folder.
For macOS, repeat the same steps but use the *Terminal* instead. In order
to see the new .git folder when finished, press Shift + Command + “ . “ to
see hidden folders and documents.