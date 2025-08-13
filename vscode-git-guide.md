# VS Code and Git Introduction Guide

## Installation Instructions

### Installing VS Code

#### Windows PC
1. Visit [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Click "Download for Windows"
3. Run the downloaded `.exe` file
4. Follow the installation wizard:
   - Accept the license agreement
   - Choose installation location (default is recommended)
   - Select additional tasks:
     - ✅ Create a desktop icon
     - ✅ Add "Open with Code" action to Windows Explorer file context menu
     - ✅ Add "Open with Code" action to Windows Explorer directory context menu
     - ✅ Register Code as an editor for supported file types
     - ✅ Add to PATH (restart required)
5. Click "Install" and wait for completion
6. Launch VS Code

#### Mac
1. Visit [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Click "Download for Mac"
3. Open the downloaded `.zip` file
4. Drag "Visual Studio Code.app" to the Applications folder
5. Launch VS Code from Applications or Spotlight
6. If you see a security warning, go to System Preferences > Security & Privacy > General and click "Open Anyway"

### Installing Git

#### Windows PC
1. Visit [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Download the latest version for Windows
3. Run the downloaded `.exe` file
4. Follow the installation wizard:
   - Use default installation location
   - Select components (default selections are fine)
   - Choose default editor: Select "Use Visual Studio Code as Git's default editor"
   - Adjust PATH environment: "Git from the command line and also from 3rd-party software"
   - Use bundled OpenSSH
   - Use the OpenSSL library
   - Configure line ending conversions: "Checkout Windows-style, commit Unix-style line endings"
   - Use Windows' default console window
   - Default pull behavior: "Default (fast-forward or merge)"
   - Choose credential helper: "Git Credential Manager"
   - Enable file system caching
5. Complete installation and open Command Prompt or PowerShell to verify: `git --version`

#### Mac
**Option 1: Using Homebrew (Recommended)**
1. Install Homebrew if not already installed:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install Git:
   ```bash
   brew install git
   ```

**Option 2: Using the Git installer**
1. Visit [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
2. Download the latest version
3. Open the downloaded `.dmg` file
4. Run the `.pkg` installer
5. Follow the installation prompts

**Option 3: Using Xcode Command Line Tools**
1. Open Terminal
2. Run: `xcode-select --install`
3. Click "Install" when prompted

### Installing GitHub CLI (gh)

#### Windows PC
1. Visit [https://cli.github.com/](https://cli.github.com/)
2. Download the Windows installer
3. Run the `.msi` file and follow the installation wizard
4. Alternatively, use package managers:
   - **Chocolatey**: `choco install gh`
   - **Scoop**: `scoop install gh`
   - **Winget**: `winget install GitHub.cli`

#### Mac
1. **Using Homebrew (Recommended)**:
   ```bash
   brew install gh
   ```
2. **Using MacPorts**:
   ```bash
   sudo port install gh
   ```
3. **Download installer**: Visit [https://cli.github.com/](https://cli.github.com/) and download the macOS installer

### Post-Installation Setup

#### Configure Git (Both PC and Mac)
Open Terminal (Mac) or Command Prompt/PowerShell (Windows) and run:
```bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"
```

#### Authenticate GitHub CLI
```bash
gh auth login
```
Follow the prompts to authenticate with your GitHub account.

---

## Course Outline: Introduction to VS Code and Git

### Class Overview
**Duration**: 3-4 hours  
**Target Audience**: Beginners with basic computer skills  
**Prerequisites**: VS Code and Git installed on participant computers

### Learning Objectives
By the end of this class, students will be able to:
- Navigate and use VS Code's basic features
- Understand version control concepts
- Create and manage Git repositories
- Use basic Git commands
- Connect local repositories to GitHub
- Collaborate using Git and GitHub

---

### Module 1: Introduction to VS Code (45 minutes)

#### 1.1 Getting Familiar with VS Code (15 minutes)
- **Interface Overview**
  - Activity Bar (Explorer, Search, Source Control, Run & Debug, Extensions)
  - Side Bar and primary panels
  - Editor area and tabs
  - Status Bar
  - Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)

#### 1.2 Basic File Operations (15 minutes)
- **Working with Files and Folders**
  - Opening files and folders
  - Creating new files (`Ctrl+N` / `Cmd+N`)
  - Saving files (`Ctrl+S` / `Cmd+S`)
  - File Explorer navigation
  - Opening integrated terminal (`Ctrl+`` / `Cmd+``)

#### 1.3 Essential Features (15 minutes)
- **Productivity Features**
  - Syntax highlighting and IntelliSense
  - Find and Replace (`Ctrl+F` / `Cmd+F`)
  - Multi-cursor editing (`Alt+Click` / `Option+Click`)
  - Basic settings and preferences
  - Installing useful extensions (Git Lens, Prettier, Live Server)

---

### Module 2: Understanding Version Control (30 minutes)

#### 2.1 What is Version Control? (10 minutes)
- **Core Concepts**
  - Why version control matters
  - Tracking changes over time
  - Collaboration and backup benefits
  - Distributed vs centralized systems

#### 2.2 Git Fundamentals (20 minutes)
- **Key Terminology**
  - Repository (repo)
  - Commit
  - Branch
  - Merge
  - Remote
  - Clone
  - Push and Pull
- **Git Workflow Overview**
  - Working Directory → Staging Area → Repository
  - Local vs Remote repositories

---

### Module 3: Getting Started with Git (60 minutes)

#### 3.1 Initial Git Setup (10 minutes)
- **Configuration**
  - Setting user name and email
  - Checking Git installation
  - Understanding `.gitconfig`

#### 3.2 Creating Your First Repository (20 minutes)
- **Local Repository Creation**
  - `git init` command
  - Understanding the `.git` folder
  - Creating a README.md file
  - Making your first commit

#### 3.3 Basic Git Commands (30 minutes)
- **Essential Commands**
  - `git status` - Check repository status
  - `git add` - Stage changes
  - `git commit` - Save changes
  - `git log` - View commit history
  - `git diff` - See changes
- **Hands-on Practice**
  - Create and modify files
  - Stage and commit changes
  - View commit history

---

### Module 4: Working with GitHub (45 minutes)

#### 4.1 Introduction to GitHub (10 minutes)
- **What is GitHub?**
  - Cloud-based Git repository hosting
  - Collaboration features
  - Project management tools
  - GitHub vs Git distinction

#### 4.2 Connecting Local and Remote Repositories (20 minutes)
- **Repository Connection**
  - Creating a GitHub repository
  - Adding remote origin
  - `git push` - Upload changes
  - `git pull` - Download changes
  - Understanding SSH vs HTTPS

#### 4.3 GitHub CLI Basics (15 minutes)
- **Using gh CLI**
  - Authentication setup
  - Creating repositories from command line
  - Basic repository operations
  - Viewing repository information

---

### Module 5: VS Code Git Integration (30 minutes)

#### 5.1 Built-in Git Features (15 minutes)
- **Source Control Panel**
  - Viewing changes
  - Staging files
  - Writing commit messages
  - Pushing and pulling
  - Branch management

#### 5.2 Git Extensions and Workflow (15 minutes)
- **Enhanced Git Experience**
  - GitLens extension features
  - Viewing file history
  - Blame annotations
  - Merge conflict resolution
  - Branch visualization

---

### Module 6: Collaboration Basics (30 minutes)

#### 6.1 Branching and Merging (15 minutes)
- **Branch Concepts**
  - Why use branches?
  - Creating and switching branches
  - `git branch` and `git checkout`
  - Basic merging concepts

#### 6.2 GitHub Collaboration Features (15 minutes)
- **Working with Others**
  - Forking repositories
  - Pull requests overview
  - Issues and project management
  - Basic collaboration workflow

---

### Module 7: Best Practices and Troubleshooting (20 minutes)

#### 7.1 Git Best Practices (10 minutes)
- **Good Habits**
  - Writing meaningful commit messages
  - Committing frequently
  - Using `.gitignore` files
  - Keeping repositories organized

#### 7.2 Common Issues and Solutions (10 minutes)
- **Troubleshooting**
  - Undoing commits
  - Resolving simple merge conflicts
  - Recovery techniques
  - Where to find help

---

### Wrap-up and Q&A (20 minutes)
- **Review Key Concepts**
- **Next Steps for Learning**
  - Advanced Git features
  - GitHub Actions
  - Collaborative workflows
  - Additional VS Code extensions
- **Resources for Continued Learning**
  - Official documentation
  - Online tutorials
  - Practice repositories

---

### Hands-on Exercises Throughout Class

#### Exercise 1: VS Code Exploration
- Open a folder in VS Code
- Create a simple HTML file
- Use find and replace
- Install an extension

#### Exercise 2: First Git Repository
- Initialize a Git repository
- Create and commit files
- View commit history

#### Exercise 3: GitHub Connection
- Create a GitHub repository
- Connect local repository to GitHub
- Push changes to remote

#### Exercise 4: Collaborative Workflow
- Fork a practice repository
- Make changes and commit
- Create a pull request

---

### Resources and References

#### Essential Links
- [VS Code Documentation](https://code.visualstudio.com/docs)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)
- [GitHub CLI Documentation](https://cli.github.com/manual/)

#### Cheat Sheets
- [VS Code Keyboard Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
- [Git Command Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

#### Practice Resources
- [GitHub Skills](https://skills.github.com/)
- [Learn Git Branching](https://learngitbranching.js.org/)
- [VS Code Interactive Playground](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)