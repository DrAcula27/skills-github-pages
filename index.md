---
Title: Markdown Cheat Sheet
---

This Cheat Sheet can be found at [The Markdown Guide](https://www.markdownguide.org).

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

### For a GitHub friendly Markdown Cheat Sheet, check out [GitHub's wiki](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

| Element | Markdown Syntax | Output |
| --- | --- | --- |
| [Headings](https://www.markdownguide.org/basic-syntax/#headings) | # H1 <br> <br> ## H2 <br> <br> ### H3 <br> <br> #### H4 <br> <br> ##### H5 <br> <br> ###### H6 | # H1 <br> <h2> H2 </h2> <br> <h3> H3 </h3> <br> <h4> H4 </h4> <br> <h5> H5 </h5> <br> <h6> H6 </h6> |
| [Bold](https://www.markdownguide.org/basic-syntax/#bold) | \*\*bold text\*\* <br> \_\_bold text\_\_ | **bold text** <br> __bold text__ |
| [Italic](https://www.markdownguide.org/basic-syntax/#italic) | \_italicized text\_ <br> \*italicized text\* | _italicized text_ <br> *italicized text* |
| [Blockquote](https://www.markdownguide.org/basic-syntax/#blockquotes-1) | \> blockquote | <blockquote> blockquote </blockquote> |
| [Ordered List](https://www.markdownguide.org/basic-syntax/#ordered-lists) | 1. First item <br> 2. Second item <br> 3. Third item | <ol><li>First item</li><li>Second item</li><li>Third item</li></ol> |
| [Unordered List](https://www.markdownguide.org/basic-syntax/#unordered-lists) | - First item <br> - Second item <br> - Third item | <ul><li>First item</li><li>Second item</li><li>Third item</li></ul> |
| [Code](https://www.markdownguide.org/basic-syntax/#code) | \`code\` | `code` |
| [Horizontal Rule](https://www.markdownguide.org/basic-syntax/#horizontal-rules) | --- | <hr> |
| [Link](https://www.markdownguide.org/basic-syntax/#links) | \[title]\(https://www.linkurl.com) | [title](https://www.linkurl.com) |
| [Image](https://www.markdownguide.org/basic-syntax/#images-1) | \![alt text]\(https://picsum.photos/200 "random image") | ![alt text](https://picsum.photos/200 "random image") |

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### [Table](https://www.markdownguide.org/extended-syntax/#tables)

**Syntax:**

\| Element | Description | <br>
\| --- | --- | <br>
\| Header | Title | <br>
\| Paragraph | Text | <br>

**Output:**

| Element | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |

### [Fenced Code Block](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks)

**Syntax:**

\`\`\` <br>
{ <br>
&nbsp; "firstName": "John", <br>
&nbsp; "lastName": "Smith", <br>
&nbsp; "age": 25 <br>
} <br>
\`\`\`

**Output:**

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### [Footnote](https://www.markdownguide.org/extended-syntax/#footnotes)

**Syntax:**

Here's a sentence with a footnote. \[^1]

\[^1]: This is the footnote.

**Output:**

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### [Heading ID](https://www.markdownguide.org/extended-syntax/#heading-ids)

**Syntax:** <br>
_To get desired output in GitHub, use HTML_

\### My Great Heading \{#custom-id}

**Output:**

<h3 id="custom-id">My Great Heading</h3>

### [Definition List](https://www.markdownguide.org/extended-syntax/#definition-lists)

**Syntax:** <br>
_To get desired output in GitHub, use HTML_

First Term <br>
: This is the definition of the first term.

Second Term <br>
: This is one definition of the second term. <br>
: This is another definition of the second term.

**Output:**

<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>

### [Strikethrough](https://www.markdownguide.org/extended-syntax/#strikethrough)

**Syntax:**

\~~The world is flat.~~

**Output:**

~~The world is flat.~~

### [Task List](https://www.markdownguide.org/extended-syntax/#task-lists)

**Syntax:**

\- [x] Completed Task <br>
\- [ ] Incomplete Task

**Output:**

- [x] Completed Task
- [ ] Incomplete Task

### [Emoji](https://www.markdownguide.org/extended-syntax/#emoji)
(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

**Syntax:**

That is so funny! `:joy:`

**Output:**

That is so funny! :joy:

### [Highlight](https://www.markdownguide.org/extended-syntax/#highlight) $${\color{red}!!Does \space not \space work \space in \space GitHub \space .md \space files!!}$$

**Syntax:**

I need to highlight these ==very important words==.

### [Subscript](https://www.markdownguide.org/extended-syntax/#subscript)

**Syntax:** <br>
_To get desired output in GitHub, use HTML_

H\~2\~O

**Output:**

H<sub>2</sub>O

### [Superscript](https://www.markdownguide.org/extended-syntax/#superscript)

**Syntax:** <br>
_To get desired output in GitHub, use HTML_

X\^2\^

**Output:**

X<sup>2</sup>
