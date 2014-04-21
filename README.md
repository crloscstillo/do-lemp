# LEMP Stack

This script is for installing the LEMP stack (Linux, Nginx, MySQL, PHP5) on a fresh Ubuntu Server installation. This was tested on Ubuntu 14.04 x64 installation, but should be working without much modification on other versions.


## Installation
Simply clone this repo inside your `/usr/local/bin` directoy (or anywhere you'd like for that matter). Just make sure the folder is in your $PATH variable.

You should also first **make sure you have git installed**. Example:

```
sudo apt-get update
sudo apt-get install -y git-core
git clone https://github.com/crloscstillo/do-lemp.git /usr/local/bin`
``` 