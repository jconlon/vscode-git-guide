# Basic Markdown Formatting

This document demonstrates fundamental Markdown formatting techniques that every user should know.

## Headers

Markdown supports six levels of headers using the `#` symbol:

# Header Level 1
## Header Level 2
### Header Level 3
#### Header Level 4
##### Header Level 5
###### Header Level 6

## Text Formatting

### Bold and Italic

You can make text **bold** using double asterisks or __double underscores__.

You can make text *italic* using single asterisks or _single underscores_.

You can combine them for ***bold and italic*** text.

### Strikethrough

You can ~~cross out~~ text using double tildes.

## Code Formatting

### Inline Code

Use backticks to create `inline code` within a sentence. This is useful for mentioning `variables`, `function names`, or `file paths`.

### Code Blocks

For larger code snippets, use triple backticks:

```
This is a basic code block
You can put any text here
No syntax highlighting
```

#### Language-Specific Code Blocks

You can specify a language for syntax highlighting:

```javascript
function greetUser(name) {
    console.log(`Hello, ${name}!`);
    return `Welcome to our application, ${name}`;
}

greetUser("World");
```

```python
def calculate_area(radius):
    """Calculate the area of a circle."""
    import math
    return math.pi * radius ** 2

# Example usage
circle_area = calculate_area(5)
print(f"Area: {circle_area:.2f}")
```

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <h1>Welcome to My Site</h1>
    <p>This is a sample HTML document.</p>
</body>
</html>
```

## Paragraphs and Line Breaks

This is the first paragraph. To create a new paragraph, simply leave a blank line between blocks of text.

This is the second paragraph. Notice the space between this and the previous paragraph.

To create a line break within the same paragraph,  
add two spaces at the end of a line  
and then press Enter.

## Practice Exercise

Try editing this document to practice these formatting techniques:

1. Create a new header below this list
2. Write a paragraph with **bold**, *italic*, and `inline code`
3. Add a code block in your favorite programming language
4. Experiment with different header levels

---

*Remember: The best way to learn Markdown is by practicing these techniques yourself!*