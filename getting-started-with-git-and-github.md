# Basics of GitHub and Git

## Introduction

**Git** is a distributed version control system that allows multiple developers to collaborate on projects and track changes to files over time. **GitHub** is a platform built around Git that provides additional features such as hosting repositories online, collaboration tools, and version control.

## Key Concepts

### 1. Version Control

Version control is the management of changes to documents, computer programs, large web sites, and other collections of information. It allows teams to:

- Track modifications: See who changed what, when, and why.
- Revert changes: Roll back to a previous version if needed.
- Maintain consistency: Ensure everyone is working on the latest version of files.

### 2. Git

Git is a distributed version control system designed for speed and efficiency. It operates locally on your computer, making it fast and capable of handling both small and large projects effectively. Key features of Git include:

- **Snapshots**: Git captures a snapshot of your files whenever a change is made, rather than storing incremental differences.
- **Branching and Merging**: Git allows for branching (creating separate lines of development) and merging branches back together. This enables parallel development and feature isolation.
- **Distributed Development**: Each developer has a complete copy of the repository, including its full history. This allows work to continue offline and facilitates collaboration.

### 3. GitHub

GitHub enhances Git by providing a centralized platform for collaboration and project management. Key features of GitHub include:

- **Hosting Repositories**: GitHub hosts your Git repositories in the cloud, making it accessible from anywhere with an internet connection.
- **Pull Requests**: Developers can propose changes (pull requests) and discuss them before merging into the main branch.
- **Issue Tracking**: GitHub provides tools for issue tracking, allowing teams to manage tasks, bugs, and feature requests.
- **Collaboration**: GitHub facilitates collaboration through features like code reviews, project wikis, and team management.

# Getting Started with Git and GitHub

### Installing Git

To start using Git, you need to install it on your local machine. You can download Git from [git-scm.com](https://git-scm.com/) and follow the installation instructions for your operating system.

### Setting Up Git

After installing Git, configure it with your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Creating a Repository

To create a new Git repository locally, navigate to your project directory and initialize Git:

```bash
cd /path/to/your/project
git init
```

### Basic Git Workflow

1. **Add**: Add files to the staging area for Git to track changes.

```bash
git add filename
```

2. **Commit**: Commit changes with a descriptive message.

```bash
git commit -m "Your commit message"
```

3. **Push**: Push commits to a remote repository (like GitHub).

```bash
git push origin main
```

### Working with GitHub

1. **Create a Repository**: Create a new repository on GitHub.

2. **Clone**: Clone an existing repository from GitHub to your local machine.

```bash
git clone https://github.com/username/repository.git
```

3. **Branching**: Create a new branch for developing a feature or fixing a bug.

```bash
git checkout -b new-feature
```

4. **Pull Requests**: Open a pull request on GitHub to propose changes and collaborate with others.

5. **Merge**: Merge pull requests into the main branch after review and approval.
