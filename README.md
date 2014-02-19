# Confluence Wiki Markup Package

This repository aims to provide a full featured Sublime Text 3 package that
provides a language for working with the wiki markup syntax from the
[Confluence][1] product by Atlassian.

Initially, this package will focus on the language and scope definitions to
support generic and targeted syntax highlighting provided by themes. When
defining the scope, the closest representation to a built-in type will be used.
This will hopefully allow most themes to be able to make sense of some of the
basic syntax rules. However, not every component in the wiki markup can easily
be represented by a generic scope, so in those instances, a unique and targeted
scope will be defined, which will require explicit theme support.

The second focus of the package will include providing basic snippets for some
of the more commonly used constructs in the language. My aim is to provide a
robust set of snippets and enhance them with actual completion support by
providing Sublime Text with a completion script.

## Syntax Highlighting

Currently the scopes are a little over-defined at this point and most likely
will change in the near future. Basic support was added to allow most themes to
get a general idea of what to highlight. However, to take full advantage of the
language a theme will need to have more specific rules for the language.

## Snippet Support

A number of utility snippets have been added to aid in quickly writing valid
markup for Confluence. Completion isn't in place at this point, so a list of
current snippets and their completion keys are provided below. To invoke the
snippet, simply type the word and hit tab.

* **1** through **6** - Inserts a header (h1 though h6) with a blank line
after.
* **anc** - Inserts an anchor macro.
* **code** - Inserts a code block.
* **color** - Inserts a color macro.
* **div** - Inserts a div macro with a blank line in between.
* **info** - Inserts an info macro.
* **note** - Inserts a note.
* **panel** - Inserts a panel with a blank line in between.
* **section** - Inserts a section with a blank line in between.
* **stat** - Inserts a grey status macro.
* **stat_n_** - Inserts a colored macro where the last letter is the color.
`statb` - blue, `statg` - green, `statr` - red, `staty` - yellow.
* **`|`** (single vertical pipe) - Continues a table cell by wrapping the
cursor in a pair of single vertical bars. Best used when using the
<kbd>end</kbd>, <kbd>tab</kbd> key sequence.
* **`|| `** (two vertical pipes with a space after) - Continues a table header
by wrapping the cursor in a pair of dual vertical bars. Best used when using
the <kbd>end</kbd>, <kbd>tab</kbd> key sequence as the <kbd>end</kbd> will go
to the end of the line (including the whitespace).
* **toc** - Inserts a table of contents with some sensible defaults.
* **tip** - Inserts a tip.
* **warning** - Inserts a warning.



  [1]: https://www.atlassian.com/software/confluence/
