---
title: Markdown Syntax Guide
date: 2025-01-01
authors:
  - name: joelabc
    link: https://github.com/joelabc
    image: https://github.com/joelabc.png
tags:
  - Markdown
  - Example
  - Guide
excludeSearch: true
type: blog
---

This article offers a sample of basic Markdown syntax that can be used in Hugo content files.

<!--more-->

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Basic Syntax

### Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Emphasis

```text
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

_This text will be italic_

_This will also be italic_

**This text will be bold**

**This will also be bold**

_You **can** combine them_

### Lists

#### Unordered

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

- Item 1
- Item 2
  - Item 2a
  - Item 2b

#### Ordered

```
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

### Images

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Links

```markdown
[Hugo](https://gohugo.io)
```

[Hugo](https://gohugo.io)

### Blockquotes

```markdown
As Newton said:

> If I have seen further it is by standing on the shoulders of Giants.
```

> If I have seen further it is by standing on the shoulders of Giants.

### Inline Code

```markdown
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

### Code Blocks

#### Syntax Highlighting

````markdown
```go
func main() {
    fmt.Println("Hello World")
}
```
````

```go
func main() {
    fmt.Println("Hello World")
}
```

### Tables

```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

## References

- [Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
- [Hugo Markdown](https://gohugo.io/content-management/formats/#markdown)
