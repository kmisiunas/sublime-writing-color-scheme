# [Writing Color Scheme for Sublime Text 2/3](https://github.com/kmisiunas/sublime-writing-color-scheme)

> Modified Monokai color scheme with specific additions for LaTeX. All modifications made to allow better writing experience. Color scheme still in Beta - user suggestions are welcome!

## Getting Started

### 1. Installation

#### Package Control

If you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed in Sublime Text:

* Select "Install Package" from the Command Palette: <kbd>Ctrl+Shift+P</kbd> on Windows and Linux or <kbd>⇧⌘P</kbd> on OS X)
* Search for "**Writing Color Scheme**" and click <kbd>enter</kbd>.

#### Manual Installation

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

``` bash
git clone https://github.com/kmisiunas/sublime-writing-theme.git "sublime-writing-theme"
```

### 2. Switch Color Scheme

Then inside Sublime Text, go to `Preferences -> Color Scheme -> User -> Writing Color Scheme`.


## Latex Examples

### Light Color Scheme (recommended)

![image](https://raw.githubusercontent.com/kmisiunas/sublime-writing-theme/master/screenshots/bright-theme.png)

Includes: 
 - Equation special background
 - balanced colors
 - In-line equations in italics

## Recommended settings

To get best experience we recommend modifying your language specific settings. For latex the settings file `LaTeX.sublime-settings` should look like:

    {
    // Add this file to Packages/User/ folder for effect

    "extensions": [ "tex" ],

    "color_scheme": "Packages/User/Writing Theme Light.tmTheme",
    //"color_scheme": "Packages/User/Writing Theme Dark.tmTheme",

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
    "line_padding_top": 2,
    "line_padding_bottom": 2,

    // Caret
    "caret_style": "solid", // blink with "smooth"
    "caret_extra_width": 1, 
    "caret_extra_top": 3,
    "caret_extra_bottom": 1
    }

## Author

**Karolis Misiunas**

+ [http://github.com/kmisiunas](http://github.com/kmisiunas)


## Contributions

**Jon Schlinkert** - provided initial Monakai Extended theme
+ [http://github.com/jonschlinkert](http://github.com/jonschlinkert)

[MIT License](LICENSE-MIT)
