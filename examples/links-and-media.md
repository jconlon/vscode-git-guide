# Links, Images, and Media in Markdown

This document demonstrates how to work with links, images, and other media elements in Markdown.

## Basic Links

### Inline Links

You can create links using the format `[link text](URL)`:

- Visit [Google](https://www.google.com) for web searches
- Check out [GitHub](https://github.com) for code repositories  
- Learn more at [Stack Overflow](https://stackoverflow.com) for programming help
- Read the [Markdown Guide](https://www.markdownguide.org) for detailed syntax

### Links with Titles

You can add titles that appear on hover using `[text](URL "title")`:

- [VS Code](https://code.visualstudio.com "Microsoft's free code editor") - A powerful code editor
- [Git Documentation](https://git-scm.com/doc "Official Git documentation") - Learn version control
- [Mozilla Developer Network](https://developer.mozilla.org "Web development resources") - Web development reference

## Reference-Style Links

For cleaner text, especially with repeated links, use reference-style links:

### Method 1: Numbered References

I love working with [VS Code][1] and [Git][2]. Both [VS Code][1] and [Git][2] are essential tools for developers.

[1]: https://code.visualstudio.com "VS Code Editor"
[2]: https://git-scm.com "Git Version Control"

### Method 2: Named References

Check out these resources for learning web development:
- [HTML tutorials][html-ref] for structure
- [CSS guides][css-ref] for styling  
- [JavaScript documentation][js-ref] for interactivity

The combination of [HTML][html-ref], [CSS][css-ref], and [JavaScript][js-ref] forms the foundation of web development.

[html-ref]: https://developer.mozilla.org/en-US/docs/Web/HTML
[css-ref]: https://developer.mozilla.org/en-US/docs/Web/CSS
[js-ref]: https://developer.mozilla.org/en-US/docs/Web/JavaScript

## Automatic Links

Markdown can automatically convert URLs and email addresses:

### URLs
- https://www.example.com
- http://github.com
- https://stackoverflow.com

### Email Addresses
- contact@example.com
- support@github.com
- hello@markdown.org

## Images

### Basic Image Syntax

Images use the format `![alt text](image URL "optional title")`:

![Markdown Logo](https://markdown-here.com/img/icon256.png "Markdown Logo")

*Note: The image above might not display if you're viewing this offline*

### Images with Links

You can make images clickable by combining image and link syntax:

[![VS Code Logo](https://code.visualstudio.com/favicon.ico "Click to visit VS Code")](https://code.visualstudio.com)

### Reference-Style Images

You can also use reference-style for images:

![Git Logo][git-logo]
![GitHub Logo][github-logo]

[git-logo]: https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png "Git Version Control"
[github-logo]: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "GitHub Platform"

## Internal Links (Anchors)

You can link to sections within the same document:

### Navigation Menu
- [Go to Basic Links](#basic-links)
- [Jump to Images section](#images)
- [See Tables section](#tables-preview)
- [Go to Practice Exercises](#practice-exercises)

## File Links

Link to other files in your project:

- [README file](../README.md) - Main project documentation
- [Basic Formatting Examples](basic-formatting.md) - Learn text formatting
- [Lists and Structure](lists-and-structure.md) - Document organization

## Tables Preview

Here's a simple table showing different types of links:

| Link Type | Syntax | Example |
|-----------|---------|---------|
| Inline | `[text](url)` | [Google](https://google.com) |
| Reference | `[text][ref]` | [Example][ex] |
| Automatic | Just type URL | https://example.com |
| Email | Type email | hello@example.com |

[ex]: https://example.com

## Advanced Link Techniques

### Links in Lists

1. **Documentation Links**
   - [Markdown Syntax](https://daringfireball.net/projects/markdown/syntax)
   - [GitHub Flavored Markdown](https://github.github.com/gfm/)
   - [CommonMark Specification](https://commonmark.org/)

2. **Tool Links**
   - [VS Code Extensions](https://marketplace.visualstudio.com/)
   - [Git Commands Reference](https://git-scm.com/docs)
   - [GitHub Desktop](https://desktop.github.com/)

### Links in Blockquotes

> "The best way to learn is by doing. Start with these resources:"
> 
> - [Interactive Git Tutorial](https://learngitbranching.js.org/)
> - [VS Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)
> - [Markdown Tutorial](https://www.markdowntutorial.com/)

### Footnote-Style Links

You can create footnote-style references for academic or detailed documentation:

Markdown was created by John Gruber[^1] in 2004. It has since become widely adopted for documentation[^2] and README files[^3].

[^1]: John Gruber's original Markdown specification: https://daringfireball.net/projects/markdown/
[^2]: Many documentation platforms support Markdown: https://docs.github.com/
[^3]: GitHub README files use Markdown: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

## Escaping Special Characters

Sometimes you need to display literal characters that have special meaning in Markdown:

- To show brackets literally: \[not a link\]
- To show asterisks: \*not italic\*
- To show backticks: \`not code\`

## Practice Exercises

Try these exercises to master links and media:

1. **Create a resource list** with at least 5 links to your favorite websites
2. **Add an image** from the web (find a Creative Commons or free image)
3. **Create reference-style links** for a list of programming languages
4. **Make a table** comparing different code editors with links to each
5. **Add internal links** to create a table of contents for this document

### Your Practice Area

Use the space below to practice:

---

## Useful Link Collections

### Learning Resources
- [freeCodeCamp](https://www.freecodecamp.org/) - Free coding curriculum
- [MDN Web Docs](https://developer.mozilla.org/) - Web development reference
- [W3Schools](https://www.w3schools.com/) - Web technology tutorials

### Development Tools
- [Visual Studio Code](https://code.visualstudio.com/) - Code editor
- [Git](https://git-scm.com/) - Version control
- [GitHub](https://github.com/) - Code hosting platform
- [Stack Overflow](https://stackoverflow.com/) - Developer community

### Design Resources
- [Unsplash](https://unsplash.com/) - Free high-quality photos
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Web fonts

---

*Remember: Good documentation includes helpful links to external resources and clear navigation between sections!*