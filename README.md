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

Post-config
- `./loguser` or `./listlog` or manually log one or more users (possibly all needed) to avoid external storage not initialized

Troubleshoot:
- `./fixperms` 
- `./stop && ./run`
