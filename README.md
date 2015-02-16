# Entheogen Color Scheme

Color scheme for Sublime Text 3. It's especially well suited for modern JavaScript development. Among other features, is has support for ES6 classes, multi-level JSON coloring and different colors of braces for function definition vs. call. Based on Monokai and NEXT. Looks good with [Predawn](https://github.com/jamiewilson/predawn) theme.

## Design

![Entheogen](https://dl.dropboxusercontent.com/u/738990/Pictures/entheogen_theme_design.png)

## Installation

Entheogen color scheme is designed to work with the latest development builds of [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Entheogen Color Scheme via the `Package Control: Install Package` menu item. The Entheogen color scheme is listed as `Entheogen Color Scheme` in the packages list.

### Using Git

Alternatively, you can install the color scheme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the color scheme repository using the command below:

    git clone https://github.com/tomaash/entheogen.git

## Activating the color scheme

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your color scheme entry to be `"color_scheme": "Packages/Entheogen Color Scheme/entheogen.tmTheme"` 

**Example Sublime Text 3 User Settings**

    {
        "color_scheme": "Packages/Entheogen Color Scheme/entheogen.tmTheme"
    }

## License

Entheogen color scheme is licensed under the [WTFPL License](http://www.wtfpl.net/).
