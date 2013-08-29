# Global Settings and Keybindings

## Settings
##########

Default settings for some Packages and Sublime itself, these settings go
to `Preferences` -> `Settings - User`

	{
		"bold_folder_labels": true,
		"caret_style": "phase",
		"color_scheme": "Packages/Color Scheme - Default/SunburstExtendet.tmTheme",
		"dictionary": "Packages/Language - English/en_GB.dic",
		"font_size": 9,
		"highlight_line": true,
		"highlight_modified_tabs": true,
		"ignored_packages":
		[
			"Vintage"
		],
		"indent_guide_options":
		[
			"draw_active"
		],
		"soda_classic_tabs": true,
		"theme": "Soda Dark fixed.sublime-theme",
		"todo":
		{
			"patterns":
			{
				"TEST": "TEST[\\s]*?:+(?P<test>.*)$"
			}
		},
		"trim_trailing_white_space_on_save": true,
		"word_wrap": false
	}

## Keybindings
##############

Default global keybindings for packages and Sublime go to `Preferences` -> `Key Bindings - User`

	[
		{ "keys": ["ctrl+g"], "command": "expand_selection", "args": {"to": "line"} },
		{ "keys": ["ctrl+l"], "command": "show_overlay", "args": {"overlay": "goto", "text": ":"} },
		{ "keys": ["ctrl+e"], "command": "toggle_comment", "args": { "block": false } },
		{ "keys": ["ctrl+shift+e"], "command": "toggle_comment", "args": { "block": true } },
		{ "keys": ["ctrl+space"], "command": "auto_complete" },
		{ "keys": ["f1"], "command": "goto_documentation" },
		{ "keys": ["shift+alt+up"], "command": "select_lines", "args": {"forward": false} },
		{ "keys": ["shift+alt+down"], "command": "select_lines", "args": {"forward": true} },
		{ "keys": ["ctrl+space"], "command": "replace_completion_with_auto_complete", "context":
			[
				{ "key": "last_command", "operator": "equal", "operand": "insert_best_completion" },
				{ "key": "auto_complete_visible", "operator": "equal", "operand": false },
				{ "key": "setting.tab_completion", "operator": "equal", "operand": true }
			]
		},
		{ "keys": ["ctrl+alt+n"], "command": "side_bar_new_file2" },
		{ "keys": ["f2"], "command": "side_bar_rename" },
		{ "keys": ["ctrl+alt+f"], "command": "side_bar_find_files_path_containing" },
		{ "keys": ["ctrl+shift+k"], "command": "find_under_expand_skip" },
		{ "keys": ["ctrl+shift+period"], "command": "navigate_to_definition" }
	]
