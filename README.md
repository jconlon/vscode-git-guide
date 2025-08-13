# VS Code and Git Introduction for USAHA

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

Visit [https://git-scm.com/downloads/mac](https://git-scm.com/downloads/mac) and follow the installation instructions for your Mac system.


### Post-Installation Setup

#### Configure Git (Both PC and Mac)

Open Terminal (Mac) or Command Prompt/PowerShell (Windows) and run:

```bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"
```


---

## Course Outline: Introduction to VS Code and Markdown

### Class Overview

**Duration**: 2 hours  
**Target Audience**: Beginners with basic computer skills  
**Prerequisites**: VS Code and Git installed on participant computers

### Getting Started

Before beginning the course, students will clone this repository:
```bash
git clone https://github.com/jconlon/vscode-git-guide.git
cd vscode-git-guide
```

### Learning Objectives

By the end of this class, students will be able to:
- Navigate and use VS Code's essential features
- Create and edit Markdown documents
- Use VS Code's built-in preview and formatting tools
- Apply Markdown syntax for various content types

---

### Module 1: VS Code Introduction (60 minutes)

#### 1.1 Getting Started (20 minutes)

- **Opening the Course Materials**
  - Clone the course repository using `git clone`
  - Open the folder in VS Code (`code .` or File > Open Folder)
  - Navigate the file explorer

- **Interface Overview**
  - Activity Bar (Explorer, Search, Source Control, Run & Debug, Extensions)
  - Side Bar and primary panels
  - Editor area and tabs
  - Status Bar
  - Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)

#### 1.2 Essential File Operations (20 minutes)

- **Working with Files**
  - Opening files from explorer
  - Creating new files (`Ctrl+N` / `Cmd+N`)
  - Saving files (`Ctrl+S` / `Cmd+S`)
  - File tabs and navigation
  - Split editor views

- **Navigation and Search**
  - Find in file (`Ctrl+F` / `Cmd+F`)
  - Find and Replace (`Ctrl+H` / `Cmd+Option+F`)
  - Go to line (`Ctrl+G` / `Cmd+G`)
  - Quick file open (`Ctrl+P` / `Cmd+P`)

#### 1.3 Productivity Features (20 minutes)

- **Editing Features**
  - Multi-cursor editing (`Alt+Click` / `Option+Click`)
  - Select all occurrences (`Ctrl+Shift+L` / `Cmd+Shift+L`)
  - Line operations (duplicate, move, delete)
  - Auto-formatting and auto-save

- **Extensions and Settings**
  - Installing extensions (Markdown All in One, Prettier)
  - Basic settings access
  - Integrated terminal (`` Ctrl+` `` / `` Cmd+` ``)

---

### Module 2: Markdown Creation and Editing (60 minutes)

#### 2.1 Markdown Basics (20 minutes)

- **What is Markdown?**
  - Plain text formatting syntax
  - Widely used for documentation, README files, and web content
  - VS Code's built-in Markdown support

- **Setting Up for Markdown**
  - Creating `.md` files
  - Markdown preview (`Ctrl+Shift+V` / `Cmd+Shift+V`)
  - Side-by-side preview (`Ctrl+K V` / `Cmd+K V`)

#### 2.2 Core Markdown Syntax (25 minutes)

Students will work with the example files provided:

- **Text Formatting** (using `examples/basic-formatting.md`)
  - Headers (`#`, `##`, `###`)
  - Bold (`**bold**`) and italic (`*italic*`)
  - Strikethrough (`~~strikethrough~~`)
  - Code inline (`` `code` ``) and blocks (``` ``` ```)

- **Lists and Structure** (using `examples/lists-and-structure.md`)
  - Unordered lists (`-`, `*`, `+`)
  - Ordered lists (`1.`, `2.`, etc.)
  - Nested lists
  - Blockquotes (`>`)
  - Horizontal rules (`---`)

#### 2.3 Advanced Markdown Features (15 minutes)

- **Links and Images** (using `examples/links-and-media.md`)
  - Links (`[text](url)`)
  - Images (`![alt](src)`)
  - Reference-style links

- **Tables and Extended Syntax**
  - Creating tables with pipes (`|`)
  - Table alignment
  - Task lists (`- [ ]` and `- [x]`)

---

### Hands-on Exercises

#### Exercise 1: VS Code Setup and Navigation (15 minutes)
- Clone the course repository
- Open in VS Code and explore the interface
- Practice file navigation and search
- Install Markdown extensions

#### Exercise 2: Create Your First Markdown Document (30 minutes)
- Create a new file called `my-notes.md`
- Practice basic formatting using the example files as reference
- Use live preview to see results
- Create a simple document about yourself with headers, lists, and formatting

#### Exercise 3: Work with Example Documents (15 minutes)
- Open and modify the provided example files
- Practice different Markdown features
- Use VS Code's formatting and preview tools

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
