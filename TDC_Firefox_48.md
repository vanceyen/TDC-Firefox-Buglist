# Done list for FE48 : #

## Firefox ##
### Toolbars and Customization ###
- [Bug 969443](https://bugzilla.mozilla.org/show_bug.cgi?id=969443) - Update CustomizableUI tests to yield on CustomizeMode.reset instead of gCustomizeMode.resetting
- [Bug 995758](https://bugzilla.mozilla.org/show_bug.cgi?id=995758) - Address bar doesn't capture focus if a new tab is created via Ctrl+T shortcut while in Customization mode
- [Bug 1260718](https://bugzilla.mozilla.org/show_bug.cgi?id=1260718) - Switch to using plain promises instead of Promise.jsm in CustomizableUI code
- [Bug 1263557](https://bugzilla.mozilla.org/show_bug.cgi?id=1263557) -  Switch to use plain promise in CustomizeMode.jsm

### Tabbed Browser ###
- [Bug 1263760](https://bugzil.la/1263760) - TabSwitchDone does not fire when a dialog is opened bug caused by quirky behavior of nested event loop

### Shell Integration ###
- [Bug 1229727](https://bugzil.la/1229727) - Mac OS X full screen warning

### Search ###
- [Bug 1240727](https://bugzilla.mozilla.org/show_bug.cgi?id=1240727) - Capital letters keywords are not recognized when showing which of the search engine will be used in the next search

### Developer Tools: Console ###
- [Bug 1251863](http://bugzil.la/1251863) - Browser Console focuses wrong window when I close it after openning from Scratchpad

### Bookmarks & History ###
- [Bug 446171](https://bugzilla.mozilla.org/show_bug.cgi?id=446171) - Name field of bookmarks saved via "Bookmark All Tabs" has "(null)" value if history is disabled or just in private browsing mode

## Toolkit ##
### Add-ons Manager ###
- [Bug 1219495](https://bugzilla.mozilla.org/show_bug.cgi?id=1219495) - about:addons renders with huge "Server not found" page if you're offline, instead of placeholder content

### Password Manager ###
- [Bug 530999](https://bugzilla.mozilla.org/show_bug.cgi?id=530999) -  Login manager UI should show site favicons
- [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook
- [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account

### Reader Mode ###
- [Bug 1184950](https://bugzil.la/1184950) - Leaving Reader Mode should not reload

## Core ##
### Security ###
- [Bug 1191092](https://bugzilla.mozilla.org/show_bug.cgi?id=1191092) - InsecurePasswordUtils should handle |input type=password| outside of a form element

## Fennec ##
- [Bug 1250741](https://bugzilla.mozilla.org/show_bug.cgi?id=1250741) - Update video player spec
- [Bug 1198935](https://bugzilla.mozilla.org/show_bug.cgi?id=1198935) - Set about: pages header height to 48px
- [Bug 1065076](https://bugzilla.mozilla.org/show_bug.cgi?id=1065076) - Update icons for video controls