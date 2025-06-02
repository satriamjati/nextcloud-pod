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
Make sure to login all users which configurated on listext to initiate external storage. Then file scan and generate preview again: `./scan && ./generate`.
