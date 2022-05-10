# GitHub Intro Notes

## Day One Coding

### Git Resources
 - [GitHub Resources](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources)
 - [Pro Git Book](https://git-scm.com/book/en/v2)
 - [Git Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Vocabulary
 - git
    > Git is a version control tracking software
 - GitHub
    > An online resource for storing git repositories
 - branch
    > Branches are a separate named versions of the code that are able to be called and worked on before merging it back into the main git branch
 - remote & local
   - Remote
        > remote is the online version of the git repository you will communicate with
    - Local
        > local is the version of code that exists on your computer that will be available to push to the remote repository
 - repo (repository)
    > The online collection of code that exists for an individual project using git
 - clone
    > the command/action using git that copies a version of the repository to your local computer
 - push & pull
   - push
        > the command/action using git to push code from the local machine to the remote repository
    - pull
        > the command/action using git to pull code from the remote repository to the local machine

## Git Workflow
---
### Informational Commands for Solo Programming
---
List
```bash
$ ls
```

Print Working Directory
```bash
$ pwd
```
Find Status of Git
```bash
$ git status
```
Add individual files to be committed.

```bash
$ git add <file-name>
```
Commit bundle of staged files with a message that shortly describes code changes. 
```bash
$ git commit -m "<meaningfull-message>"
```

Push staged commit from local computer to online repository branch. i.e. main, production, dev, etc.
```bash
$ git push origin <branch-name>
```
---

### Informational Commands for Paired Programming
---
Create New Branch
```bash
$ git checkout -b <branch-name>
```
