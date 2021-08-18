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


## Release Notes

### 0.0.1

Initial release.