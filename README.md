# Ardaric

This [Ghost](https://github.com/tryghost/ghost) theme is an opinionated fork of [Attila](https://attila.zutrinken.com). Still aiming to be content-focussed and responsive, with minor tweaks based on personal preferences and performance.

## Features

Maintained Attila features:

* Responsive layout
* Parallax cover images for blog, archives and posts (plan to convert to CSS)
* Reading progress for posts (brightened color)
* Automatic line numbers for code snippets

Tweaks:

* Use system font stack vs web fonts
* Don't auto-highlight code snippets (I prefer Prism.js)
* More responsive scaling
* Removed Disqus support (TBD)

## Development

Install [Grunt](https://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt dependencies:

	npm install

Build Grunt project:

	grunt build

The zip Grunt task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

	grunt zip

