# This is not official extension
There is an official one, it can be supported and maintained better than this one :) 

[https://github.com/fregante/GhostText-for-VSCode](https://github.com/fregante/GhostText-for-VSCode)
[https://marketplace.visualstudio.com/items?itemName=fregante.ghost-text](https://marketplace.visualstudio.com/items?itemName=fregante.ghost-text)


# vscodeghosttext GhostText extension

![ghost_vscode_demo](https://user-images.githubusercontent.com/2128250/130036929-09cc73fb-d781-44e6-a18a-fdd959be9e7f.gif)

https://marketplace.visualstudio.com/items?itemName=samoylenkodmitry.vscodeghosttext

This is an extension for Visual Studio Code https://code.visualstudio.com/.

It also requires [GhostText](https://ghosttext.fregante.com/) plugin installed in your browser.
But default GhostText extension for VSCode is limited and require extra steps to turn on.

* Firefox: https://addons.mozilla.org/en-US/firefox/addon/ghosttext/
* Chrome: https://chrome.google.com/webstore/detail/ghosttext/godiecgffnchndlihlpaajjcplehddca

## Features

* very handy for leetcode grocking
* autostarts with vscode
* have a settings to change temp file suffix. Defaul is: java


## Extension Settings

```
				"properties": {
					"tmpFileSuffix":{
						"type":"string",
						"default":".java",
						"description": "Suffix for a temporary filename. Default: '.java'",
						"scope": "window"
					}
				}
```

This extension contributes the following settings:

* `tmpFileSuffix`: suffix for temp file

## Installation
Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.
```
ext install samoylenkodmitry.vscodeghosttext
```

# If it not working
Please check that `node` command can be run on your system from terminal. If not install `nodejs`.

## Release Notes

### 0.0.3

Postinstall script.

### 0.0.2

Changed activation event from `*` to `onStartupFinished`.

### 0.0.1

Initial release.
