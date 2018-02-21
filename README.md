# [Writing Color Scheme for Sublime Text 2/3](https://github.com/kmisiunas/sublime-writing-color-scheme)

Color scheme optimised for writing in Latex and Markdown. Features:

 - Pleasant background/foreground contrast
 - Equations in red
 - \cite and \ref less distracting 
 
![image](https://raw.githubusercontent.com/kmisiunas/sublime-writing-theme/master/screenshots/example_20180221.png)


## Getting Started

## Installation

### Package Control

If you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed in Sublime Text:

* Select "Install Package" from the Command Palette: <kbd>Ctrl+Shift+P</kbd> on Windows and Linux or <kbd>⇧⌘P</kbd> on OS X)
* Search for "**Writing Color Scheme**" and click <kbd>enter</kbd>.

### Manual Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

``` bash
git clone https://github.com/kmisiunas/sublime-writing-theme.git "sublime-writing-color-scheme"
```

### Switching Color Scheme

Then inside Sublime Text, go to `Preferences -> Color Scheme -> Writing Color Scheme`.


## Recommended settings

To get best experience we recommend modifying your language specific settings. For latex the settings file `LaTeX.sublime-settings` should look like:

    {
    // Add this file to Packages/User/ folder for effect

    "extensions": [ "tex" ],
    
    "color_scheme": "Packages/User/Writing Color Scheme/Writing Color Scheme Light.tmTheme",
    
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": false,
    "auto_match_enabled": true,

    // Layout
    "draw_centered": true,
    "word_wrap": true,
    "wrap_width": 86,
    "rulers": [],

    // Line
    "line_numbers": true,
    "highlight_line": false,
    "line_padding_top": 4,
    "line_padding_bottom": 2,
    
    // Caret
    "caret_style": "solid", // blink with "smooth"
    "caret_extra_width": 1, 
    "caret_extra_top": 3,
    "caret_extra_bottom": 2
    }

## Recomended packages

The theme is great in "Distraction Free Mode" or with [DistractionFreeWindow](https://github.com/aziz/DistractionFreeWindow)

## Versions

 + **v2017-09-20** An update to make it compatible with sublime text v3. Also made comments a bit softer and main text a bit sharper. 
 + **v2018-02-21** Updated colors for labels and functions. Within text now they are less distracting. 

## Author

**Karolis Misiunas**

+ [http://github.com/kmisiunas](http://github.com/kmisiunas)


## Contributions

**Jon Schlinkert** - provided initial Monakai Extended theme
+ [http://github.com/jonschlinkert](http://github.com/jonschlinkert)


[MIT License](LICENSE-MIT)
