# JavaScriptCanvas.tmbundle #

A TextMate bundle for the HTML Canvas api.

[TextMate](http://macromates.com/) is a text editor / IDE for Mac OS X. This bundle adds functionality for developing with the HTML Canvas api.
For more information on Canvas see:

*	[HTML Canvas specification](http://www.whatwg.org/specs/web-apps/current-work/multipage/the-canvas-element.html)
*	[MDN Canvas doc centre](https://developer.mozilla.org/en/HTML/Canvas)


## Current status ##

The bundle currently only provides snippets for the Canvas api methods. This helps you avoid looking up the documentation for method names and arguments. The completion also reduces typing effort.

**Note:** The bundle binds the ⌃⇧⌘C `[control-shift-option-c]` key sequence while in the `source.js` context. That means ⌃⇧⌘C `[control-shift-option-c]` will open a context menu listing all the api methods.

Contribution is very welcome. Fork and go for it!


## Installation ##

It should be possible to install this bundle using <del>the excellent [GetBundles bundle](https://github.com/textmate/getbundle.tmbundle),
or</del> the [TextMate Gem](http://yehudakatz.com/2008/05/19/textmate-gem/).

You can download a zip of the current version <http://bit.ly/tmcanvas> (rename the expanded folder to `JavaScriptCanvas.tmbundle`).

Or clone the repo to your bundle folder with the following...

*	`cd ~/Library/"Application Support"/TextMate/Bundles/`
*	if that directory wasn't found, you'll need to create it, then:
*	`git clone git@github.com:johnhunter/JavaScriptCanvas.tmbundle.git "JavaScriptCanvas.tmbundle"`
*	`osascript -e 'tell app "TextMate" to reload bundles'`


## Licence ##

Licenced under CC-BSD 2011, John Hunter  
<http://creativecommons.org/licenses/BSD/>
