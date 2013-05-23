modernizer
==========

first Joomla Extension to implement "feature detection" browser upgrade messages, based on Modernizr.js


At May 2013, There are many Joomla extensions around implementing some sort of browser upgrade check,
but no one is doing it in the right way suggested by html5 experts reccomandations

You shuoud **not do browser detection** (browser are many, too many now in the mobile era to permit this check to scale well)

You should do **feature detection**!

Yes, you should be vendor agnostic now: the important thing is that the user agent supports a modern feature you need in 
your Joomla site: e.g. Rounded Corners, CSS3 Gradients, HTML5 Media Queries, Audio API, Hisotry API, Cache Manifest ect...

This matters, not the browser vendor branding and version number nowadays.

Modernizer for Joomla based on the famous and awarded  javascript library Modernizr, does this check in pure javascript
avioiding also problem with php based checks and Joomla cache enabled.

Tell your users to modernize their browsers!

So, install it, configure your feature needs and.... go, innovate!

