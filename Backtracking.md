When working on a Git project, sometimes we make changes that we want to get rid of. 
Git offers a few eraser-like features that allow us to undo mistakes during project creation. 

## head commit

In Git, the commit you are currently on is known as the HEAD commit. In many cases, the most recently made commit is the HEAD

```
git show HEAD
```

The output of this command will display everything the git log command displays for the HEAD commit, plus all the file changes that were committed.

## git checkout

You could rewrite the line how it was originally, but what if you forgot the exact wording? The command

```
git checkout HEAD filename
```
will restore the file in your working directory to look exactly as it did when you last made a commit.

Here, filename again is the actual name of the file. If the file is named changes.txt, the command would be

```
git checkout HEAD changes.txt
```

## 
