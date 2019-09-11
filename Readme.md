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
- shows the status of the git repository

```bash
git show
```
- shows the commit history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
- add the files FILENAME and ANOTHERFILENAME to the stash

```bash
git commit -m "MESSAGE"
```
- commits the stashed files to the repo and adds 
the MESSAGE that describe what was done

```bash
git log
```
- shows a history of the commits made to this point in time

```bash
git log --all --decorate --oneline --graph
```
- displays a 'graph' of the commits, one commit per line

```bash
git config --global alias.adog "log --all --decorate --oneline --graph"
```
- creates a git alias for the log all decorate oneline graph command.
- use this alias by entering 'git adog' (much shorter)

```bash
git remote add origin URL
```
- assign the remote "origin" repository to the URL given
- replace URL with the relevant github/etc location

```bash
git push -u origin master
```
- push the changes to the origin

## Oher Git Things

**.gitignore** is a file that tells git files/folder that are
not to be part of the repository (that is - ignored when
adding/commiting


