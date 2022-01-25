# Coding and other technical content

**Material for Mkdocs, like many static site generators, was specifically designed to support technical documentation projects. As a result, it offers a range of powerful features to support display code-based learning content.**

## Presenting code

Code can be presented inline: for example `#!python range()`.

Material for Mkdocs also provides enhanced support for code blocks. The example below showcases a range of the tools available, including:

* Specifying a code-block title
* Custom line numbering of code.
* The ability to highlight individual lines.
* The ability to specify the syntax-specific code highlighting to be used (in this case Python).
* Adding an annotation to a code-block.
* Copy to clipboard as default.


``` py title="bubble sort example" linenums="4" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i): #(1)
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

1.  I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

## Integrating Jupyter notebooks

Jupyter notebooks can be integrated into Mkdocs like any other markdown file, using plugins such as [mkdocs-jupyter](https://github.com/danielfrg/mkdocs-jupyter) and [mknotebooks](https://github.com/greenape/mknotebooks).

 By default the state of the notebook, including output cells, will be integrated. Both plugins also provide the option to execute the notebooks when the documentation is built.

## Additional plugins

A large number of additional [plugins and themes](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Plugins) are available for Mkdocs that support a range of additonal functionality.