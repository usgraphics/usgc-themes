# USGC Sublime Text Color Schemes
For text only, not designed for programming.

### Sublime Text
Download and obtain a license here: https://www.sublimetext.com/

### Installation
Settings > Browse Packages... > Paste theme files in this directory.

### Themes list

U.S. Graphics Company internal part numbers.
```text
┌─────────────┬─────────────┬────────────────┬──────────────────────────────────┐
│ PART NUMBER │ THEME NAME  │ DESCRIPTION    │ COMMENT                          │
├─────────────┼─────────────┼────────────────┼──────────────────────────────────┤
│ 5200-010    │ HIGHK       │ White scheme   │ High dielectric constant         │
│ 5200-020    │ RETICLE     │ Dark scheme    │ Photomask for lithography        │
│ 5200-030    │ POLYIMIDE   │ Amber scheme   │ Heat-resistant polymer           │
│ 5200-040    │ EPITAXY     │ Magenta scheme │ Crystal layer growth             │
│ 5200-050    │ METALGATE   │ Cyan  cheme    │ Metal gate transistor            │
└─────────────┴─────────────┴────────────────┴──────────────────────────────────┘
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
│ 660000    │ MAROON               │
│ 00A645    │ GREEN                │
│ 000066    │ BLUE                 │
│ 006666    │ CYAN                 │
│ 660066    │ MAGENTA              │
│ FFBF00    │ YELLOW               │
│ 666600    │ OLIVE                │
│ 999999    │ GRAY                 │
└───────────┴──────────────────────┘
```

### Sublime Text Preferences

These themes work best with the following settings in your `Preferences.sublime-settings` file:

<img width="600" alt="usgc-theme-colors" src="https://github.com/user-attachments/assets/f0210f2a-9468-48d9-9ecf-30547e601526" />

WARNING: `vim` mode is active in this settings file.
```json
{
	"theme": "Adaptive.sublime-theme",
	"color_scheme": "USGC-RETICLE-ST.sublime-color-scheme",
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

### Screenshots

Here is the updated flowing table with a merged header column:

Here is the updated Markdown table with all text in code format and without bold formatting:

| U.S. Graphics Company Themes |                                                                                                                                                                              |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `HIGHK`<br>`USGC-HIGHK-ST`<br>`PN#: 5200-010`<br><img width="460" alt="HIGHK" src="https://github.com/user-attachments/assets/fe0ebfa7-2725-4eb0-bd67-5d316daa8a63" /> | `RETICLE`<br>`USGC-RETICLE-ST`<br>`PN#: 5200-020`<br><img width="460" alt="RETICLE" src="https://github.com/user-attachments/assets/d5c16dec-2374-4dc3-8e61-d756eb345b65" /> |
| `POLYIMIDE`<br>`USGC-POLYIMIDE-ST`<br>`PN#: 5200-030`<br><img width="460" alt="POLYIMIDE" src="https://github.com/user-attachments/assets/05e4576a-6006-4f01-9a08-a5b54e05d21d" /> | `EPITAXY`<br>`USGC-EPITAXY-ST`<br>`PN#: 5200-040`<br><img width="460" alt="EPITAXY" src="https://github.com/user-attachments/assets/729ea77b-f101-4e22-988d-7f4d404dc37e" /> |
| `METALGATE`<br>`USGC-METALGATE-ST`<br>`PN#: 5200-050`<br><img width="460" alt="METALGATE" src="https://github.com/user-attachments/assets/aa7d4900-6621-4c0d-a989-3c555ebdf1ee" /> |                                                                                                                                                                              |
