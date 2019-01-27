# userChromeJS

#### Tested on Firefox 65.0b12, Windows 10

## Instructions

1. Just for [Firefox Developer Edition](https://www.mozilla.org/firefox/developer/) (main compatibility target), [Firefox Nightly](https://www.mozilla.org/firefox/channel/desktop/#nightly) and [Firefox ESR](https://www.mozilla.org/en-US/firefox/organizations/all/). It will not work on Firefox release/stable or Firefox Beta.

2. Save [config.js](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/installation-folder/config.js) to Firefox installation folder (usually **C:\Program Files (x86)\Mozilla Firefox**), next to **firefox.exe**.

3. Save [config-prefs.js](https://raw.githubusercontent.com/xiaoxiaoflood/firefox-scripts/master/installation-folder/config-prefs.js) into **\defaults\pref** inside Firefox installation folder (usually **C:\Program Files (x86)\Mozilla Firefox\defaults\pref**), next to **channel-prefs.js**.

4. Click Firefox menu button (☰) -> *Help* -> *Troubleshooting information* (or simply open the address "*about:support*"), then click *Open folder*. This is the folder of your Firefox profile. In there, create a new folder called **chrome**.

5. Inside **chrome**, create another new folder called **utils**, then save all [these](https://github.com/xiaoxiaoflood/firefox-scripts/tree/master/chrome/utils) files into it.

6. Save [rebuild_userChrome.uc.js](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/chrome/rebuild_userChrome.uc.js) into **chrome**.

7. Save the desired [userChromeJS scripts](https://github.com/xiaoxiaoflood/firefox-scripts/tree/master/chrome) into **chrome**. Read below description of each one.

8. Restart Firefox.

## userChromeJS scripts

(click on each to expand)
<details>
  <summary>about:blank as New Tab</summary>
  Self-descriptive title. For clean, light and empty New Tab page.

  [Download link](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/chrome/aboutBlankNewTab.uc.js).  
</details>
<details>
  <summary>Master Password+</summary>
  Locks Firefox with password. It will prompt the password on browser startup or anytime when you lock it with Ctrl+Alt+Shift+W.
  
  You need to set a master password in <i>Firefox Options > Privacy & Security > [×] Use a master password</i>.

  [Download link](https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/chrome/masterPasswordPlus.uc.js).  

  Locked:
  ![Locked](https://i.imgur.com/cE3sUGT.png "Locked")

  Unlocked:
  ![Unlocked](https://i.imgur.com/KOkEJq5.png "Unlocked")
</details>

## Screenshots

<img src="https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/screenshots/folder.png">

###### userChromeJS Manager (the blue ones are restartless)
<img src="https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/screenshots/rebuild_userChrome.png" height="600">

###### Status Bar, Extension Options Menu, MinMaxClose Button, newDownloadPlus.uc.js and legacy extensions:
<img  src="https://github.com/xiaoxiaoflood/firefox-scripts/raw/master/screenshots/window.png">
