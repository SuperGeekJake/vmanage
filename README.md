# vmanage

### Apache Virtual Host Manager for Linux.

Built and tested on Ubuntu. Meant for development environments. Use at your own risk.

## Installation

1. a2enmod vhost_alias userdir
2. chmod +x ./vmanage
3. mv ./vmanage /usr/local/bin

## Command
vmanage [create|delete] {domain}
