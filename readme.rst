ViS: Vi Slowed/jS
=====
ViS as in Vi Slowed(kidding :-]) written in Java*S*cript.
ViS is a lightweight-but-powerful programmer's editor running as a Chrome
Packaged App. Inspired by Caret and built on top of it and Ace editor's editing
component, it offers(as of now it should be AIMING FOR):

-  lighter weight than the original
-  full Vim command support
-  compatible with .vimrc file and .vim plugin file
-  able to run as a standalone application on multiple platform
-  passing on the torch of vim.js since it has been archived
-  more to come...

This project would also reference other vim related repos on Github, they would be properly cited and referenced.
More information on the original Caret app(highly recommended, I love it), links to Caret in the Chrome Web Store, and an
external package file are available at http://thomaswilburn.net/caret.
Documentation can be found in the
`wiki <https://github.com/thomaswilburn/Caret/wiki>`_.


You can also load the app from source code, either to hack around on or
to try the absolute bleeding edge. You'll need to have Node and NPM
installed first, then follow these steps:

0. Clone this repo to your local machine
1. Run ``npm install`` to get the development dependencies (Grunt, LESS,
   and some other packages)
2. Run ``npm run build``, which will generate the CSS files from the LESS
   source
3. Visit ``chrome://extensions`` and enable Developer Mode.
4. Still on the extensions page, click the button marked "Load unpacked
   extension..." and select the directory containing Caret's
   manifest.json.
