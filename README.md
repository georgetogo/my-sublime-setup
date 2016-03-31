
# Sublime Text Setup

### Plugins:
* Package Control
* Emmet
* AutoFileName
* Git
* GitGutter
* Sass
* jQuery
* SideBarEnhancements

### Settings - User:
```sh
{
	"always_show_minimap_viewport": true,
	"bold_folder_labels": true,
	"caret_extra_bottom": 1,
	"caret_extra_top": 1,
	"caret_extra_width": 1,
	"caret_style": "smooth",
	"color_scheme": "Packages/Theme - Otto/schemes/Otto Oceanic.tmTheme",
	"fade_fold_buttons": true,
	"font_size": 12,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"overlay_scroll_bars": "enabled",
	"scroll_speed": 1.5,
	"show_encoding": true,
	"spacegray_sidebar_font_large": true,
	"spacegray_sidebar_tree_large": true,
	"spacegray_tabs_font_large": true,
	"spacegray_tabs_xlarge": true,
	"theme": "Otto Oceanic.sublime-theme",
	"theme_otto_tab_auto_width": true,
	"theme_otto_tab_selected_prelined": true,
	"word_wrap": "false"
}
```

### Key Bindings - User:
(Make OSX Home & End key act the way I want 'em to)
```sh
{ "keys": ["home"], "command": "move_to", "args": {"to": "bol"} },
{ "keys": ["end"], "command": "move_to", "args": {"to": "eol"} },
{ "keys": ["shift+end"], "command": "move_to", "args": {"to": "eol", "extend": true} },
{ "keys": ["shift+home"], "command": "move_to", "args": {"to": "bol", "extend": true } }
```
