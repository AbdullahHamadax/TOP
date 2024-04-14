Version: English
=======================
HTML (**H**ypertext **M**arkup **L**anguage) is a markup language for creating hypertext documents, meaning that with HTML, you declare what is to be displayed to the viewer.

HTML5 is declared with `<!DOCTYPE html>`

> Notes below include HTML5 tag elements

### Classes and IDs

Classes and IDs help reference HTML elements more easily when working with CSS and JavaScript. Classes are used on one or more tag elements, often used for referencing elements when used with CSS. IDs are used to reference a single element, typically used with JavaScript.

```HTML
<div id="uniq-id"></div>
<div class="again haha"></div>
<div class="again other"></div>
<div class="again haha"></div>
<div class="again"></div>
```

### Headings

Headings are used to describe the topic they precede. Tag elements from \<**h1**\> **\-\>** \<**h6**\> correspond from most important to least important.

### Paragraphs
Tags| Meaning, usage
--|--
\<**p**\> | defines a paragraph of text
\<**br**\> | line break
\<**pre**\> | display content exactly as it is in HTML, preserving spaces, line breaks, etc.

### Text Formatting

Tags| Meaning, usage
:--:|--
\<**mark**\> | mark highlighted text <mark>highlight</mark>
\<**strong**\> | marks content as <strong>important</strong>, typically displayed as bold
\<**b**\>  | <b>bold</b> content
\<**em**\>  | marks <em>emphasized text</em>, typically displayed as italicized
\<**i**\>  | <i>italicize</i> content
\<**u**\>  | <u>underline</u> content
\<**abbr**\>  | marks an abbreviation with a title attribute <abbr title="abbreviation">ABBR</abbr>
\<**sup**\>   | marks <sup>superscript</sup>
\<**sub**\>  |  marks <sub>subscript</sub>

### Anchors and Hyperlinks

Some common parameters used in the \<**a**\> tag include: `href`, `rel`, `target`, `title`, `download`.
| Case  | Meaning  |
|---|---|
| \<a href="htpps://link.com"\>Link\</a\> | Link to another site  |
|\<a href="htpps://link.com"\ rel="external">Link\</a\> | link to another site with relationship expressed through `rel=""`|
|\<a href="htpps://link.com"\ target="_blank">Link\</a\> | link to another site and open it in a new window/tab indicated by `target="_blank"` or could be opened in the same window,...|
|\<a href="tel:123456789"\>Call me\</a>| when clicked, it will switch to software to make a call|
|\<a href="mailto:example@test.com"\>Send email\</a\>| when clicked, it will switch to software to send an email|

### Lists

\<ol\> defines an ordered list, \<ul\> defines an unordered list, and \<li\> defines list items.

```HTML
<ol type="a">
  <li>Items</li>
    <ul>
      <li> nested unordered list item </li>
      <li> nested unordered list item </li>
      <li> nested unordered list item </li>
    </ul>
  <li>Items</li>
  <li>Items</li>
  <li>Items f</li>
  <li>Items g</li>
</ol>
```

<ol type="a">
  <li>Items</li>
    <ul>
      <li> nested unordered list item </li>
      <li> nested unordered list item </li>
      <li> nested unordered list item </li>
    </ul>
  <li>Items</li>
  <li>Items</li>
  <li>Items f</li>
  <li>Items g</li>
</ol>

Additionally, there are description lists with \<dl\>, \<dt\>, \<dd\> tags.

### Tables

Presented in a tabular form with cells, rows, and columns.

```HTML
<table>
  <caption>Table Title</caption>

  <tr>
    <th>Column Header 1</th>
    <th>Column Header 2</th>
    <th> Column Header 3</th>
  </tr>

  <tr>
    <td> Row 1 col 1</td>
    <td> Row 1 col 2</td>
    <td> Row 1 col 3</td>
  </tr>
  <tr>
    <td colspan="3"> row 2; spans all 3 cols</td>
  </tr>
  <tr>
    <td rowspan="2"> spans row 3 + 4; col 1</td>
    <td> Row 3 col 2</td>
    <td> Row 3 col 3</td>
  </tr>
  <tr>
    <td> Row 4 col 2</td>
    <td> Row 4 col 3</td>
  </tr>
</table>
```

<table>
  <caption>Table Title</caption>

  <tr>
    <th>Column Header 1</th>
    <th>Column Header 2</th>
    <th>Column Header 3</th>
  </tr>

  <tr>
    <td> Row 1 col 1</td>
    <td> Row 1 col 2</td>
    <td> Row 1 col 3</td>
  </tr>
  <tr>
    <td colspan="3"> row 2; spans all 3 cols</td>
  </tr>
  <tr>
    <td rowspan="2"> spans row 3 + 4; col 1</td>
    <td> Row 3 col 2</td>
    <td> Row 3 col 3</td>
  </tr>
  <tr>
    <td> Row 4 col 2</td>
    <td> Row 4 col 3</td>
  </tr>
</table>

For clearer table layout, we can use \<thead\>, \<tbody\>, \<tfoot\>.

### Div element, Sectioning elements, Media elements, Iframes, Images

The \<div\> tag is used to group other elements and is used to organize elements in a web page. It's a powerful tool in web design. Avoid nesting too many \<div\> tags (try not to nest more than 6 levels). Instead, use HTML5 introduced tags like \<article\> (wraps sections of content that are related to each other), \<section\> (wraps a specific part of content), \<nav\> (wraps the navigation links of a web page), \<fieldset\
