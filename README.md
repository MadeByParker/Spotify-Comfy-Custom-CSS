![Screenshot of the Theme](https://github.com/Parker06/Comfy/blob/main/Comfy.PNG)

# Comfy Discord Theme for Spotify:

## It uses Spicetify

## To install Spicetify:

* Press Windows Key and type Powershell, to open and run powershell as admin on windows, for others view [https://github.com/khanhas/spicetify-cli/wiki/Installation.](https://github.com/khanhas/spicetify-cli/wiki/Installation)

* Run this command: `Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression`.

* Run `spicetify --help` for list of commands.

* Type `spicetify` to create config file.

* Then to make a backup of spicetify type: `spicetify backup apply enable-devtool`.

### Spotify will open automatically with the default theme so to change it.

* Copy the color.ini and user.css files into C:\Users\Your User Name\\.spicetify\Themes then create a new folder naming whatever you want.

## Then to update it:

* Go to .spicetify and click on the config.ini file, then replace "SpicetifyDefault" with the folder name you made e.g Comfy.

* As my theme has a light and dark mode go to "color_scheme" in the file and type Light or Dark for options, save the file.

* Then go to the powershell again and type `spicetify apply`.

## To update the same theme to newer version

* Open Powershell as an adminstrator then type `spicetify apply` to update the theme, Spotify should restart automatically to apply the changes.

[Source.](https://www.muo.com/tag/customize-spotify-with-spicetify-themes/)

## What to do if Spotify receives an update?

* Go into Windows Powershell and then run the command, `spicetify backup apply` to make a new backup point then once it created a backup then type `spicetify apply` to re-apply the custom css theme.
