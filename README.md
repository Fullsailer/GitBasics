# Git Basics

## Introduction

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
>
> –– <cite>[Git](https://git-scm.com/)<cite>

## Objective

Git Basics helps users learn the basics of Git.

## Table of Content

- [Steps to Contribute](#steps-to-contribute)
- [Commit Guidelines](#commit-guidelines)
- [Points to Consider while Contributing](#points-to-consider-while-contributing)

## Steps to contribute

In order to contribute to this project, follow the steps below:

- Fork the project, using the gray `Fork` button in the top right of this page
- Clone your forked repository

  ```bash
  git clone https://github.com/<YourUsername>/GitBasics.git
  ```

- Create a branch in your local repository to make your changes in

  ```git
  git checkout -b your-branch-name
  ```

- After making changes in your local repository, add the files changed

  ```git
  git add file-name
  ```

- Commit changes when you are satisfied. Refer to [Commit Guidelines](#commit-guidelines)

  ```git
  git commit -m "<message>"
  ```

- Push changes to your remote forked repository

  ```git
  git push -u origin your-branch-name
  ```

- Go back to your repository on GitHub and submit a Pull Request with the commits you want to merge with the project
- Follow up with the comments in your pull requests until it is merged

## Commit guidelines

Use the following commit category at the beginning of your message, to make commits easy to follow:

- **feat** - for new features
- **fix** - for defects or bugs
- **chore** - for changes that don't alter the source, but necessary
- **ci** - for ci pipeline changes
- **docs** - for documentation changes
- **perf** - for performance enhancements
- **refactor** - for refactors; altering the code, but not changing functionality
- **revert** - reverting changes
- **style** - for cosmetic changes
- **test** - for unit tests

## Points to consider while contributing

- Maintain original code formatting to avoid merge conflicts
- Keep comments meaningful. Do not add any unnecessary comments in between the code
