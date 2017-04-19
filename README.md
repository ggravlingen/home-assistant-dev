# home-assistant-dev

These are my settings for setting up a dev environment for Home Assistant on Windows.

1: Install Oracle VM Virtualbox

2: Download Ubuntu (https://www.ubuntu.com/) and use the iso to install a Virtual Machine

3: Setup network for the virtual machine. Use bridged adapter (important!) or your virtual machine won't be able to discover other devices on the network.

4: Follow the guidelines (https://home-assistant.io/developers/development_environment/) on how to setup a local repository. I had to run the bin dos2unix on all files in the script-folder for the setup script to work.
