# Bones - Grav Theme

[![Foundation Version](https://img.shields.io/badge/Foundation-v6.1.2-FF6908.svg)](http://foundation.zurb.com/) 
[![MotionUI Version](https://img.shields.io/badge/MotionUI-v1.2.0-FF6908.svg)](http://zurb.com/playground/motion-ui) 
[![FontAwesome Version](https://img.shields.io/badge/FontAwesome-v4.5.0-1d9d74.svg)](https://fortawesome.github.io/Font-Awesome/) 
[![WOWjs Version](https://img.shields.io/badge/WOW.js-v1.1.2.unofficial-eb3980.svg)](http://mynameismatthieu.com/WOW/) 
[![AnimateCSS Version](https://img.shields.io/badge/Animate.css-v3.5.1-f35626.svg)](http://daneden.github.io/animate.css/) 
[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](http://sgne.ws/1KPEcMD)

**Bones** is a [Grav](http://getgrav.org) theme based on [Foundation6](http://foundation.zurb.com/) by Zurb and Includes [FontAwesome](https://fortawesome.github.io/Font-Awesome/), [WOW.js](http://mynameismatthieu.com/WOW/), and [Animate.css](http://daneden.github.io/animate.css/). This is a base theme meant to be customized. The idea is to provide a starting point for your next custom project.

#### [Bones - Demo](http://demos.smartgravity.com/grav-bones/)


![Bones Screenshot](assets/bones-macbook-pro.png)

# Installation

Installing the Bones theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file. 

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The Bones theme can be found in a self-contained repository for a complete site which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

`bin/gpm install bones`

This will install the Bones theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/bones`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `bones`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-bones) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

`/your/site/grav/user/themes/bones`

> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Bones theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Bones is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update bones

This command will check your Grav install to see if your Bones theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Bones is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/bones` directory.
* Download the new version of the Bones theme from either [GitHub](https://github.com/getgrav/grav-theme-bones) or [GetGrav.org](http://getgrav.org/downloads/themes#extras).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `bones`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Bones as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: bones`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **bones** folder.
