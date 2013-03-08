# Bracket Highlighter
#####################

## Settings
###########

Settings for `Preferences` -> `Package Settings` -> `Bracket Highlighter` ->
`Settings - User`

	{
		"match_brackets_only_when_between": true,
		"match_adjacent_only" : false,
	
		"quote_scope" : "bracket.quote",
		"curly_scope" : "bracket.curly",
		"round_scope" : "bracket.round",
		"square_scope": "bracket.square",
		"angle_scope" : "bracket.angle",
		"tag_scope"   : "bracket.tag",
	
		"quote_style" : "underline",
		"curly_style" : "solid",
		"round_style" : "outline",
		"square_style": "outline",
		"angle_style" : "solid",
		"tag_style"   : "outline"
	}

## Coloring
###########

To get better colors for the Highlighter, copy your colorscheme. This can be
found usually in the sublime package directory (`Preferences` -> `Browse Packages...`)

Open `Color Scheme - Default`, locate the `.tmTheme` file of your prefered Scheme
and add these snippet into the `<array>` tag:

	<dict>
					<key>name</key>
					<string>Bracket Tag</string>
					<key>scope</key>
					<string>bracket.tag</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#FF5500</string>
					</dict>
			</dict>
			<dict>
					<key>name</key>
					<string>Bracket Curly</string>
					<key>scope</key>
					<string>bracket.curly</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#00FF00</string>
							<key>background</key>
							<string>#333355</string>
					</dict>
			</dict>
			<dict>
					<key>name</key>
					<string>Bracket Round</string>
					<key>scope</key>
					<string>bracket.round</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#5555FF</string>
					</dict>
			</dict>
			<dict>
					<key>name</key>
					<string>Bracket Square</string>
					<key>scope</key>
					<string>bracket.square</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#5555FF</string>
					</dict>
			</dict>
			<dict>
					<key>name</key>
					<string>Bracket Angle</string>
					<key>scope</key>
					<string>bracket.angle</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#AE81FF</string>
					</dict>
			</dict>
			<dict>
					<key>name</key>
					<string>Bracket Quote</string>
					<key>scope</key>
					<string>bracket.quote</string>
					<key>settings</key>
					<dict>
							<key>foreground</key>
							<string>#449944</string>
					</dict>
			</dict>
