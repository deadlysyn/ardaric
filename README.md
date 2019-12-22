# Ardaric

This [Ghost](https://github.com/tryghost/ghost) theme is an opinionated fork of [Attila](https://attila.zutrinken.com). Still aiming to be content-focussed and responsive, with minor tweaks based on personal preferences and performance optimized.

## Screenshots

<table>
<tr>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/attila/master/src/screenshot-desktop.jpg" />
</td>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/attila/master/src/screenshot-mobile.jpg" />
</td>
</tr>
</table>

## Features

Maintained Attila features:

* Responsive layout
* Parallax cover images for blog, archives and posts
* Reading progress for posts
* Automatic line numbers for code snippets
* Disqus support

Tweaks:

* Use system font stack
* Don't auto-highlight code snippets (I prefer Prism.js)
* More responsive scaling

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus = 'YOUR_DISQUS_SHORTNAME';</script>` to your blog header.

## Development

Install [Grunt](https://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt dependencies:

	npm install

Build Grunt project:

	grunt build

The zip Grunt task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

	grunt zip

