# This repository contains modules for [LIT](https://github.com/username000101/LIT) userbot

## Look for a branch with your architecture and load modules only from there.

### How to install it?
#### The first way
	1. Download the module(.so) to any location on your device (although it is best to keep them in one place (in $LIT_INSTALL_PREFIX/.lit/modules, for example)
	2. Find the module configuration(.json) in the repo
	3. Copy the configuration in $LIT_INSTALL_PREFIX/.lit/modules.json to the "modules" object, replacing "path": "/path/to/your/libmodulename.so" with the path to the module
#### The second way
	1. Download the module(.so) to any location on your device
	2. Run LIT with this command:
	```bash
	[sudo] [./]LIT --install /path/to/downloaded/module.so
	```
