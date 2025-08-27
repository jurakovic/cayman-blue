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

### Configuration

The theme can be customized using the following options in `_config.yml` file:

##### Display Options
- `show_header`: `true`/`false` - controls visibility of the page header
- `show_footer`: `true`/`false` - controls visibility of the page footer
- `custom_css`: `true`/`false` - enables loading of custom CSS file

##### Theme Options
- `dark_theme`: `true`/`false` - enables dark theme support (thanks to [Dark Reader](https://github.com/darkreader/darkreader?tab=readme-ov-file#using-dark-reader-on-a-website))

##### Link Behavior
- `target_blank`: Controls which links should open in new tab (`target="_blank"`). Options:
  - Single area: `[main]`, `[header]`, or `[footer]`
  - Multiple areas: `[header, main, footer]`
  - Note: Links that point to sections within the current page will always open in the same tab

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
