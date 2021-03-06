# Bambu Markup

Replacements for Django's Markdown and reStructuredText support

## About Bambu Tools 2.0

This is part of a toolset called Bambu Tools. It's being moved from a namespace of `bambu` to its own
'root-level' package, along with all the other tools in the set. If you're upgrading from a version prior
to 2.0, please make sure to update your code to use `bambu_markup` rather than `bambu.markup`.

## Installation

Install the package via Pip:

```
pip install bambu-markup
```

Add it to your `INSTALLED_APPS` list:

```python
INSTALLED_APPS = (
    ...
    'bambu_markup'
)
```

## Settings

Set `MARKDOWN_EXTENSIONS` to a list of MArkdown extensions in order to further filter Markdown
text.

Set `MARKDOWN_ENABLE_ATTRIBUTES` to `True` to enable HTML attributes.


## Questions or suggestions?

Find me on Twitter (@[iamsteadman](https://twitter.com/iamsteadman))
or [visit my blog](http://steadman.io/).