---
title: "Git"
author: "Clemens Schmid"
theme: "Singapore"
---

# The command line

## The command line

## Navigating

```bash
pwd
ls
cd
```

## Creating, editing and deleting files

```bash
touch
echo "test" > file.txt
nano
rm
```

## Making and deleting directories

```
mkdir
rm -r myDir
```

## Running fancy command line tools

A dialogue with the computer

```bash
# trident
git
```

# What is Git?

## The software

## Version control

## Trees and networks

## Where and how to get help

# Git in action

## Creating a git repository

\small
```bash
mkdir myProject
cd myProject
```
\normalsize

```bash
git init
```

**Initialize a directory to be managed by Git**

- Creates a hidden `.git` directory, which Git uses to manage everything for this project
- Actually we rarely start like this -- we rather create project on GitHub and clone that (see below)

## Git's status

```bash
git status
```

**Show the status of a project**

- In a new project without any changes Git could detect, we get the following message:

```
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

- We're on the master branch
- We haven't added any commits yet
- There's nothing to commit, because we haven't made any changes yet

This will change -- we will call `git status` frequently

## Logging progress: Preparing changes

\small
```bash
echo "This is a test file" > testfile.txt
ls
cat testfile.txt
```
\normalsize

```bash
git add testfile.txt
```

**Add files to the set of changes prepared for the next commit**

Useful options:

- `--all`: Add all changes to the staging area
- `-f`: Force a file to be added that would otherwise be ignored (see below)

## Logging progress: The commit

```bash
git commit
```

## Deeper inspection: The log

```bash
git log
```

## Deeper inspection: Differences

```bash
git diff
```

# The .gitignore file

## Ignoring files

## Unignoring files

# Branches

## Creating a new branch

```bash
git branch
```

## Switching between branches

```bash
git switch
# git checkout
```

## Merging branches

```bash
git merge
```

## Cleaning up and unwanted changes

```bash
git reset
git clean
```

## The woundrous world of stashing

```bash
git stash
```

# Beyond that

## Working with remotes

Will be covered later

```bash
git clone
git remote
# git fetch
git pull
git push
```

## Tagging

```bash
git tag
```

## Further obscure commands down the rabbit hole

```bash
git revert
git rebase
git range-diff
git blame
git cherrypick
# ...
```