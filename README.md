# Startupper

This is an automatic MacOS system provisioner, based on Ansible.

This script allows you to install and configure your new laptop using three different profiles: developer, analyst, designer, IT.

If you are using a git yadm the repository will be downloaded and configured via the saved dotfiles.

## Installation

### MacOS

To install on MacOS

```
bash <(curl -fsSL https://raw.githubusercontent.com/savez/startupper/master/bin/install.macos)
```

## Programs

### developers
 
- docker
- awscli
- google-cloud-sdk
- docker-completion
- docker-compose
- docker-credential-helper-ecr
- imagemagick
- node
- yarn
- yarn-completion
- php
- golang
- nvm
- iterm2
- visual-studio-code
- postman
- dbeaver

# Thanks

This project was born thanks to [SparkFabrik](<https://github.com/sparkfabrik>).
Looking at their repository <https://github.com/sparkfabrik/sparkdock> I got the inspiration
