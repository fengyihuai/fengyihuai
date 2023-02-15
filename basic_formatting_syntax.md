# Heading

```
# The largest heading
## The second largest heading
###### The smallest heading
```

# Styling text
You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and .md files.

|Style                  | Syntax            | Keyboard shortcut                               | Example                      | Output                     |
|-----------------------|-------------------|-------------------------------------------------|------------------------------|----------------------------|
|Bold              | `** **`or `__ __` | `Command` + `B` (Mac) or `Ctrl` + `B`(Windows/Linux) | `**This is bold text**`      | **This is bold text**      |
|Strikethrough     | `~~ ~~`           | `Command` + `I` (Mac) or `Ctrl` + `I`(Windows/Linux) | `~~This was mistaken text~~` | ~~This was mistaken text~~ |
|Bold and nested italic | `** **` and `_ _` |                            | `**This tex is _extremely_ important` | **This text is _extremely_ important** |
|All bold and italic    | `*** ***`         |                                      | `***All this text is important***` |***All this text is important*** |
|Subscript              | `<sub></sub>`     |                           | `<sub> This is a subscript text</sub>` | Hi<sub> This is a subscript text</sub> |
|Superscript            | `<sup></sup>`     |                         | `<sup>This is a superscript text</sup>` | Hi<sup>This is a superscript text</sup> |

# Quoting text
You can quote text with a `>`.

```
Text that is not a quote
> Text that is a quote
```
Text that is not a quote
> Text that is a quote

# Quoting code
You can call ou code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press `Command`+`E`(Mac) or `Ctrl`+`E`(Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

To format code or text into its own distinct block use triple backticks.
``````
Some basic Git commands are:
```
git status
git add
git commit
```
```````
Some basic Git commands are:
```
git status
git add
git commit
```

For more information, see "[Creating and highlighting code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)."

If you are frequently editing code snippets and tables, you may benefit from enablind a fixed-width font in all comment fields on Github. For more information, see "[Enabling fixed-width fonts in the editor](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github#enabling-fixed-width-fonts-in-the-editor)."

# Supported color models
In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

```
The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.
```
![example](https://docs.github.com/assets/cb-13280/images/help/writing/supported-color-models-rendered.png)

Here are the currently supported color models.
| Color           | Syntsx      | Example     | Output                                                                                                     |
|-----------------|-------------|-------------|------------------------------------------------------------------------------------------------------------|
|HEX              | `` `#RRGGBB` `` | `` `#0969DA` `` | ![HEX](https://docs.github.com/assets/cb-1560/images/help/writing/supported-color-models-hex-rendered.png) |
|RGB  | `` `rgb(R,G,B)` `` | `` `rgb(9, 105, 218)` `` | ![RGB](https://docs.github.com/assets/cb-1962/images/help/writing/supported-color-models-rgb-rendered.png) |
|HSL| `` `hsl(H,S,L)` `` | `` `hsl(212, 92%, 45%)` `` | ![HSL](https://docs.github.com/assets/cb-2068/images/help/writing/supported-color-models-hsl-rendered.png) |

Notes:
- A supperorted color model cannot have any leading or trailing spaces within the backticks.
- The visualization of the color is only supported in issues, pull requests, and discussions.

# Links
You can also create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `(  )`. You can also use the keyboard shortcut `Command`+`K` to create a automatically create a link from selectioin.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut `Command`+`V`. If you'd like to replace the text with the link, use the keyboard shortcut `Command`+`Shift`+`V`.

`This site was built using [GitHub Pages](https://pages.github.com/).`

This site was built using [GitHub Pages](https://pages.github.com/).

Tips: GitHub automatically creates links when valid URLs are written in a comment. For more information, see "[Autolinked references and URLs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls)."

# 
