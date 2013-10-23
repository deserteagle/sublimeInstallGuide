# JSLint
########

requires Java on the local machine

Settings for `Preferences` -> `Package Settings` -> `JSLint` -> `Settings - User`

	{
                // Options pass to jslint.
                "jslint_options": "--eqeq --maxerr 9999999 --sloppy --white --timeout 60 --browser",

                // Ignore errors, regex.
                "ignore_errors":
                [
                        "(?:\\$|Ext|console)' was used before"
                ]
}
