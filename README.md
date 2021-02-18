# pico8-vsix

Up-to-date extension for editing and running pico8 files.

*Syntax highlighting updated to match **version 0.2.2**.*

## Features

* Syntax highlighting for *.p8 files
* If used in workspace mode will set the pico8 home to your workspace
* CMD+R to open automatically run the .p8 you're editing in pico8

## Requirements

You need to have pico8.

## Extension Settings

This extension contributes the following settings:

* `pico8.executablePath`: path to where your pico8 actually is (default is `/Applications/PICO-8.app/Contents/MacOS/pico8`)

## Known Issues

 * Missing `#include` highlighting
 * Missing v2.0 operators highlighting
 * Missing P8SCII highlighting

 If you can help with any of the above issues, feel free to make a pull request.

## Release Notes

### 0.2.2

 * Initial fork from pico8-vscode
 * Changed versioning scheme to match PICO8 version
 * Updated P8 API highlighting

### 0.0.1

 * Initial release of pico8-vscode

## License

All code is by John Barton and [MIT licensed](/LICENSE.md) with the exception of the syntaxes folder which is covered by [the original author's license](/syntaxes/OSSREADME.json)
