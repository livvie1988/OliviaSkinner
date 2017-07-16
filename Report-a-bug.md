Before reporting please follow the troubleshooting guide first, it contains steps that will help you solve most of the problems that might not be related or directly related to the extension.

## Troubleshooting

- Make sure that you are using the new YouTube Material layout. If you aren't then enable it and try again: https://www.youtube.com/new

  - This extension is built just for the new layout, it will not work with the classic layout.

- Make sure that you are using the most recent Iridium version. If you aren't then update it, restart the browser and see if the problem has already been fixed.

  - Quite often problems have already been fixed in a recent version that your browser hasn't had the time to updated Iridium yet. To check which version is the latest visit the latest release tracker located here: https://github.com/ParticleCore/Iridium/releases/latest or the respective branch (alpha/beta) if you are using a development version.

- This extension is only being supported for **stable versions** of Firefox 54+, Chrome 58+ and Opera 45+, there are no plans to support any other browser in the future. If you are using a different browser then try running the extension in one of the supported versions.

  - If the problem still persists move to the next step.

- Make sure you are not using the Flash player. Right click on your player and see if it lists "About Adobe Flash Player <Number>..."
  - The extension works with the Flash player, but many features do not simply because they are not compatible or possible to work with the limitations imposed by this player type. The only solutions are to use the HTML5 player by visiting this link and activating it: https://www.youtube.com/html5 or to use the Flash player without using the incompatible features

- Disable the extension and restart the browser.
  - If the problem still persists then it is not related to the extension. It might be caused by another extension, browser setting or by the website itself
  - If the problem doesn't persist move to the next step

- Disable all other extensions and userscripts (except YT+) you might have running in your browser and restart the browser.
  - If the problem doesn't persist then it might not be related to the extension, it is most likely being caused by a conflicting extension. Enable each one individually until the issue returns, then proceed to the posting section
  - If the problem still persists move to the next step

- Check if your browser or extension has a new update version, if it does then update them.
  - If the problem still persists move to the next step

- Reset the extension settings to their default.
  - If the problem still persists move to the next step

- Create a new browser profile and install only Iridium, see if the problem still persists. New profile instructions:  [Firefox](https://support.mozilla.org/en-US/kb/profile-manager-create-and-remove-firefox-profiles#w_starting-the-profile-manager) | [Chrome](https://web.archive.org/web/20160915221807/https://support.google.com/chrome/answer/142059) | [Opera](http://lmgtfy.com/?q=reset+opera+profile)
  - If the problem doesn't persist then it was a browser setting that was causing the issue
  - If the problem still persists move to the posting section

## Posting a new issue

- Before posting a new issue make sure that your issue doesn't already exist, use the search box for this purpose.
  - Remember to search in the [closed issues section](https://github.com/ParticleCore/Iridium/issues?q=is%3Aissue+is%3Aclosed) as well, your issue might already have been addressed and fixed.

- Issues must be in English only, no other language will be accepted.

- To post your issue the following template will be of extreme help. Fill it accordingly following the instructions mentioned on the next step:

        Browser Name: 

        Browser Version: 

        Operating System: 

        Software Type: 

        Software Version: 

        Userscript Manager: (Remove this line if you are not using the userscript version)

        Userscript Version: (Remove this line if you are not using the userscript version)

        Problem Description: 

        Steps to reproduce: 

        Additional details: 

- The following explains the information you will have to fill in the above blank template

        Browser Name: (The browser you are using; Firefox, Chrome or Opera)

        Browser Version: (The browser version; 38.0.0, 58.0.1.514 or 42.0.2311.135)

        Operating System: (The OS you are using; Windows 7, Linux, OSX)

        Software Type: (The type of Iridium extension you are using; Add-on, extension or Userscript)

        Software Version: (The version of the Iridium extension you are using; 0.0.1, 0.2.5, etc.)

        Userscript Manager: (The type of userscript manager you are using; Greasemonkey or Tampermonkey)

        Userscript Version: (The userscript manager version you are using; 3.2beta1, 3.10.84)

        Problem Description: (Try to be as precise as possible, include screenshot(s) or video(s) if the problem can be visualized)

        Steps to reproduce: (Try to be as precise as possible, include example pages if applicable)

        Additional details: (Optional)(Any other information that you might find useful)