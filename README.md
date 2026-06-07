#  My Custom UI Styles for Firefox Nightly

This is the contents of my Firefox "chrome" folder, containing my own CSS customizations. I use these files on macOS.

The goal of these special styles is to optimize Firefox Nightlyfor "compact mode“.nMy focus was on the tabs and the address bar, but other customizations are also included.

I wanted to share these files because "CustomCSSforFx" is no longer up-to-date. If you like my design (see screenshot), feel free to copy it. 

![](screenshot01.png)

#  How to use

To use it, you must first enable user stylesheets and compact mode.
Copy this text into your user.js (or copy my user.js to your profile):

// *********************
// Enable user stylesheets
user_pref("toolkit.legacyUserProfileCustomizations.stylesheets", true);

// Enable compact mode
user_pref("browser.compactmode.show", true);

// Enable Nova UI
user_pref("browser.nova.enabled", true);
user_pref("browser.newtabpage.activity-stream.nova.enabled", true);
user_pref("browser.urlbar.nova.featureGate", true);
user_pref("browser.urlbar.quicksuggest.ampTopPickUseNovaIconSize", true);
// *********************

Give feedback 
