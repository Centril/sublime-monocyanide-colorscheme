[![Build Status]][url: Build Status] [![License]][url: License] [![Semver]][url: Semver] [![Gittip]][url: Gittip]

# [Monocyanide ColorScheme] <br/> for [Sublime Text]

> Extends [Monokai Extended] with a darker background, and lighter but slightly more saturated colors, as well as boldness added for functions, classnames, and a differentiated style for doc-block comments (e.g: javadocs).

A companion to the **[Cyanide Theme]**.

## Getting Started

### 1. Installation

#### Package Control

If you already have [Package Control] installed in Sublime Text:

* Select "Install Package" from the Command Palette:
    + <kbd>Ctrl+Shift+P</kbd> on Windows and Linux
    + <kbd>⇧⌘P</kbd> on OS X
* Search for "**Monocyanide Colorscheme**" and hit <kbd>ENTER</kbd>.

#### Manual Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

```shell
git clone https://github.com/centril/sublime-monocyanide-colorscheme.git "sublime-monocyanide-colorscheme"
```

### 2. Switch Themes

Then inside Sublime Text, go to:
```
Preferences -> Color Scheme -> Monocyanide ColorScheme
```

Here you can pick the variation that you like.

## Monokai Extended Enhancements

Adds scopes, support and/or improves styling for:

* JSON, syntax highlighting added.
* Keyword control: bold
* Primitives are differently colored.
* Comments are entirely desaturated.
* Documentation comments: lighter than normal comments.
* Documentation tags (@param, ...): bold
* {@link &lt;ref&gt;}, &lt;ref&gt; is now bold
* Method calls, bold
* Variations on the background

## Sneak peak

![screenshot: gruntfile.js]
> <div align="center">The gruntfile that builds the colorschemes.</div>

![screenshot: groovy]
> <div align="center">A groovy file.</div>


## Background variations

[Monocyanide ColorScheme] comes in 5 flavors where the background of each is different. The variations that are available are:
+ Default (the one with no suffix): `#0a0a0a`
+ Black: `#000000`
+ Contrasted: `#121212`
+ Contrasted Semi: `#191919`
+ Contrasted Light: `#282828`

When words are not enough:

![screenshot: bg-variations]

## [Monocyanide ColorScheme] Builder

*You must install the Monocyanide ColorScheme if you want to use the Monocyanide ColorScheme Builder.*

Create your own custom Monocyanide ColorScheme with the builder. If you don't have [grunt] installed, do that first.

Go to your Monocyanide ColorScheme Theme folder and run:

```shell
npm install
```

Edit the `backgrounds.json` file to add your own custom backgrounds.

Save the file, and run:

```shell
grunt build
```

Your new colorschemes are generated. Update the [Sublime Text] settings to use it.

## Plugins support

The following Sublime Text plugins are currently supported by Cyanide Theme:

* [GitGutter]
* [SublimeLinter3]

## Changelog

See the **[messages folder][CHANGES]**.

## Bugs / Issues / Feature requests / Contribution

Want to contribute? Great stuff! Please use the issue system that github provides to report bugs/issues or request an enhancement. Pull requests are also more than welcome.

## Author

**Mazdak Farrokhzad / Centril [&lt;twingoow@gmail.com&gt;]**

+ [twitter]
+ [github]

## Copyright & License

Licensed under the **[MIT License]**.
Copyright 2014   Mazdak Farrokhzad for the modified parts.
Original parts: [Jon Schlinkert].

## Acknowledgements

This color scheme is based on **[Monokai Extended]** by [Jon Schlinkert] and has been modified to fit the **[Cyanide Theme]** by [Lefoy] and my self. The tools that have been used are **[Color Scheme Editor]** by [Borislav Peev], and **[Scope Hunter]** by [facelessuser].

<!-- references -->

[Build Status]: http://img.shields.io/travis/Centril/sublime-monocyanide-colorscheme.svg?style=flat
[url: Build Status]: https://travis-ci.org/Centril/sublime-monocyanide-colorscheme
[Gittip]: http://img.shields.io/gittip/Centril.svg?style=flat
[url: Gittip]: https://www.gittip.com/Centril/
[License]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[url: License]: LICENSE.md
[Semver]: http://img.shields.io/badge/semver-2.0.0-blue.svg?style=flat
[url: Semver]: http://semver.org/spec/v2.0.0.html

[Monocyanide ColorScheme]: https://github.com/centril/sublime-monocyanide-colorscheme
[Sublime Text]: http://www.sublimetext.com/
[Monokai Extended]: https://github.com/jonschlinkert/sublime-monokai-extended
[Cyanide Theme]: https://github.com/lefoy/cyanide-theme
[Package Control]: http://wbond.net/sublime_packages/package_control/

[grunt]: http://gruntjs.com/

[screenshot: README.md]: https://github.com/Centril/sublime-monocyanide-colorscheme/blob/screenshots/readme.md.png?raw=true "This readme.md file"
[screenshot: groovy]: https://github.com/Centril/sublime-monocyanide-colorscheme/blob/screenshots/groovy.png?raw=true "A .groovy file"

[GitGutter]: https://sublime.wbond.net/packages/GitGutter
[SublimeLinter3]: https://github.com/SublimeLinter/SublimeLinter3

[twitter]: http://twitter.com/CenoRIX
[github]: http://github.com/centril
[&lt;twingoow@gmail.com&gt;]: mailto:twingoow@gmail.com

[CHANGES]: messages/
[MIT License]: LICENSE.md

[Lefoy]: https://github.com/lefoy
[Jon Schlinkert]: https://github.com/jonschlinkert
[Color Scheme Editor]: https://github.com/bobef/ColorSchemeEditor)
[Borislav Peev]: https://github.com/bobef
[Scope Hunter]: https://github.com/facelessuser/ScopeHunter
[facelessuser]: https://github.com/facelessuser

<!-- references -->