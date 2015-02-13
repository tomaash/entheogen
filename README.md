# Entheogen Theme

Dark theme for Sublime Text 3. It's especially well suited for modern JavaScript development. Among other features, is has support for ES6 classes, multi-level JSON coloring and different colors of braces for function definition vs. call. 

## Design

![Entheogen](https://dl.dropboxusercontent.com/u/738990/Pictures/entheogen_theme_design.png)

## Installation

Entheogen theme is designed to work with the latest development builds of [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Entheogen Theme via the `Package Control: Install Package` menu item. The Entheogen Theme is listed as `Theme - Entheogen` in the packages list.

### Using Git

Alternatively, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/tomaash/entheogen-theme.git

## Activating the theme

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "entheogen.tmTheme"` 

**Example Sublime Text 3 User Settings**

    {
        "theme": "entheogen.tmTheme"
    }

## License

Entheogen Theme is licensed under the [WTFPL License](http://www.wtfpl.net/). You are free to do what the fuck you want.