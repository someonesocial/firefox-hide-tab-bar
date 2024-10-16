# firefox-hide-tab-bar

I tried the ARC browser and fell in love with the vertical tabs. But I wanted to keep using Firefox for its features.

With this custom CSS, you can use any vertical tab extension you like in Firefox and regain the vertical height of the tab bar without losing the ability to minimise, maximise and close the window in windows.

My favourite vertical tab extension is Tab Stash (https://addons.mozilla.org/de/firefox/addon/tab-stash/), as it allows you to group tabs together and also represents these groups as Firefox bookmark folders that you can sync across devices.

![grafik](https://github.com/user-attachments/assets/1edf955a-0df4-4d11-9ba1-c48485f12cc4)


## Installation

1. Download the vertical tab extension of your choice and open it in the sidebar.
1. Right-click the toolbar or touchbar and chose *Customise toolbar...*.
2. Drag the new tab button and any other buttons you need out of the toolbar, as you will not be able to click them if the tab bar is hidden.
3. When you are done, click the *Done* button.
4. Follow this guide *https://www.userchrome.org/how-create-userchrome-css.html* to use the userChrome.css file provided above.

Also have a look at the code, I have commented it so you can easily modify/add to it.

## Extra:
If you want a completely black appearance of your browser, install this theme https://addons.mozilla.org/de/firefox/addon/black21/ and also copy the file userContent.css into the "chrome" folder, which will theme the Tab Stash extension.
