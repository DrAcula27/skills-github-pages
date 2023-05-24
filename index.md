---
Title: Markdown Cheat Sheet
---

This Cheat Sheet can be found at [The Markdown Guide](https://www.markdownguide.org).

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

### For a GitHub friendly Markdown Cheat Sheet, check out [GitHub's wiki](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

<table>
  <tr>
    <th> Element </th>
    <th> Markdown Syntax </th>
    <th> Output </th>
  </tr>
  <tr>
    <td rowspan="6"> <h3><a href="https://www.markdownguide.org/basic-syntax/#headings">Headings</a></h3> </td>
    <td> # H1 </td>
    <td> <h1> H1 </h1> </td>
  </tr>
  <tr>
    <td> ## H2 </td>
    <td> <h2> H2 </h2> </td>
  </tr>
  <tr>
    <td> ### H3 </td>
    <td> <h3> H3 </h3> </td>
  </tr>
  <tr>
    <td> #### H4 </td>
    <td> <h4> H4 </h4> </td>
  </tr>
  <tr>
    <td> ##### H5 </td>
    <td> <h5> H5 </h5> </td>
  </tr>
  <tr>
    <td> ###### H6 </td>
    <td> <h6> H6 </h6> </td>
  </tr>
  <tr>
    <td rowspan="2"> <h3><a href="https://www.markdownguide.org/basic-syntax/#bold">Bold</a></h3> </td>
    <td> **bold text** </td>
    <td> <strong>bold text</strong> </td>
  </tr>
  <tr>
    <td> __bold text__ </td>
    <td> <b>bold text</b> </td>
  </tr>
  <tr>
    <td rowspan="2"> <h3><a href="https://www.markdownguide.org/basic-syntax/#italic">Italic</a></h3> </td>
    <td> _italic text_ </td>
    <td> <em>italic text</em> </td>
  </tr>
  <tr>
    <td> *italic text* </td>
    <td> <i>italic text</i> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#blockquotes-1">Blockquote</a></h3> </td>
    <td> > blockquote </td>
    <td> <blockquote> blockquote </blockquote> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#ordered-lists">Ordered Lists</a></h3> </td>
    <td> 1. First item <br> 1. Second item <br> 1. Third item </td>
    <td> <ol><li>First item</li><li>Second item</li><li>Third item</li></ol> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#unordered-lists">Unordered Lists</a></h3> </td>
    <td> - First item <br> - Second item <br> - Third item </td>
    <td> <ul><li>First item</li><li>Second item</li><li>Third item</li></ul> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#code">Code</a></h3> </td>
    <td> `code` </td>
    <td> <code>code</code> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#horizontal-rule">Horizonal Rule</a></h3> </td>
    <td> --- </td>
    <td> <hr> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#links">Link</a></h3> </td>
    <td> [link title](https://www.linkurl.com) </td>
    <td> <a href="https://www.linkurl.com">Link title</a> </td>
  </tr>
  <tr>
    <td> <h3><a href="https://www.markdownguide.org/basic-syntax/#images-1">Image</a></h3> </td>
    <td> ![alt text](https://picsum.photos/200 "random image") </td>
    <td> <img src="https://picsum.photos/200" alt="random image"/> </td>
  </tr>
</table>

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### [Table](https://www.markdownguide.org/extended-syntax/#tables)

**Syntax:**

\| Element \| Description \| <br>
\| --- \| --- \| <br>
\| Header \| Title \| <br>
\| Paragraph \| Text \| <br>

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
\: This is the definition of the first term.

Second Term <br>
\: This is one definition of the second term. <br>
\: This is another definition of the second term.

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

\- \[x] Completed Task <br>
\- \[ ] Incomplete Task

**Output:**

- [x] Completed Task
- [ ] Incomplete Task

### [Emoji](https://www.markdownguide.org/extended-syntax/#emoji)
(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

**Syntax:**

That is so funny! `:joy:`

**Output:**

That is so funny! 😂

### [Highlight](https://www.markdownguide.org/extended-syntax/#highlight) <br>
_**GitHub does not support highlighting text**_

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
