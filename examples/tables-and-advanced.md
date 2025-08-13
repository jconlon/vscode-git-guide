# Tables and Advanced Markdown Features

This document covers tables, advanced formatting techniques, and extended Markdown syntax.

## Basic Tables

Tables are created using pipes (`|`) to separate columns and dashes (`-`) to separate the header row:

| Name | Age | City |
|------|-----|------|
| Alice | 28 | New York |
| Bob | 34 | San Francisco |
| Carol | 25 | Chicago |

## Table Alignment

You can align columns using colons (`:`) in the separator row:

| Left Aligned | Center Aligned | Right Aligned |
|:-------------|:--------------:|--------------:|
| Left | Center | Right |
| This text | is aligned | differently |
| in each | column | 123.45 |

## Programming Languages Comparison

| Language | Type | Difficulty | Use Case | Learning Resources |
|:---------|:----:|:----------:|----------|:-----------------:|
| **Python** | Interpreted | Beginner | Data Science, Web | [Python.org](https://python.org) |
| **JavaScript** | Interpreted | Beginner | Web Development | [MDN Docs](https://developer.mozilla.org) |
| **Java** | Compiled | Intermediate | Enterprise Apps | [Oracle Docs](https://docs.oracle.com) |
| **C++** | Compiled | Advanced | System Programming | [CPP Reference](https://cppreference.com) |
| **Rust** | Compiled | Advanced | Systems, Performance | [Rust Book](https://doc.rust-lang.org) |

## VS Code Extensions Comparison

| Extension | Category | Rating | Purpose | Price |
|-----------|----------|:------:|---------|:-----:|
| **GitLens** | Version Control | ⭐⭐⭐⭐⭐ | Enhanced Git capabilities | Free |
| **Prettier** | Formatting | ⭐⭐⭐⭐⭐ | Code formatting | Free |
| **Live Server** | Development | ⭐⭐⭐⭐ | Local development server | Free |
| **Markdown All in One** | Documentation | ⭐⭐⭐⭐⭐ | Markdown support | Free |
| **Thunder Client** | API Testing | ⭐⭐⭐⭐ | REST API testing | Freemium |

## Complex Table Example

Here's a more complex table showing project planning information:

| Phase | Tasks | Duration | Dependencies | Status | Notes |
|:------|:------|:--------:|:-------------|:------:|:------|
| **Planning** | Requirements gathering<br>Architecture design<br>Timeline creation | 2 weeks | None | ✅ Complete | Initial scope defined |
| **Development** | Backend API<br>Database setup<br>Frontend components | 6 weeks | Planning complete | 🔄 In Progress | 60% complete |
| **Testing** | Unit tests<br>Integration tests<br>User acceptance | 2 weeks | Development > 80% | ⏳ Pending | Test plan ready |
| **Deployment** | Production setup<br>Go-live<br>Monitoring | 1 week | Testing complete | ⏳ Pending | Infrastructure ready |

## Task Lists and Checkboxes

### Project Checklist

- [x] ~~Set up development environment~~
- [x] ~~Create project repository~~
- [x] ~~Design database schema~~
- [ ] Implement user authentication
  - [x] Login functionality
  - [x] Registration process
  - [ ] Password reset
  - [ ] Email verification
- [ ] Build core features
  - [ ] User dashboard
  - [ ] Data visualization
  - [ ] Export functionality
- [ ] Testing and deployment
  - [ ] Write unit tests
  - [ ] Performance testing
  - [ ] Security audit

### Learning Goals

- [x] **Week 1:** Master VS Code basics
  - [x] Interface navigation
  - [x] File management
  - [x] Extensions installation
- [ ] **Week 2:** Markdown proficiency
  - [x] Basic syntax
  - [ ] Tables and lists
  - [ ] Advanced formatting
- [ ] **Week 3:** Git fundamentals
  - [ ] Repository creation
  - [ ] Commit and push
  - [ ] Branching basics

## Keyboard Shortcuts Table

| Action | Windows | Mac | Linux |
|--------|---------|-----|-------|
| **File Operations** |
| New File | `Ctrl+N` | `Cmd+N` | `Ctrl+N` |
| Open File | `Ctrl+O` | `Cmd+O` | `Ctrl+O` |
| Save | `Ctrl+S` | `Cmd+S` | `Ctrl+S` |
| **Navigation** |
| Command Palette | `Ctrl+Shift+P` | `Cmd+Shift+P` | `Ctrl+Shift+P` |
| Quick Open | `Ctrl+P` | `Cmd+P` | `Ctrl+P` |
| Go to Line | `Ctrl+G` | `Cmd+G` | `Ctrl+G` |
| **Editing** |
| Multi-cursor | `Alt+Click` | `Option+Click` | `Alt+Click` |
| Select All Occurrences | `Ctrl+Shift+L` | `Cmd+Shift+L` | `Ctrl+Shift+L` |
| **Markdown Specific** |
| Preview | `Ctrl+Shift+V` | `Cmd+Shift+V` | `Ctrl+Shift+V` |
| Side Preview | `Ctrl+K V` | `Cmd+K V` | `Ctrl+K V` |

## HTML in Markdown

You can use HTML tags for advanced formatting:

<details>
<summary>Click to expand advanced topics</summary>

### HTML Elements

You can use HTML when Markdown isn't sufficient:

<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
<strong>Important Note:</strong> This is a highlighted box using HTML div tags.
</div>

<br>

<table>
<tr style="background-color: #e1f5fe;">
<th>Feature</th>
<th>Markdown</th>
<th>HTML Required</th>
</tr>
<tr>
<td>Bold Text</td>
<td>✅</td>
<td>❌</td>
</tr>
<tr>
<td>Colored Text</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td>Complex Tables</td>
<td>Limited</td>
<td>✅</td>
</tr>
</table>

</details>

## Emoji and Special Characters

### Common Emojis

| Category | Emojis |
|----------|--------|
| **Status** | ✅ ❌ ⏳ 🔄 ⚠️ |
| **Development** | 💻 🖥️ 📱 ⚙️ 🔧 |
| **Success** | 🎉 🚀 ⭐ 👍 💯 |
| **Learning** | 📚 🎓 💡 🔍 📝 |

### Git Workflow with Emojis

| Stage | Emoji | Description |
|-------|-------|-------------|
| Planning | 📋 | Initial planning and requirements |
| Development | 👨‍💻 | Active coding phase |
| Testing | 🧪 | Testing and quality assurance |
| Bug Fix | 🐛 | Fixing identified issues |
| Documentation | 📚 | Writing or updating docs |
| Deployment | 🚀 | Releasing to production |
| Hotfix | 🔥 | Critical production fixes |

## Mathematical Expressions

Some Markdown processors support LaTeX-style math:

Inline math: `$E = mc^2$`

Block math:
```
$$
\sum_{i=1}^{n} x_i = x_1 + x_2 + \cdots + x_n
$$
```

*Note: Math rendering depends on your Markdown processor*

## Code Tables

Comparing different programming approaches:

| Language | Hello World | Variables | Comments |
|----------|-------------|-----------|----------|
| **Python** | `print("Hello World")` | `name = "Alice"` | `# This is a comment` |
| **JavaScript** | `console.log("Hello World")` | `let name = "Alice"` | `// This is a comment` |
| **Java** | `System.out.println("Hello World")` | `String name = "Alice";` | `// This is a comment` |
| **C++** | `cout << "Hello World" << endl;` | `string name = "Alice";` | `// This is a comment` |

## Practice Exercises

### Exercise 1: Create Your Own Table
Create a table comparing your three favorite tools or applications:

*Your table here*

### Exercise 2: Advanced Task List
Create a nested task list for a project you're working on:

*Your task list here*

### Exercise 3: Keyboard Shortcuts
Create a table of your most-used keyboard shortcuts:

*Your shortcuts table here*

---

## Tips for Better Tables

1. **Keep it simple**: Don't overcomplicate table structure
2. **Use alignment**: Right-align numbers, center-align short text
3. **Be consistent**: Use consistent formatting within columns
4. **Consider alternatives**: Sometimes lists are clearer than tables
5. **Test rendering**: Check how your tables look in different viewers

### Common Table Mistakes

❌ **Don't do this:**
- Inconsistent spacing
- Too many columns (becomes unreadable)
- Missing header separators
- Mixing data types in columns

✅ **Do this instead:**
- Clean, consistent formatting
- Logical column organization
- Clear headers
- Appropriate use of alignment

---

*Tables are powerful tools for organizing information. Practice creating different types to master this skill!*