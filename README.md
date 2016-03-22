# my-sublime-prefs

Store my configuration preferences, packages and linters for [Sublime Text 3](https://www.sublimetext.com/3)

----
### Version
0.0.1

----
### Theme and color scheme
 Material Theme (https://packagecontrol.io/packages/Material%20Theme)
 	
 	"theme": "Material-Theme-Darker.sublime-theme",
 	"color_scheme": "Packages/Material Theme/schemes/Material-Theme-Darker.tmTheme",

----
### Packages
* AdvancedNewFile
* All Autocomplete
* AutoFileName
* CSS Snippets
* CSScomb
* DocBlockr
* EditorConfig
* Emmet
* Git
* GitGutter
* Gutter Color
* JavaScript & NodeJS Snippets
* jQuery
* JSCS-Formatter
* Material Theme
* Package Control
* SideBarEnhancements
* SublimeLinter
* SublimeLinter-csslint
* SublimeLinter-json

----
### Linters preferences

        "lint_mode": "save only",
        "linters": {
            "csslint": {
                "@disable": false,
                "args": [],
                "errors": "",
                "excludes": [],
                "ignore": "box-model,duplicate-properties,import,verqualified-elements,shorthand,important,ids,qualified-headings,unique-headings,overqualified-elements,vendor-prefix,unqualified-attributes,outline-none",
                "warnings": ""
            },
            "jscs": {
                "@disable": false,
                "args": [],
                "excludes": []
            },
            "json": {
                "@disable": false,
                "args": [],
                "excludes": [],
                "strict": true
            }
        },
        "mark_style": "squiggly underline",
        "no_column_highlights_line": true,
        "passive_warnings": true,
----
### changelog
* 22-03-2016
