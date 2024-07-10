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
