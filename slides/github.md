---
title: "Github"
author: "Sophie C. Schmidt"
theme: "Singapore"
---
# Github

## What is Github?

- "a code hosting platform for version control and collaboration"
- a remote git repository, where you can
  - work collaboratively
  - in a version controlled way,
  - discuss changes "where they are made",
  - interact with other users
- or simply back up your stuff remotely

## Your github repository

- has a name (github.com/yourname/yourrepo)
- settings:
  - private or public
  - private: you decide who can see it
  - public: everyone can see it
   - both: YOU decide who commits
  - initialize with a README?
  - add a gitignore?
  - choose a license

## short excursion: **README**

What is a README.md?

- md = markdown:
  - very simple markup language
  - hashtags (#) for headers
  - minus (-) for bullet points
  - asterisk (\*) to make things italic: \*italic\*: *italic*
- README
  - a file that gets displayed first in the repo
  - explains what it is about
  - how to use the code (from data, workflows, to licenses...)
  - how to contribute
  - how to cite

## connect your repos

- easiest way: *clone* the github repository to your own computer
- = download the folder that is your repository

- use :
``` bash
cd /path/to/where/you/want/it
git clone "github.com/yourname/yourrepo"
```

- -> creates new git-repository /path/to/where/you/want/it/yourrepo
- now change / add / commit as you want

## synchronise your local and remote repos

- we want to synchronise them, so they have the same commit history
  - *push*: uploades changes *to* remote
  - *pull*: downloads and merges changes *from* the remote
  - ONLY commited changes get copied

- `git clone`: needs to be done once
- `git pull`: anytime something in the remote has been changed

- if you pull sth that can't be merged automatically
  - amend the affected lines by hand
  - nothing gets overwritten by accident!
  
## Visualisation of Workflow

![](https://dev.vividbreeze.com/wp-content/uploads/2018/03/gitBasicsRemote.jpg)

<!--- show these steps --->


# Working together

## Github's infrastructure

- public repositories can be *forked* by anybody
  - = make a copy to your own profile
  - there make all the changes and commits you want
  - want to suggest changes to the owner of the original repo?   
  --> create a *pull request* (PR)

- owner looks at your commits and decides whether they want to integrate the changes or not
- you can *comment* the PR & discuss changes

## further space for discussions:

- *issues*
  - can be created by anyone to suggest additions, changes, ...
  - discussion thread of comments
  - to dos
  - assign people to tasks
  - link comments to commits / code lines (?)
  - *close* them when done discussing!

<!--- show and tell with 1 partner --->


# Let's do this

<!--- workshop content --->
## Create Github repository

- open Github and log in
- create a new repository
  - make it public
  - initialize with a README
  - add a gitignore
- now:
``` bash
cd /path/to/where/you/want/it
git clone "github.com/yourname/yourrepo"
```

## Change things

<!--- workshop content --->

- open the README.md
- write a couple of words
- git add
- git commit
- git push

**Well done!**

## Cooperating 
<!--- workshop content --->

- take a partner
- exchange URLs to your repositories
- fork the repo of your partner
- clone it to your computer
- add a sentence to his readme
- git add, commit, push
- create a pull request

- partner merges
