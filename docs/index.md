# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout
Documentation Tools

Software documentation tools are very important in software development. It is like a compass for your team. Documentation acts as a reference guide explaining how it works, how it operates, and how to use it.
MkDocs

MkDocs is a fast, simple, and downright gorgeous static site generator that's geared towards building project documentation

MkDocs Installation
python3 --version
pip --version
pip install mkdocs
Mkdocs --version

Material Theme
pip install mkdocs-material

Highlighting

Enables highlighting of source code in code blocks using the highlight.js JavaScript library. Default: True.

hljs_style
The highlight.js library provides 79 different styles (color variations) for highlighting source code in code blocks. Set this to the name of the desired style.

Default: github

hljs_languages

By default, highlight.js only supports 23 common languages. List additional languages here to include support for them.
analytics
Defines configuration options for an analytics service. Currently, only Google Analytics v4 is supported via the gtag option.

gtag

To enable Google Analytics, set to a Google Analytics v4 tracking ID, which uses the G- format. See Google's documentation to Set up Analytics for a website and/or app (GA4) or to Upgrade to a Google Analytics 4 property.

theme:
    name: mkdocs
    analytics:
        gtag: G-ABC123
When set to the default (null) Google Analytics is disabled for the site.
shortcuts: 
Defines keyboard shortcut keys.

help: 

Display a help modal which lists the keyboard shortcuts. Default: 191 (?)
next: 

Navigate to the "next" page. Default: 78 (n)
previous: 

Navigate to the "previous" page. Default: 80 (p)

search: 

Display the search modal. Default: 83 (s)
navigation_depth: The maximum depth of the navigation tree in the sidebar. Default: 2.
nav_style: 

This adjusts the visual style for the top navigation bar; by default, this is set to primary (the default), but it can also be set to dark or light.

locale: 

The locale (language/location) used to build the theme. If your locale is not yet supported, it will fallback to the default.






