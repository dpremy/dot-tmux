# dpremy tmux config, shell aliases, and cheat sheets

![Build Status](https://ci.davidremy.me/api/badges/dpremy/dot-tmux/status.svg)

## Purpose

This repository contains the dotfiles and configs I use with tmux. It is desinged to work with [GNU stow](https://www.gnu.org/software/stow/), but can easily be used without it.

## Installation

```shell
# if you don't already have GNU stow, install stow for your OS

# clone this repo in to a .files directory
git clone -q https://gitlab.com/dpremy/dot-tmux.git ~/.files/dot-tmux

# use stow to symlink this 'package' in to your home directory
stow -d ~/.files/ -t ~/ -S dot-tmux
```

## Usage

See [tmux_cheatsheet.pdf](./cheatsheets/tmux_cheatsheet.pdf) or [tmux_cheatsheet.md](./cheatsheets/tmux_cheatsheet.md) for some of the most common key bindings. [tmux.conf](.config/tmux/tmux.conf) also has comments and may be worth reviewing.
