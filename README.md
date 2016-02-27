
# Sublime Text Setup

### Plugins Installed:
* Emmet
* Git
* GitGutter
* One Dark Color Scheme
* Package Control
* Sass
* SideBarEnhancements
* Theme - Spacegray

### Settings - User:
```sh
{
	"caret_extra_bottom": 1,
	"caret_extra_top": 1,
	"caret_extra_width": 1,
	"caret_style": "smooth",
	"color_scheme": "Packages/One Dark Color Scheme/One Dark.tmTheme",
	"font_size": 13,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"scroll_speed": 1.5,
	"spacegray_sidebar_font_large": true,
	"spacegray_sidebar_tree_large": true,
	"spacegray_tabs_font_large": true,
	"spacegray_tabs_xlarge": true,
	"theme": "Spacegray.sublime-theme",
	"word_wrap": "false"
}

```

### Key Bindings - User:
(Make OSX Home & End key act the way I want em to)
```sh
{ "keys": ["home"], "command": "move_to", "args": {"to": "bol"} },
{ "keys": ["end"], "command": "move_to", "args": {"to": "eol"} },
{ "keys": ["shift+end"], "command": "move_to", "args": {"to": "eol", "extend": true} },
{ "keys": ["shift+home"], "command": "move_to", "args": {"to": "bol", "extend": true } }
```
