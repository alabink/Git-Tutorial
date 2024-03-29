# Git_Tutorial

## Introduction

Git is a popular version control system widely used for managing source code in software projects. Below are some basic instructions to get started with Git.

## Installing Git

Firstly, you need to install Git on your computer. You can download Git from its official website: [git-scm.com](https://git-scm.com/).

## Configuring Git

After installation, you need to set up your personal information in Git. This includes your name and email address.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Creating a Repository

To begin tracking your project with Git, navigate to your project directory in the terminal and run.

```bash
git init
```

This command initializes a new Git repository in your project directory.

## Basic Git Commands

### git status

Use git status to see the current state of your repository. It shows which files have been modified, added, or deleted.

```bash
git status
```

### git add

To start tracking new files or stage changes for commit, use git add.

```bash
git add filename.txt         # Stage a specific file
git add .                    # Stage all changes in the current directory
```

### git commit

Once you have staged your changes, you can commit them to the repository with a descriptive message.

```bash
git commit -m "Commit message"
```

### git push

If you're working with a remote repository (like GitHub), you can push your committed changes to it using git push.

```bash
git push origin master       # Push changes from local 'master' branch to remote 'origin' repository
```

### git pull

To fetch changes from a remote repository and merge them into your local branch, use git pull.

``` bash
git pull origin master       # Pull changes from remote 'master' branch into local branch
```
# Conclusion

This tutorial provides an introduction to Git, encompassing key aspects such as installation, configuration, repository creation, and fundamental commands for codebase management. While Git offers numerous advanced features for version control and collaboration, grasping these foundational concepts will lay a solid groundwork for your journey with Git.






For more information and advanced usage, refer to the official Git documentation: [git-scm.com](https://git-scm.com/doc).
