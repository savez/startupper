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

### analyst

- iterm2
- visual-studio-code
- postman
- node
- yarn
- yarn-completion
- php
- golang
- python@3.10
- dbeaver
- openrefine
- awscli
- google-cloud-sdk

### designer

- gimp
- figma

### it

- anydesk
- microsoft-remote-desktop

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

### general programs

- slack
- google-chrome
- firefox
- bitwarden
- miro
- hot
- clickup
- homebrew/cask-versions/tunnelblick-beta
- neofetch
- thefuck
- yadm

# Thanks

This project was born thanks to [SparkFabrik](<https://github.com/sparkfabrik>).
Looking at their repository <https://github.com/sparkfabrik/sparkdock> I got the inspiration
