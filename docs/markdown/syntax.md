# Markdown syntax

## Overview

Remember what I said before? Markdown powers your notepad to run some basic Word functions. Almost all markdown editors and renders support listed features.

## Headings

In order to create a headings in Markdown, the number sign(#) helps you to do that.

| Markdown         | Output           |
| ---------------- | ---------------- |
| `# Level 1`      | <h1>Level 1</h1> |
| `## Level 2`     | <h2>Level 2</h2> |
| `### Level 3`    | <h3>Level 3</h3> |
| `#### Level 4`   | <h4>Level 4</h4> |
| `##### Level 5`  | <h5>Level 5</h5> |
| `###### Level 6` | <h6>Level 6</h6> |

As you can see, the number of '#' indicates the heading level.

## Paragraphs

### Organizations

Just use a blank line to separate two paragraphs.

```markdown linenums="1"
This is the first paragraph.

This is the second paragraph.
```

### Line breaks

Like LaTeX, markdown treats two adjacent lines in the same paragraph, so it won't add an auto line break between them. We need to use `<br>` to make a explicit hint.

```markdown
This is the first line.<br>This is the second line.
```

## Emphasis

### Bold

To bold some text, add two pairs of asterisks before and after them.

```markdown
I need to **bold this**.
```

### Italic
Be careful! It is different from bold, and we only need to put single pair of asterisk before and after the text.

```markdown
I need to make it *italic*.
```

### Bold and italic
Using your logical thinking, the combination of bold and italic is add three pairs of asterisks!

```markdown
Make it ***bold and italic***.
```