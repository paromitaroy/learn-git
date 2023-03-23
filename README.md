## Test commnet on main

# Learn Git :heart:

## Git Basics

- What is Git : Git is a free and open source version control system (VCS), originally created by Linus Torvalds in 2005

- What is VCS :
 Which changes were made? 
 Who made the changes? 
 When were the changes made? 
 Why were changes needed?

## What is a Repository ?

 - A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file’s revision history.
 - The file history appears as snapshots in time called commits, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called branches.


## How Git works

Here is a basic overview of how Git works: 

- Create a branch 
- Add commits
- Open a pull request
- Review code
- Merge
- Deploy

## Basic Git commands 

```
 git init 
```
 it initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control

```
git clone 
```
creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches

```
cd repo
```
change into the `repo` directory

```
git checkout -b <my-branch>
```
it creates a new branch and switch to that branch 

```
git add file1.md 
```
it stage the changed file named file1.md

```
git status
```
shows the status of changes as untracked, modified, or staged.

```
git add . 
```
it stage all changed files

```
git commit -m "adding Readme file"
```
take a snapshot of the changes

```
git push origin <my-branch>
```
push changes to the repository 

```
git pull
```
update all remote tracking branches, and the currently checked out branch

```
git merge
```
this command is typically used to combine changes made on two distinct branches


# References :
Source : [guide](https://guides.github.com/introduction/git-handbook/)
