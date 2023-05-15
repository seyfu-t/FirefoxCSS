# FirefoxCSS by KingSeyfo (based on parts of someone else's design, I can't find him anymore so can't reference him)
## Prerequisites

Verify that the user **stylesheets (userChrome)** option is enabled:
  1. Go to the address `about:config` in Firefox

  2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`

  3. Confirm the option is set to **true**
 Note: If you later deactivate this option the CSS file won't be read, so your Firefox will go back to default

## Installation
1. Go to the address `about:profiles` in Firefox
2. You will see a list of all your profile. You will most likely only see one since you only have one. If there are multiple profiles, the one you are using right now is the one without the button to change **this** to the default profile
3. It will show the path to the profile with a button right next to it saying `open folder`. Click on it.
4. Now if there is no folder called `chrome` go ahead an create one
5. Copy the repo files into that `chrome` folder
6. Restart all instances of Firefox, if you have any open.
