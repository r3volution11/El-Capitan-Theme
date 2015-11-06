# El Capitan Theme

This is a dark version of the El Capitan theme created by [Ricci Adams](https://github.com/iccir). 

This README needs to be updated big time to reflect that. Most of the following is the same README from the original theme.

At the moment this theme is not 100% functional. I hope for it to be that way early next week! However - it does, for the most part, work well on retina displays.

---

OS X Yosemite inspired light theme for Sublime Text 3.

Based on Soda Theme by Ian Hill ([http://buymeasoda.com/](http://buymeasoda.com/))

## Design

### Light

![Screenshot](https://raw.githubusercontent.com/wiki/iccir/El-Capitan-Theme/Screenshot.png)

### Dark

![Screenshot](http://f.cl.ly/items/0B423I1f3D1H2t2h0n3B/Image%202014-09-07%20at%2011.32.55%20AM.png)

## Installation

El Capitan theme is designed to work with the latest development builds of [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

(Needs to be updated to reflect two different theme options)

(Investigate Package Control)

If you are using [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install the theme via the `Package Control: Install Package` menu item:

* Open Command Palette (mac: command + shift + p, windows: ctrl + shift + p),
* Choose the `Package Control: Install Package` menu item,
* Install the `Theme - El Capitan` package.

[:earth_africa: Learn more →](https://packagecontrol.io/packages/Theme%20-%20El%20Capitan)

### Using Git

(Needs to be updated to reflect two different theme options)

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/iccir/El-Capitan-Theme/ "Theme - El Capitan"

### Download Manually

(Needs to be updated to reflect two different theme options)

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - El Capitan`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User` (or `Preferences: Settings – User` via Command Palette),
* If you installed the theme via Package Manager, add an entry `"theme": "El Capitan.sublime-theme"`,
* Add (or update) your theme entry to be `"theme": "Packages/Theme - El Capitan/El Capitan Light.sublime-theme"` or `"theme": "Packages/Theme - El Capitan/El Capitan Dark.sublime-theme"`.

**Example Sublime Text 3 User Settings**

    {
        `"theme": "Packages/Theme - El Capitan/El Capitan Light.sublime-theme"`
    }

### Code Font

The code font shown in the light screenshot is Monaco, in the dark is Panic Sans.

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

## License

El Capitan Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

El Capitan Theme is based on Ian Hill's excellent Soda Theme, and thus the following Creative Commons license "author specified" components apply:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.
