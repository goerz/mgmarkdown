# mgmarkdown #

`mgmarkdown` is a personalized markdown processor, building upon the 
[Python Markdown Package][] and extending it with the math capabilities of the 
[render_math][] plugin for the [Pelican][] blogging system. The `codehilite`,
`extra`, `headerid`, `toc`, and `meta` Markdown extensions are enabled.

It is intended to generate previews of markdown articles for
<http://michaelgoerz.net>. Thus, the generated html will match the style of that
site.

[Python Markdown Package]: https://github.com/waylan/Python-Markdown
[render_math]: https://github.com/barrysteyn/pelican_plugin-render_math
[Pelican]: http://blog.getpelican.com

## Prerequisites ##

    pip install markdown

## Installation ##

    pip install mgmarkdown

This will install the `mgmarkdown` script on your system

## Usage ##

See `mgmarkdown --help`
