# FormosaV5 Change Log

## TODO (Menu page)
* Organize files into folders
* Design/add sections for store and gift card
* Build responsive nav
* Build footer
* Refactor HTML
* Refactor CSS

## 2020 September 07
* Implemented new header section to menu with color-changing smooth transition animated background. Works fine in chrome, but while the images change in FF, there is no smooth transition. After researching the issue it appears this is a known bug/limitation on FF. Could possibly use animation with keyframes instead of transitions to correct the issue on FF.

## 2020 September 04
* Corrected shadows on chocolate back images.

## 2020 September 02
* Initial release of menu beta.
* Fixed bug experienced on macOS devices that was causing backs of menu cards to be visible. (added CSS rule "transform-style: preserve-3d;" to inner-card class)
