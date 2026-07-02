# Introduction to Markdown

`Markdown` is a markup language.

It is used to format text in plain text.

## Workflow

To use markdown:
- Markdown file
- Markdown processor

**Markdown file** is a file with extension name `.md` or `.markdown`. Example: `Mathematics.md`.

**Markdown processor** is a program which is capable of processing markdown files. Example: `Typora`.

# Headings

## Method1
To create a heading, add <kbd>#</kbd> before the heading text:
```Markdown
# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6
```

**Key Points**
- **Levels of Heading**
    The number of `#` determins the heading level (less `#` for higher level).
    Markdown support up to 6 level of heading.
- **Prone to Error**
    There must be a space between `#` and title.

## Method2

On the line below the heading text, add any number of `=` or `-`:
```markdown
Headling Level 1
================
Heading Level 2
---------------
```

# Paragraphs

To create paragraphs, add a blank line to separate the text:
```markdown
Paragraph 1

Paragraph 2
```

# Line Breaks

To create a line break, type two or more <kbd>Space</kbd> at the end of the line, then type <kbd>Enter</kbd> to insert the next line:
```markdown
First line  
Second line
```

# Emphasis

## Bold

To bold text, two <kbd>*</kbd> or <kbd>_</kbd> warp around both side:
```markdown
**Bold Text**
__Bold Text__
```

## Italic

To Italic text, one <kbd>*</kbd> or <kbd>_</kbd> warp around both side:
```markdown
*Italic Text*
_Italic Text_
```

# Quotes

To create a block quote. use a <kbd>></kbd> before text:
```markdown
> Quote Text
```

# Lists

## Unordered

Unordered list can be created using `-`, `+` and `*` character.

```Markdown
- Item
- Item
- Item
```
or
```Markdown
+ Item
+ Item
+ Item
```
or
```Markdown
* Item
* Item
* Item
```

## Ordered

```Markdown
1. Item
1. Item
1. Item
```

**Key Point**
- Markdown can handles counting automatically.

## Task

```Markdown
- [x] Done task
- [ ] To-do task
```

# Code

## Inline Code
```
`Code`
```

To escape inline code, enclosing it with double tick mark.

## Code Block

````
```
Code
```
````

# Links

```markdown
[Text](URL "title")
```

# Image

```Markdown
![Text](URL)
```