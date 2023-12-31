# Plugins

## Abbreviations

<https://squidfunk.github.io/mkdocs-material/reference/tooltips/#adding-abbreviations>

??? abstract "Markdown Extensions"
    - abbr

Foo

*[Foo]: This is a Tooltip that shows the abbreviations.

## Admonition

<https://squidfunk.github.io/mkdocs-material/reference/admonitions/>

??? abstract "Markdown Extensions"
    - admonition

!!! note
    This is an admonition example.

## Footnotes

<https://squidfunk.github.io/mkdocs-material/reference/footnotes/>

??? abstract "Markdown Extensions"
    - footnotes

Footnotes[^1]

[^1]: Description of the footnote1.

## Grids

<https://squidfunk.github.io/mkdocs-material/reference/grids>

??? abstract "Markdown Extensions"
    - md_in_html

<div class="grid cards" markdown>
- Block 1
- Block 2
- Block 3
- Block 4
</div>

## Collapsible Admonition Blocks

<https://squidfunk.github.io/mkdocs-material/reference/admonitions/#collapsible-blocks>

??? abstract "Markdown Extensions"
    - pymdownx.details

??? note
    Message

## Emojis

<https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/>

??? abstract "Markdown Extensions"
    - pymdownx.emoji

:smile:

## Syntax Highlighting

<https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/#highlight>

??? abstract "Markdown Extensions"
    - pymdownx.highlight
    - pymdownx.superfences

```bash
echo "Message"
echo "Message"
```

## Tabs

<https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/#tabbed>

??? abstract "Markdown Extensions"
    - pymdownx.tabbed

=== "A"
    Message A
=== "B"
    Message B

## Tasklists

<https://squidfunk.github.io/mkdocs-material/reference/lists/#using-task-lists>

??? abstract "Markdown Extensions"
    - pymdownx.tasklist

- [x] Checked List Item
- [ ] Unchecked List Item

## Tables

<https://squidfunk.github.io/mkdocs-material/reference/data-tables/>

??? abstract "Markdown Extensions"
    - tables

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |
