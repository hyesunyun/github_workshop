# Github Workshop

In this workshop, you will learn the basics of using [Github](https://github.com) as a web-based version control system (VCS).
VCSs are software tools that help software teams manage changes to source code over time.

## Workshop Topics
This workshop will cover the following topics:
1. Github Account Creation & Initial Setup
2. Command Line Basics
3. Configuration
4. Creating Repository and Downloading to Local Computer
5. Pushing and Pulling Changes to Repository
6. Branching and Merging Changes
7. Collaborative Workflow

### What do you need for the workshop?
1. Web browser to access GitHub
2. Email address for account creation
3. Terminal (mac/linux) / cmd or PowerShell (windows)
4. Some type of text editor or IDE (Visual Studio, Sublime, Atom, PyCharm, etc.)

## What is Git & Github?
- **Git**: A version control system that tracks changes.
- **GitHub**: A cloud-based hosting service for Git repositories. [Gitlab](https://about.gitlab.com/) and [Bitbucket](https://www.atlassian.com/software/bitbucket) are some alternatives to Github.

## Setup
- Sign up on GitHub (if you don’t have an account)
- Install Git (if not already installed)
  - Windows: [Git for Windows](https://git-scm.com/downloads/win)
  - Mac: run the following in a terminal => `brew install git` (Homebrew)
  - Linux: run the following in a terminal => `sudo apt install git` (Debian-based)
 
## Command Line Basics
The command line is a text-based interface for interacting with your computer, and you will only need to know few basic commands for navigation and file management to work with Git.

### Navigation
- `cd` (**change directory**): Navigates to different directories.
  - `cd ~`: Goes to your home directory.
  - `cd ..`: Goes to the parent directory.
  - `cd /path/to/directory`: Navigates to a specific directory. 
- `pwd` (**print working directory**): Displays the current directory's path

### File and Directory Management
- `ls` (**list files**): Shows the contents of the current directory. 
  - `ls -l`: Provides a detailed listing with permissions, size, and modification dates. 
- `mkdir` (**make directory**): Creates a new directory. 
  - `mkdir -p ./workspace/docs`: Creates the "docs" directory and its parent directory "workspace" if they don't exist. 
- `rm` (**remove**): Deletes files or directories. 
  - `rm filename`: Deletes a file.
  - `rm -r directoryname`: Deletes a directory and its contents.
 
## Git Configuration
Run the following commands to configure your Git. You only need to do this once.

```sh
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## Basic Git Commands & Tips

> [!NOTE]  
> For basic git commands and details of an example collaborative workflow, please refer to [Git Command Cheat Sheet.pdf](Git&#32;Command&#32;Cheat&#32;Sheet.pdf)
> We will go through these in the workshop and highly encourage you to follow along!

> [!TIP]
> Try to use good, descriptive commit messages. Brief enough that it’s easy to read, but detailed enough that it’s easy to understand. 
> Explain *what* and *why* rather than the *how*.
> 
> You can also follow some conventional commit message style. \
> *Commit types include*: `Feat` – *feature*, `Fix` – *bug fixes*, `Docs` – *changes to the documentation like README*, `Style` – *style or formatting change* \
> *Example*: `Docs: Fixes typo on in-from-the-depths.md`
> 
> This article provides a more in-depth look at writing good git commit messages: https://cbea.ms/git-commit/

> [!IMPORTANT]  
> Basic collaborative workflow: Clone → Branch → Edit → Add → Commit → Push → PR.

## Resources
Recommended resources for further learning:
- [Command line crash coure](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Environment_setup/Command_line)
- [GitHub Docs](https://docs.github.com/en)
- [Git Handbook](https://docs.github.com/en/get-started/using-git/about-git)
- Git Rebase vs Merge vs Squash??
  - [From GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/about-pull-request-merges)
  - [From Medium Blog Post](https://medium.com/@shikha.ritu17/git-rebase-vs-merge-vs-squash-choosing-the-right-strategy-for-version-control-a9c9bb97040e)
