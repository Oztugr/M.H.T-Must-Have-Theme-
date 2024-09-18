# M.H.T (Must Have Theme)

**Note:** This repo is based on "https://github.com/drannex42/FirefoxSidebar/tree/main?tab=readme-ov-file" and heavily modified by me using my stuff, soulhotel/
    FF-ULTIMA,  artsyfriedchicken /EdgyArc-fr,  KiKaraage/ArcWTF theme codes.





# Features:
  - Edge-like vertical tab design
  - 3D Tabs, Url bar and browser content
  
# How to use

To use FirefoxSidebar you will need to clone this repo into your firefox profile as the `chrome` folder and then follow the Sideberry section below. Both are outlined below in how to do so.

## 1. userChrome.css

Follow the instructions for adding this repository to your Firefox Profile.

1. Navigate to `about:profiles` in your address bar
2. Open profiles folder
3. Copy the chrome folder into your profiles folder 
4. In Firefox navigate to `about:config` in your address bar
4. change the characteristic `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
6. Restart Firefox

You could skip the clone step entirely if you manually add the FirefoxSidebar files to the "chrome" folder in your Firefox Profile (you will need to make a `chrome` folder if it doesn't exist!).

Visit [userchrome.org](https://www.userchrome.org/how-create-userchrome-css.html) if you are confused or have any questions.

## 2. Sidebery (Sideberry)

Load the `sidebery-data.json` file into your Sidebery addon by using the 'import' section under 'Help'.

If you dislike any of the theme presets for dark or light themes, or you have a particular color scheme in mind then navigate to Sideberry Settings > Style Editor (found at the end of the settings sidebar). The preference is to replace the values in the right panel, not in the theme editor to the left - this way you can easily update to newer versions in the future.

### Extensions

All extensions can be found in `/extensions`.


**The following extensions are added by default:**

- [Window Controls / Client Side Decorations (CSD)](/extensions/window_controls.css)
  - This adds the window controls to be inline with your address bar.

There are a number of additional 'extensions' added in that folder. 

## User Settings

Please backup the `prefs.css` and the `custom.css` files before updating to a new versionof FirefoxSidebar.  There may be new additions to these files, so you will need to re-add your preferencess to the file accordingly. These files should be updated *far less* than the other files, but just to make sure please save them.

### Preferences

There are a number of preferences you can enable or disable in the `prefs.css` file. There are examples and descriptions of the different preferences within that file.

### Custom Tweaks

For ease of use I suggest using the `custom.css` file to for your personal tweaks.

### If you use FF without the bookmarks bar

Then the sidebar switcher will be missing, edit `userChrome.css` and uncomment the relevant section.
