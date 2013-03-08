# Terminal for Firefox

**My fork was merged back into [paulrouget/firefox-jsterm](https://github.com/paulrouget/firefox-jsterm). All functionality is now available there.**

**Go to: [paulrouget/firefox-jsterm](https://github.com/paulrouget/firefox-jsterm)**.

This Firefox addon contains full-featured console that supports
JS, [CoffeeScript](http://coffeescript.org) and [LiveScript](http://livescript.net).

Chrome coffeescript addons
like [CoffeeConsole](https://github.com/snookca/CoffeeConsole) cannot
manipulate DOM or play nicely (or even reasonably) with window properties.
They’re just shortcuts for coffeescript.org, which just compiles coffee down
to JS. This seems useless to me, because I want coffeescript as first-class
browser citizen. Some time ago, Mozilla introduced new awesome dev tools APIs
which allowed to make this addon.

Info and screencast are available at http://paulrouget.com/e/jsterm/. To switch between languages, use `:js`, `:coffee` & `:livescript`.
The language you choose will be saved for the next console session.

Screenshot:

![](http://f.cl.ly/items/151E3z1m150S3p2T1z3J/Screen%20Shot%202013-02-25%20at%204.52.26%20AM.png)
