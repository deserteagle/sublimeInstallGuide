# Packages and PackageControl
#############################

## PackageControl
#################

Install PackageControl by copy & paste the code below into the Sublime console.
The console can be opened by `ctrl+shift+'` (accent) or via `View` -> `Show Console`

	import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print('Please restart Sublime Text to finish installation')

If that does not work, check [this site](http://wbond.net/sublime_packages/package_control/installation "package control homepage")
for alternative ways :-)

After the installation is done, installing or removing packages should work via
the command palette `Package Control:`

## Nearly Required Packages
###########################

This plugins are nearly required for a smooth and usable IDE:

	* "All Autocomplete" uses all open files for autocompletion
	* "Bracket Highlighter" better bracket highlighting
	* "Emmet"/"ZenCoding" html helper
	* "SideBarEnhancements" better contextmenue for the sidebar
	* "sublimelint" syntax linter for sublime
	* "ctags" offers go-to-definition stuff
	* "ctags for php" with some extended features, requires "ctags"

Details and settings for these packages can be found in their
corresponding documentation.

## Very Useful Packages
#######################

These packages are quite handy and recommended for extensive usage

	* "Alignment" automatic alignment, eg. for array definitions
	* "DocBlockr" inteligent php docblock generator
	* "Goto Documentation" open php.net manual for the current function
	* "Inc-Dec-Value" increment and decrement numeric (dec, bin, hex) values with arrow keys
	* "Inline Calculator" solving simple mathematical expressions within the editor
	* "jQuery" ready to use jQuery snippets
	* "SublimeTODO" //@TODO: (etc.) processor
	* "changetracker" displays unsaved changes to a file by adding a bullet to the lines in question
	* "jslint" javascript linter

## Noteworthy Packages
######################

Title says it all

	* "Dictionaries" spellchecking for other languages
	* "Format SQL" obvious
	* "Function Name Display" displays the current function name in the status bar
	* "Pretty JSON" JSON formater
	* "Theme Soda" skin for sublime
	* "Sublimipsum" lorem ipsum generator
	* "StringEncode" string manipulating functions
	* "extjs" snippets and unicode encode/decode commands
	* "git" git integration
	* "GernateUUID" UUID generator
	* "WordCount" counts words, chars etc. in buffer
