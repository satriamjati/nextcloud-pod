# nextcloud-pod

Install nextcloud on your podman. Tested on Ubuntu 24.04 LTS.

Configurable
- listext
- listusers
- pass
- install (some still hardcoded)

Installation
- ./build
- ./install


Note: 
Sometimes external storages are not initialized automatically, hence not found in files:scan. You can fix this by logging user in manually or use `./loguser`. Then file scan and generate preview again: `./scan && ./generate`. In some cases, you may need to log more than a user, use `listlog` for multiple login. If there is any other error, try `./fixperms` before try reinstalling.
