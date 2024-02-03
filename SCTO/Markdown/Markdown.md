## Markdown 

To use Obsidian to its full extent, you need to know the Markdown language. It's a very simple formatting language. Markdown is a simple and lightweight way to format plain text, using symbols like #, *, and _ to create headings, lists, bold, italic, and more. Obsidian is a note-taking application that uses Markdown as the primary format for notes.

Obsidian supports the basic Markdown syntax, as well as some advanced features like tables, fenced code blocks, syntax highlighting, footnotes, and strikethrough. Obsidian also has its own flavor of Markdown, which adds some extra features like internal links, wikilinks, embeds, aliases, tags, and transclusions.

Obsidian’s Markdown support makes it easy to create, edit, and format notes, as well as to link them together and create a network of knowledge. You can also use Obsidian to publish your notes to the internet, or export them to other formats.

| Element                     | Code                            | Output                         |
|-----------------------------|---------------------------------|--------------------------------|
| Internal Link               | `[[Note Name]]`                 | [Note Name](#markdown)          |
| External Link               | `[Link Text](https://google.com)`| [Link Text](https://google.com) |
| Bold                        | `**text**`                      | **text**                       |
| Preformatted Text (for code)| `` `code goes here` ``           | `code goes here`                |
| Adding Image                | `![Image Title](IMAGE_URL)`      | ❤                              |
| Headings                    | `# Heading text`                 | # Heading Text                 |
| Sub Headings                | `## Heading text`                | ## Heading Text                |
| List (bullet points)        | `- One<br>- Two`                 | - One<br>- Two                 |
| List (numbered)             | `1. One<br>2. Two`               | 1. One<br>2. Two               |

>You can use Obsidian without using Markdown - but if you want to format the notes, you'll need Markdown.

### An example of Markdown in Obsidian
Here is a sample note that uses some basic and advanced Markdown features:


# My Markdown Note

This is a paragraph with some **bold** and *italic* text.

This is a list of items:

- Item 1
- Item 2
- Item 3

This is a table:

| Name | Age | Occupation |
| ---- | --- | ---------- |
| Alice | 25 | Teacher |
| Bob | 32 | Engineer |
| Carol | 28 | Writer |

This is a code block with syntax highlighting:

```python
def hello(name):
    print(f"Hello, {name}!")
````

[This is a footnote](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)[1](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax).

This is an internal link to another note: [[Another note]]

This is a wikilink to a note that doesn’t exist yet: [[New note]]

This is an embed of an image: ![[Zettelkasten steps.png]]

This is an alias for a link: [[Another note|A different name]]

This is a tag: #markdown

This is a transclusion of another note: {{embed: [[👓 List of Papers]]}}

[](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)[1](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax): This is the footnote text.

```

I hope this example helps you understand how to use Markdown in Obsidian. 😊
```