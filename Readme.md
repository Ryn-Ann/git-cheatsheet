#Readme.md

This is my git cheat sheet.

## git commands

```bash
git init REPO-NAME
```
- creates a repository called REPO-NAME

```bash
git status
```
-shows the status of the git repository

```bash
git show
```
- shows the commit history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
-add the files FILENAME and ANOTHERFILENAME to the stash

```bash
git commit -m "MESSAGE"
```
-commits the stashed files to the repo and adds 
the MESSAGE that describe what was done

```bash
git log
```
-shows a history of the commits made to this point in time

```bash
git log --all --decorate --oneline --graph
```
-shows all history of changes in one line

## Oher Git Things

**.gitignore is a file that tells git files/folder that are
not to be part of the repository (that is - ignored when
adding/commiting
