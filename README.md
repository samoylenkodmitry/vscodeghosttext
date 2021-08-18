# vscodeghosttext GhostText extension

## Features

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

# If it not working
Please check that `node` command can be run on your system from terminal. If not install `nodejs`.

## Release Notes

### 0.0.3

Postinstall script.

### 0.0.2

Changed activation event from `*` to `onStartupFinished`.

### 0.0.1

Initial release.