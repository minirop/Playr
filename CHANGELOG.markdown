#### Known issues
* Volume control not working in Opera if there's more than one video on the same "line"

#### TODO
* Fix issues above
* Add a Flash fallback

### v0.5.5
* Added cue timestamps tags support (see notes on WebVTT implementation)
* Cue tags parser fixes

### v0.5
* Interface improvements
* Added buffering bar
* Added WebVTT text position support
* Fixed WebVTT text alignment

### v0.4
* Added line position (L:xx%) support
* Code refactoring

### v0.3.4
* Added <track> label support
* Added <c.classname> WebVTT tag support

### v0.3.3
* Fixed fullscreen controls not displaying properly

### v0.3.2
* Changed the setup method
* Some CSS fixes

### v0.3.1
* Fixed Firefox 4 replaying the video automatically
* Removed version number in JS & CSS files
* Added notes on local testing

### v0.3
* Interface improvements

### v0.2.8
* Added track auto-select based on <html> lang & <track> srclang

### v0.2.7
* Added font size auto-scaling when using fullscreen
* Added code documentation (merge branch documentation)

### v0.2.6.1
* Added fullscreen auto-resize when resizing the window

### v0.2.6
* Improved fullscreen (based on window resolution)
* Fixed Firefox not restoring properly from fullscreen
* Made srclang attribute optional

### v0.2.5
* Improved integration script
* Added remove "controls" attribute
* Cleaned CSS

### v0.2.1
* Improved Safari performances: frozen while loading, but smooth once loaded
* New way of adding the controls

### v0.2
* Fixed a bug where Firefox would not get and display the subtitles
* Added a basic fullscreen option (buggy in Firefox when restoring)
* Added keyboard escape shorcut to restore from fullscreen

### v0.1.6
* Fixed volume and closed captions controls in Firefox
* Added a timecode notifier when hovering the timebar

### v0.1.5
* Added a volume control (replacing range type input)
* Extended clickable area of the closed caption menu
* Added draggable timebar and volumebar cursors
* Added Changelog

### v0.1
* Initial version
