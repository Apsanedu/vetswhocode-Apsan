
# Git and GitHub: An Extensive Guide

### Version Control

A Version Control records changes to files over a period of time so that you can go back to specific versions.

## Git - Version Control System

Git is a distributed version control system that allows users to track changes in files and collaborate on projects. Developed by Linus Torvalds in 2005, it has become an essential tool for software development.

### Centralized Version Control System
CVS, Subversion, Perforce

### Distributed Version Control System
Git, Mercurial, Bazaar, Darcs

### **Key Concepts**

- **Repository (Repo)**: A folder that contains all project files, including version history.
- **Fork**: Creating a personal copy of a repository to make changes while keeping a link to the original (it's called the upstream repo)
- **Clone**: Copying a repository from a remote server to a local machine.
    ` git clone <your-fork-url.git> `
- **Branch**: "A git repo is just a big tree 🌳. You might have hundreds of people working on the same project and branches ensure that collaboration can happen without complete chaos. Changes on your branch are isolated from the work everybody else is doing." (Delaney)
    ` git checkout -b my-cool-thing `
- **Commit**: A snapshot of changes made to files at a specific point in time.
` git add .
git commit -m "Easy work!" ` 
- **Pull**: Fetching changes from a remote repository to a local one.
- **Push**: Uploading local changes to a remote repository.
- **Merge**: Combining changes from one branch into another.
- **Conflict**: Occurs when two branches have made changes to the same part of a file.
- **Pull Request (PR)**: Often used in collaboration, it is a request to merge changes from one branch into another. It is identical to the command "git merge".

## Git History

### **Origins**

Git was created by Linus Torvalds in 2005 to support the development of the Linux. Git allows users to collaborate on projects.

### **Key Milestones**

- **2005**: Git's initial release.
- **2008**: GitHub, a web-based Git hosting service, was launched.
- **2013**: Git surpassed Subversion to become the most widely used version control system.
- **2020**: Microsoft acquired GitHub.

## Common Git Commands

### **Initializing a Repository**

- `git init`: Initializes a new Git repository.

### **Basic Commands**

- `git add <file>`: Stages changes for commit.
- `git commit -m "message"`: Records staged changes with a message.
- `git status`: Shows the status of changes in the working directory.

### **Branching and Merging**

- `git branch`: Lists all local branches.
- `git checkout -b <branch>`: Creates and switches to a new branch.
- `git merge <branch>`: Merges changes from one branch into the current branch.
- `git merge <branch> --squash`: Combines all the commits into one when merging one branch into another.
- `git log`: Displays a log of all commits.

### **Remote Repository**

- `git remote add origin <URL>`: Adds a remote repository.
- `git push origin <branch>`: Pushes changes to a remote repository.
- `git pull origin <branch>`: Pulls changes from a remote repository.

### **Collaboration**

- `git clone <URL>`: Clones a remote repository to the local machine.
- `git fork`: Creates a personal copy of a repository on GitHub.
- `git pull request`: Initiates a pull request on GitHub.
- `git fetch`: Retrieves changes from a remote repository.

## GitHub - Online Git Repository Hosting

GitHub is a web-based platform for hosting Git repositories. It offers collaboration features, issue tracking, and project management tools. It has become the go-to platform for open-source and private software development.

### **Features**

- **Repositories**: Store and manage Git repositories.
- **Issues**: Track and manage tasks, bugs, and feature requests.
- **Pull Requests**: Facilitate code review and contribution.
- **Actions**: Automate workflows and CI/CD pipelines.
- **Wikis**: Collaboratively create documentation.
- **Projects**: Manage project boards for task tracking.
- **Security**: Analyze and secure code with automated checks.

## Git Flow

Git Flow is a branching model and a set of conventions for using Git effectively. It defines how branches are organized, how features are developed, and how releases are managed.

### **Branches**

- **Master**: The main branch containing production-ready code.
- **Develop**: The branch for ongoing development and integration of features.
- **Feature**: Short-lived branches for developing new features.
- **Release**: Preparation for a new release, including bug fixes.
- **Hotfix**: Fixing critical issues in the production code.

### **Workflow**

1. Start a new feature branch from `develop`.
2. Develop the feature in the feature branch.
3. Merge the feature branch into `develop` for integration.
4. Create a release branch from `develop` for versioning.
5. Test and finalize the release.
6. Merge the release branch into `master` for production.
7. If needed, create a hotfix branch from `master` for critical fixes.


$$ Works Cited:

Chacon, S., & Straub, B. (2014). *Pro Git: Everything you need to know about Git*. Apress.
Delaney, J. How to Participate on Github. 17 Jan. 2019, https://fireship.io/snippets/git-how-to-participate-on-github/.
GitHub. GitHub Features: The Right Tools for the Job. https://github.com/features.
