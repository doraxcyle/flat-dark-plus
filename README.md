# <b> Flat Dark+ Theme</b>

A flat dark theme for Visual Studio Code that is based on Dark+ (default dark) but with better features and customizations.

#
## ✨<b>New Update - version 1.0.0</b>  ✨
#
## <b>What's new</b>?

- New dark color
- Hover effects for buttons
- A more flat design all round.
- Terminal border for splitted terminals.
- Better syntax highlighting for html, css, js, etc.
- Easily know which of your tabs are active and focused with the new colored borders.

#

## <b>The team</b>

- [xcyl](https://github.com/xcyl/flat-dark-plus)
- [utibeinyangetuk](https://github.com/utibeinyangetuk/flat-dark-plus)

#

## <b>Screenshots</b>
<br>

# - <b>welcome page</b>

![](https://raw.githubusercontent.com/utibeinyangetuk/flat-dark-plus/master/welcome.png)
# - <b>HTML</b>
![](https://raw.githubusercontent.com/utibeinyangetuk/flat-dark-plus/master/html.png)
# - <b>CSS</b>
![](https://raw.githubusercontent.com/utibeinyangetuk/flat-dark-plus/master/css.png)
# - <b>JAVASCRIPT</b>
![](https://raw.githubusercontent.com/utibeinyangetuk/flat-dark-plus/master/javascript.png)

#
## <b>my custom settings</b>
#### ⚠️ You must have downloaded and installed Fira code font before you can set it as your editor font.


    "editor.padding.bottom": 12,
    "editor.padding.top": 12,
    "editor.lineHeight": 25,
    "editor.fontWeight": "450",
	"editor.fontFamily": "fira code Retina",
	"editor.fontLigatures": "'cv05','zero','onum','cv14','cv17','ss04','cv18','cv16','cv31','cv30','cv29','cv27','ss10','ss07','ss06','cv28','cv32','cv26','cv25','ss09','cv21','cv23'",



### 🚨 For extra semantics highlighting, you can edit your token colors in the settings.json file using the command below
#

  "editor.semanticTokenColorCustomizations": {

		"[flat dark+]": {
			"rules": {
				"variable": {
					"foreground": "#8e8eeb",
				},
				"method": {
					"foreground": "#d5a106",
				},
				"function": {
					"foreground": "#b738ee",
                    "fontstyle":"underline"
				},
				"parameter": {
					"foreground": "#b70a3e",
				},
				"property": {
					"foreground": "#698989",
				},
				"class": {
					"foreground": "#ff8f0099",
				}
			}
		},
	},
