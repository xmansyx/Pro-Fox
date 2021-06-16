# pro-fox: A Firefox Theme

## Description
A custome css theme for Firefox Proton that aims to make it even better
+ tabs are moved under urlbar
+ centeralized url bar
+ remove (playing - paused) from tabs that are playing videos or sound
+ selected tabs are expanding and their main color changed to accent color
+ moved sound icon on top of favicon
+ enhanced and bigger menus with icons
+ supports both dark and light mode
+ more...

![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-16%2018-59-08.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-16%2018-57-31.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-16%2018-56-31.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-16%2018-57-31.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-07%2012-46-00.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-07%2012-51-09.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-07%2012-46-21.png)
![Preview](https://github.com/xmansyx/Pro-Fox/blob/main/previews/Screenshot%20from%202021-06-07%2012-51-24.png)
![Preview](https://raw.githubusercontent.com/xmansyx/Pro-Fox/main/previews/Screencast%20from%2006-07-2021%2012%2055%2038%20PM.gif)


### NOTES
+ 100% working on linux.
+ Untested on macOS.

### Manual Installation

1. Open `about:config` page.
2. A dialog will warn you, but ignore it, ~~just do it~~ press the `I accept the risk!` button.
3. Search for these:

	+ **`toolkit.legacyUserProfileCustomizations.stylesheets`**
	+ **`layers.acceleration.force-enabled`**
	+ **`gfx.webrender.all`**
	+ **`gfx.webrender.enabled`**
	+ **`layout.css.backdrop-filter.enabled`**
	+ **`svg.context-properties.content.enabled`**

4. Go to your Firefox profile.

	+ Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`.
	+ Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`.
	+ macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`.

5. Create a folder and name it **`chrome`**, then assuming that you already have cloned this repo, just copy the theme to `chrome` folder.
6. Restart Firefox.
7. Finally, you can now change whatever color mode you want in the Cusomization Window.

	+ Default - Uses system colors, but uses the theme's layout.
	+ Dark - Dark colorscheme. Good for the night.
	+ Light - Bright colorscheme. Good for killing the eyes.

