# USGC Sublime Text Color Schemes
For text only, not designed for programming.

### Sublime Text
Download and obtain a license here: https://www.sublimetext.com/

### Installation
Settings > Browse Packages... > Paste theme files in this directory.

### Themes list

U.S. Graphics Company internal part numbers.
```text
┌─────────────┬─────────────┬───────────────────────┐
│ PART NUMBER │ THEME NAME  │ DESCRIPTION           │
├─────────────┼─────────────┼───────────────────────┤
│ 5200-010    │ HIGHK       │ White color scheme    │
│ 5200-020    │ AMHS        │ Dark color scheme     │
│ 5200-030    │ POLYIMIDE   │ Amber color scheme    │
│ 5200-040    │ EPITAXY     │ Magenta color scheme  │
│ 5200-050    │ METALGATE   │ Cyan color scheme     │
└─────────────┴─────────────┴───────────────────────┘
```

Theme file names are formatted as `USGC-<THEME NAME>-<SOFTWARE CODE>`.

```text
┌───────────────┬────────────────┐
│ SOFTWARE CODE │ SOFTWARE NAME  │
├───────────────┼────────────────┤
│ ST            │ Sublime Text   │
└───────────────┴────────────────┘
```

### Standard colors
```text
┌───────────┬──────────────────────┐
│ HEX COLOR │ NAME                 │
├───────────┼──────────────────────┤
│ 000000    │ BLACK                │
│ FFFFFF    │ WHITE                │
│ FF0000    │ FL RED               │
│ 00FF00    │ FL GREEN             │
│ 0000FF    │ FL BLUE              │
│ 00FFFF    │ FL CYAN              │
│ FF00FF    │ FL MAGENTA           │
│ FFFF00    │ FL YELLOW            │
│ FF6600    │ FL ORANGE            │
│ 660000    │ RED                  │
│ 00A645    │ GREEN                │
│ 000066    │ BLUE                 │
│ 006666    │ CYAN                 │
│ 660066    │ MAGENTA              │
│ FFBF00    │ YELLOW               │
│ 666600    │ BROWN                │
│ 999999    │ GRAY                 │
└───────────┴──────────────────────┘
```

### Sublime Text Preferences

These themes work best with the following settings in your `Preferences.sublime-settings` file:


WARNING: `vim` mode is active in this settings file.
```json
{
	"theme": "Adaptive.sublime-theme",
	"color_scheme": "USGC-AMHS-ST.sublime-color-scheme",
	"theme_font_options": ["no_italic"],
	"auto_complete": true,
	"caret_blink_interval": 0.5,
	"caret_extra_bottom": -5,
	"caret_extra_top": -5,
	"caret_extra_width": 0,	
	"caret_style": "wide",
	"font_face": "Berkeley Mono Condensed",
	"font_size": 13,
	"font_options": ["no_italic"],
	"line_padding_top": -1,
	"line_padding_bottom": -1,
	"highlight_line": false,
	"rulers": [96],
	"default_line_endings": "unix",
	"show_line_endings": false,
	"tab_size": 4,
	"tab_completion": false,
	"detect_indentation": false,
	"draw_white_space": "none",
	"draw_indent_guides": false,
	"index_files": true,
	"ignored_packages": [
	]
}

```