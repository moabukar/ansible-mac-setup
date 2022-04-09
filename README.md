# MacOS Monterrey Setup using Ansible

This is my personal Ansible configuration for setting up a DevOps Mac setup from scratch. 

## How to install

There's a simple shell script in `bin/bootstrap` which will perform the initial steps of automating. 

## What am I installing

- Everything located in ```ansible-osx.yml```

- ZSH + Oh My Zsh as the primary shell
- Homebrew for package management
- ASDF for version management (along with plugins and default versions for ruby, python, javascript, elixir and erlang)
- Virtualbox, Vagrant and Docker
- VSCode + default plugins and configuration
- A selection of Android SDK's
- Lots of other tools and utilities

## How can I customise? 

Everything can be customised by editing `ansible_osx.yml`.

