# Comfy Discord Theme for Spotify:

## It uses Spicetify

## To install Spicetify:

*Open and run powershell as admin on windows, for others view [https://github.com/khanhas/spicetify-cli/wiki/Installation.](https://github.com/khanhas/spicetify-cli/wiki/Installation)

*Run this command Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression.

*Run spicetify --help for list of commands.

*Type spicetify to create config file.

*Then to make a backup of spicetify type: spicetify backup apply enable-devtool.

### Spotify will open automatically with the default theme so to change it.

*Copy the color.ini and user.css files into C:\Users\[Your Name]\.spicetify\Themes then create a new folder naming whatever you want.

## Then to update it:

*Go to .spicetify and click on the config.ini file, then replace "SpicetifyDefault" with the folder name you made e.g Comfy.

*As my theme has a light and dark mode go to "color_scheme" in the file and type Light or Dark for options, save the file.

*Then go to the powershell again and type spicetify apply.

[Source.](https://www.muo.com/tag/customize-spotify-with-spicetify-themes/)
