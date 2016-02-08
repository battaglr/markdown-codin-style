# Markdown Codin’ Style

This document only defines style and formatting rules for writing Markdown
documents. It’s based on personal preferences and doesn’t pretend to be the
“one and only” way of doing it.

## Whitespace

- Use Unix newline character: `LF`.
- Line length should be 80 characters or less.
- Use two spaces per indentation level.
- Remove all trailing whitespace that’s not intended to generate a line break.
- Always end files with a newline.

_Psst, you may want to check my [presentation about whitespace]
(http://speakerdeck.com/battaglr/why-you-should-care-about-whitespace)_.

## Headings

- Use one to six hash characters to declare headings.
- Leave one space after the hash.
- Never use hash characters at the end.
- Insert a blank line after the heading.

```md
#·Foobar¬
¬
```

## Paragraphs

Insert a blank line after each paragraph.

```md
This is a paragraph.¬
¬
```

### Line breaks

Use two spaces to declare (hard) line breaks.

```md
Foo··
bar
```

## Emphasis

Wrap text with asterisks to indicate emphasis.

```md
Emphasis is usually displayed as *italics*, and strong emphasis as **bold**.
```

Wrap text with underscores when nesting emphasis declarations.

```md
*You can nest __emphasis__ declarations*.
```

## Lists

- Leave one space after the list marker.
- Avoid separating list items with blank lines.

```md
-·Foo
-·Bar
```

### Ordered

Use decimal numbers followed by a dot to declare an ordered list item.

```md
1. Foo
2. Bar
```

### Unordered

Use a dash to declare an unordered list item.

```md
- Foo
- Bar
```

## Horizontal rules

- Use three consecutive dash characters to declare an horizontal rule.
- Insert a blank line before and after.

```md
¬
---
¬
```

## Notice

The formatting rules described in this document are compliant with the original
[Markdown](http://daringfireball.net/projects/markdown/syntax) syntax and the
[CommonMark](http://commonmark.org/) specification.

## License

Do whatever you want with this, it’s public domain.
