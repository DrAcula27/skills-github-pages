---
Title: Markdown Cheat Sheet
---

This Cheat Sheet can be found at [The Markdown Guide](https://www.markdownguide.org).

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

| Element | Markdown Syntax |
| --- | --- |
| [Headings](https://www.markdownguide.org/basic-syntax/#headings) | `# H1` <br> `## H2` <br> `### H3` <br> `#### H4` <br> `##### H5` <br> `###### H6` |
| [Bold](https://www.markdownguide.org/basic-syntax/#bold) | `**bold text**` <br> `__bold text__` |
| [Italic](https://www.markdownguide.org/basic-syntax/#italic) | `_italicized text_` <br> `*italicized text*` |
| [Blockquote](https://www.markdownguide.org/basic-syntax/#blockquotes-1) | `> blockquote` |
| [Ordered List](https://www.markdownguide.org/basic-syntax/#ordered-lists) | `1. First item` <br> `2. Second item` <br> `3. Third item` |
| [Unordered List](https://www.markdownguide.org/basic-syntax/#unordered-lists) | `- First item` <br> `- Second item` <br> `- Third item` |
| [Code](https://www.markdownguide.org/basic-syntax/#code) | `code` |
| [Horizontal Rule](https://www.markdownguide.org/basic-syntax/#horizontal-rules) | `---` |
| [Link](https://www.markdownguide.org/basic-syntax/#links) | `[title](https://www.linkurl.com)` |
| [Image](https://www.markdownguide.org/basic-syntax/#images-1) | `![alt text](image.jpg)` |

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### [Table](https://www.markdownguide.org/extended-syntax/#tables)
```
| Syntax | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |
```
| Syntax | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |

### [Fenced Code Block](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks)

<p>
``` <br>
{ <br>
&nbsp; "firstName": "John", <br>
&nbsp; "lastName": "Smith", <br>
&nbsp; "age": 25 <br>
} <br>
```

{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}

### [Footnote](https://www.markdownguide.org/extended-syntax/#footnotes)

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### [Heading ID](https://www.markdownguide.org/extended-syntax/#heading-ids)

`### My Great Heading {#custom-id}`

### My Great Heading {#custom-id}

### [Definition List](https://www.markdownguide.org/extended-syntax/#definition-lists)

```
term
: definition
```

term
: definition

### [Strikethrough](https://www.markdownguide.org/extended-syntax/#strikethrough)

```
~~The world is flat.~~
```

~~The world is flat.~~

### [Task List](https://www.markdownguide.org/extended-syntax/#task-lists)

```
- [x] Completed Task
- [ ] Incomplete Task
```

- [x] Completed Task
- [ ] Incomplete Task

### [Emoji](https://www.markdownguide.org/extended-syntax/#emoji)
(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

`That is so funny! :joy:`

That is so funny! :joy:

### [Highlight](https://www.markdownguide.org/extended-syntax/#highlight)

`I need to highlight these ==very important words==.`

I need to highlight these ==very important words==.

### [Subscript](https://www.markdownguide.org/extended-syntax/#subscript)

`H~2~O`

H~2~O

### [Superscript](https://www.markdownguide.org/extended-syntax/#superscript)

`X^2^`

X^2^
