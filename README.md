# This is a *mostly* working mobile only fork of the Discord Inspired theme for Silly Tavern.
 It also includes a fix for the Landing Page extension so the sidebar doesn't cover it.

## How do I apply the theme?
### Step 1: Install [Silly Tavern CSS Snippets](https://github.com/LenAnderson/SillyTavern-CssSnippets/)
Open Silly Tavern, go to the extensions page (three blocks icon) and click on install extension. Then paste "https://github.com/LenAnderson/SillyTavern-CssSnippets/" into the text box on the popup. Then click save and relaunch Silly Tavern.
 
### Step 2: Go to [#releases](https://github.com/dumbbitchashlyn/st-discord-inspired/releases/) and download whichever CSS file you prefer ***AND the .json theme file***.
 You will find two CSS files attached to the latest release. The only difference between them is whether or not the sidebar is center aligned or not.
 
 ![image](https://github.com/dumbbitchashlyn/st-discord-inspired/assets/59678757/1856cac1-6860-4558-a0c3-23705ee01aeb)
 vs
![image](https://github.com/dumbbitchashlyn/st-discord-inspired/assets/59678757/d1f13025-908d-4416-a80a-b2dae606445b)


### Step 3: Copy the .json theme file to SillyTavern.
   #### If you're using termux: 
   Ensure that termux has access to your phones files:
   
   > Run `termux-setup-storage` and accept the prompt
   
   Copy the .json file to your Silly Tavern themes directory:
   
   > `cp ~/storage/shared/***PATH_TO_FILE***/Discord_Inspired_Mobile_v1.1.0.json ~/***PATH_TO_SILLYTAVERN_DIR***/public/themes`
   
   You now can exit termux.

   #### If you're on Windows:
   go install the [proper version](https://github.com/nyxkrage/st-discord-inspired) nerd what are u even doing here
 
 ### Step 4: Install the theme.
 Open Silly Tavern and click on the user settings icon (avatar with a gear). 
 > First, under theme preset, select the Discord Inspired theme from the dropbox.

> Then scroll down until you see "Custom CSS" and click on the icon next to it.


>  At this point a new tab should open that says "CSS Snippets". Click on the import icon closest to the text, and select the CSS file you previously downloaded.

> Then click the checkbox marked "Theme". The theme should now be applied, and you can give the snippet a name if you want, I'd recommend something with the version number in it.

The theme is now installed, you may go back to Silly Tavern.

# Custom Colors
The background color is tied to the chat background selector in Silly Tavern's user settings.
The sidebar color is tied to the UI background selector.
