---
comments: true
---

# Basic usage

!!! info
    We provide [interactive editors](#playground) at the page bottom. You could try everything you want there.

## Overview

Let's take a look at all the basic functions we need to know to finish a document.

## Headings

When we write a document, headings are always essential.

To make headings in markdown, hash(#) helps us declare them. The more hash we put before the text, the lower level it will be.

| Markdown                 | Rendered                 |
| ------------------------ | ------------------------ |
| `# Heading level 1`      | <h1>Heading level 1</h1> |
| `## Heading level 2`     | <h2>Heading level 2</h2> |
| `### Heading level 3`    | <h3>Heading level 3</h3> |
| `#### Heading level 4`   | <h4>Heading level 4</h4> |
| `##### Heading level 5`  | <h5>Heading level 5</h5> |
| `###### Heading level 6` | <h6>Heading level 6</h6> |

??? tip "Alternative method for level 1 and 2"
    ```markdown
    Heading level 1
    ===============

    Heading level 2
    ---------------
    ```

    It doesn't matter how many equal sign(=) or dash(-) we put at the next line of our headings.

## Emphasis

We can emphasize some text by making them **bold**, _italic_ and _**combining them**_.

### Bold

Add two asterisks or underscores without space around the text to **bold** them.

| Markdown | Rendered | Recommendation |
| -------- | -------- | -------------- |
| `**bold**` | **bold** | :heavy_check_mark: |
| `__bold__` | **bold** | :heavy_multiplication_x: |

!!! warning
    We should avoid using underscores inline.

    Change `fo__o__bar` to `fo**o**bar`. Make fo**o**bar easy to understand by the editors and other colleagues. 

### Italic

Italics don't emphasize as much as bolding. So we only use a pair of asterisks or underscores around.

| Markdown | Rendered | Recommendation |
| -------- | -------- | -------------- |
| `*italic*` | _italic_ | :heavy_multiplication_x: |
| `_italic_` | _italic_ | :heavy_check_mark: |

!!! warning
    If we use underscores inline. Unexpected things will happen :cry: .

    `This_is_an example.` This_is_an example.

    `This*is*another example.` This*is*another example.

### Bold and italic

Stronger than bold, so three asterisks or underscores will be used.

| Markdown | Rendered | Recommendation |
| -------- | -------- | -------------- |
| `***important***` | _**important**_ | :heavy_check_mark: |
| `___important___` | _**important**_ | :heavy_check_mark: |
| `**_important_**` | _**important**_ | :heavy_check_mark: |
| `__*important*__` | _**important**_ | :material-check-all: |

!!! warning
    If we want to use it inline, asterisks are the only choice.

    `It's so***important***` It's so***important***

## Line breaks and paragraphs

Like HTML, `<br>` could break the line. Want to start a new paragraph? Just leave a blank line in between.

```markdown
This is the first line.<br>This is the second line.
This will be connected to the previous line.

Another para.
```

This is the first line.<br>This is the second line.
This will be connected to the previous line.

Another para.

## Quotes

Add greater than sign(>) before the line to make a quote.

```markdown
> This is a quote.
>
> We can make it become a block quote.
>> Or even nest it.
```

> This is a quote.
>
> We can make it become a block quote.
>> Or even nest it.

## Tables

Adding tables in markdown is like drawing a table.

Minus sign(-) should be added to the second line of the table and use pipeline(|) to separate columns.

```markdown
|   | A | B | C |
| - | - | - | - |
| 1 | A1 | B1 | C1 |
| 2 | A2 | B2 | C2 |
| 3 | A3 | B3 | C3 |
```

|   | A | B | C |
| - | - | - | - |
| 1 | A1 | B1 | C1 |
| 2 | A2 | B2 | C2 |
| 3 | A3 | B3 | C3 |

!!! note
    The number of minus sign(-) could be different.

### Alignment

Colons(:) could help us align the text.

```markdown
|   | Left | Center | Right |
| - | :- | :-: | -: |
| 1 | A1 | B1 | C1 |
| 2 | A2 | B2 | C2 |
| 3 | A3 | B3 | C3 |
```

|   | Left | Center | Right |
| - | :- | :-: | -: |
| 1 | A1 | B1 | C1 |
| 2 | A2 | B2 | C2 |
| 3 | A3 | B3 | C3 |

!!! note
    By default, all content in the table will be left aligned(like the first column).

## Lists

## Unordered lists

To create an unordered list, minus sign(-), asterisks(*) or plus sign(+) should be placed first in the line.

```markdown
- First item
- Second item
- Third item

* Asterisk
+ Or plus sign
```

- First item
- Second item
- Third item

- Asterisk

- Or plus sign

## Playground

<textarea>
**Unleash your imaginations!**
</textarea>

<link rel="stylesheet" href="../../stylesheets/markdown.css">
<script src="https://unpkg.com/stackedit-js@1.0.7/docs/lib/stackedit.min.js"></script>
<script src="../../javascripts/markdown.js"></script>
