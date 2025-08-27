# The Cayman Blue theme

> Main [README](https://github.com/jurakovic/cayman-blue/blob/master/README.md) is in master branch.

Cayman Blue is a fork of [Cayman](https://github.com/pages-themes/cayman) Jekyll theme for GitHub Pages.

It is custom theme used for some of the [jurakovic.github.io](https://jurakovic.github.io) pages. Currently it's not made for general use.  

Key differences ([compare](https://github.com/jurakovic/cayman-blue/compare/master...jurakovic:cayman-blue:cayman-blue?expand=1)):

- fixed Google Analytics scripts
- changed style (colors, fonts, sizes, paddings etc.)
- changed `<title>` tag (removed repository description)
- added favicon (non-customizable)
- changed footer content (non-customizable)
- added new configuration options (see below)

### Configuration Options

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| `show_header` | Boolean | `true` | Controls visibility of the page header |
| `show_footer` | Boolean | `true` | Controls visibility of the page footer |
| `custom_css` | Boolean | `false` | Enables loading of custom CSS file |
| `dark_theme` | Boolean | `false` | Enables dark theme support via [Dark Reader](https://github.com/darkreader/darkreader?tab=readme-ov-file#using-dark-reader-on-a-website) |
| `target_blank`* | Array | `[]` | Controls which links open in new tab* (`target="_blank"`). Values: `header`, `main`, `footer` |

> \* Links that point to sections within the current page will always open in the same tab

#### Example Configuration

```
title: My Site
description: My site description
remote_theme: jurakovic/cayman-blue
show_header: true
show_footer: true
custom_css: true
dark_theme: true
target_blank: [main, footer]
```
