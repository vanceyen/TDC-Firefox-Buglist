# TDC Firefox Team Bug Log - WEEK 17 : #


## Fred Lin ##

### Done : ###

- [Firefox]
  - [Bug 1240727](https://bugzilla.mozilla.org/show_bug.cgi?id=1240727) - Capital letters keywords are not recognized when showing which of the search engine will be used in the next search
  - [Bug 969443](https://bugzilla.mozilla.org/show_bug.cgi?id=969443) - Update CustomizableUI tests to yield on CustomizeMode.reset instead of gCustomizeMode.resetting
  - [Bug 1219495](https://bugzilla.mozilla.org/show_bug.cgi?id=1219495) - about:addons renders with huge "Server not found" page if you're offline, instead of placeholder content
  - [Bug 1260718](https://bugzilla.mozilla.org/show_bug.cgi?id=1260718) - Switch to using plain promises instead of Promise.jsm in CustomizableUI code
  - [Bug 1263557](https://bugzilla.mozilla.org/show_bug.cgi?id=1263557) -  Switch to use plain promise in CustomizeMode.jsm

### Next : ###

- [Firefox]
  - [Bug 1256772](https://bugzilla.mozilla.org/show_bug.cgi?id=1256772) - Fix ESLint issues in devtools/client/webconsole/jsterm.js
  - [Bug 1011023](https://bugzilla.mozilla.org/show_bug.cgi?id=1011023) - Simplify test_bookmarks_restore_notification.js to use add_task
  - [Bug 1217134](https://bugzilla.mozilla.org/show_bug.cgi?id=1217134) - Replace show password placeholder with conventional show password checkbox


## Ray Lin ##
### Done : ###

- [Firefox]
  - [Bug 995758](https://bugzilla.mozilla.org/show_bug.cgi?id=995758) - Address bar doesn't capture focus if a new tab is created via Ctrl+T shortcut while in Customization mode
- [Fennec]
  - [Bug 1250741](https://bugzilla.mozilla.org/show_bug.cgi?id=1250741) - Update video player spec
  - [Bug 1198935](https://bugzilla.mozilla.org/show_bug.cgi?id=1198935) - Set about: pages header height to 48px
  - [Bug 1065076](https://bugzilla.mozilla.org/show_bug.cgi?id=1065076) - Update icons for video controls

### Next : ###

- [Fennec]
  - [1260304](https://bugzilla.mozilla.org/show_bug.cgi?id=1260304) - mediasource: prepended to the context menu of MSE videos
- [Firefox]
  - [Bug 925101](https://bugzilla.mozilla.org/show_bug.cgi?id=925101) - Remove legacy signons.txt files
  - [Bug 1203481](https://bugzilla.mozilla.org/show_bug.cgi?id=1203481) - All dividers in the URL bar should have the same style 
   
## Ricky Chien ##

### Done : ###
 - [Firefox]
 	- [Bug 1251863](http://bugzil.la/1251863) - Browser Console focuses wrong window when I close it after openning from Scratchpad

### Next : ###
 - [Firefox]
	- [Bug 1259340](http://bugzil.la/1259340) - New Private Browsing Window update

## Scott Wu ##
	
### Next : ###
- [Firefox]
	- [Bug 446171](https://bugzilla.mozilla.org/show_bug.cgi?id=446171) - Name field of bookmarks saved via "Bookmark All Tabs" has "(null)" value if history is disabled or just in private browsing mode

- [Fennec]
	- [Bug 1264901](https://bugzilla.mozilla.org/show_bug.cgi?id=1264901) -  Implement the remote media-control front-end
		
## Sean Lee ##

### Done : ###

- [Firefox]
  - [Bug 1191092](https://bugzilla.mozilla.org/show_bug.cgi?id=1191092) - InsecurePasswordUtils should handle |input type=password| outside of a form element

  ### Next : ###

- [Firefox]
  - [Bug 1261234](https://bugzilla.mozilla.org/show_bug.cgi?id=1261234) - Insecure form action password form warning appears for trustworthy action URLs using HTTP

## Tim Chien ##

### Done : ###

- [Firefox]
   - [Bug 1243722](https://bugzil.la/1243722) - Wrong doorhanger when updating password on Facebook
   - [Bug 1184950](https://bugzil.la/1184950) - Leaving Reader Mode should not reload
   - [Bug 1229727](https://bugzil.la/1229727) - Mac OS X full screen warning
   - [Bug 1243729](https://bugzil.la/1243729) - Username is overwritten with a blank one when updating the password for a Twitter account
   - [Bug 1263760](https://bugzil.la/1263760) - TabSwitchDone does not fire when a dialog is opened bug caused by quirky behavior of nested event loop 

### Next : ###
- [Firefox]
	- [Bug 1266372](https://bugzil.la/1266372) - The close reader mode button on page should behave the same as bug 1184950
	- [Bug 1264805](https://bugzil.la/1264805) - Leaving Reader Mode should not reload on Fennec

## Joseph Yeh ##

### Done : ###

- [Firefox]
	- [Bug 530999](https://bugzilla.mozilla.org/show_bug.cgi?id=530999) -  Login manager UI should show site favicons


## Dan Huang ##

### Next : ###
- [Firefox]
	- [Bug 920956](https://bugzilla.mozilla.org/show_bug.cgi?id=920956) - DevTools touch emulation: suppress regular mouse events, emulate 300ms delay


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