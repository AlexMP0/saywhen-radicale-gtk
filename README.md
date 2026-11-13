**Inspired by the [saywhen](https://github.com/dmi3dmi3/saywhen) android app.**

This is a clone of the saywhen app to work with a radicale server on desktop in the aspect of Adwaita apps.
It launches a small dialog box in which you enter a new event in natural language and it parses the text automatically. It sends the proper event to the radicale server.

***This app is fully vibecoded, use at your own risk.***

Run `saywhen --init` to set credentials and create the config file for the first time.

## CLI flags:
 
`-n` simply displays what was parsed, without saving; `--ics` outputs the generated file.

`-y` saves without prompting.

`--check` tests the connection to Radicale.

`--selftest` runs the parser's test suite.

If no arguments are provided, it enters interactive mode. If you have `prompt_toolkit` installed, the preview updates in real time as you type, similar to SayWhen.

Expect this program to behave similarly to the saywhen android app.
