# Markdown-Cheatsheet

Markdown is a simple markup language that enables you to easily format text using a plain text editor. Here is a quick guide to the most common Markdown syntax:

### Headings

You can create headings by using one to six hash symbols (`#`). The number of hash symbols corresponds to the heading level. For example:

**Code**
```
# Heading 1
## Heading 2
### Heading 3
```

**Result**
# Heading 1
## Heading 2
### Heading 3


### Emphasis

You can emphasize text in three ways:

- *Italic*: Surround the text with a single asterisk or underscore.
- **Bold**: Surround the text with two asterisks or underscores.
- ***Bold and italic***: Surround the text with three asterisks or underscores.

You can also strikethrough text by surrounding it with two tildes (`~~`).

**Code**
```
*italic*
**bold**
***bold and italic***
~~strikethrough~~
```

**Result**
*italic*
**bold**
***bold and italic***
~~strikethrough~~


### Lists

You can create ordered and unordered lists. For unordered lists, use a hyphen (`-`), plus sign (`+`), or asterisk (`*`) as the bullet point. For ordered lists, use numbers. For example:

#### Unordered

**Code**
```
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```

**Result**
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2

#### Ordered

**Code**
```
1. Item 1
2. Item 2
   1. Subitem 1
   2. Subitem 2
```

**Result**
1. Item 1
2. Item 2
   1. Subitem 1
   2. Subitem 2


### Links

You can create links by surrounding the link text with square brackets (`[]`) and the link URL with parentheses (`()`). For example:

**Code**
```
[Link text](URL)
```

**Result**
[Link text](URL)


### Images

You can add images by using an exclamation mark (`!`) followed by square brackets for alt text and parentheses for the image URL. For example:

**Code**
```
![Alt text](https://picsum.photos/420)
```

**Result**
![Alt text](https://picsum.photos/420)


### Code

You can indicate inline code by surrounding the code with backticks (`` ` ``). To create a code block, use three backticks and specify the language (optional). For example:

#### Inline

**Code**
```
`code`
```

**Result**
`code`

#### Blocks

**Code**
````javascript
console.log('Hello world!');
````

**Result**
```javascript
console.log('Hello world!');
```


### Blockquotes

You can create blockquotes by using a greater than symbol (`>`). For example:

**Code**
```
> This is a blockquote.
```

**Result**
> This is a blockquote.


### Horizontal Rule

You can create a horizontal rule by using three or more hyphens (`---`), asterisks (`***`), or underscores (`___`).

**Code**
```
---
```

**Result**
---


### Tables

You can create tables by using vertical bars (`|`) and hyphens (`-`) to separate columns and rows, respectively. For example:

**Code**
```
| Name | Age | Gender |
|------|-----|--------|
| John | 25  | Male   |
| Jane | 30  | Female |
| Bob  | 40  | Male   |
```

**Result**
| Name | Age | Gender |
|------|-----|--------|
| John | 25  | Male   |
| Jane | 30  | Female |
| Bob  | 40  | Male   |
