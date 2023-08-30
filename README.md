# dpremy tmux config, shell aliases, and cheat sheets

## Purpose

This repository contains the dotfiles and configs I use with tmux. It is desinged to work with [dotfiler](https://github.com/svetlyak40wt/dotfiler), but can easily be used without it.

## Installation

```shell
# if you don't already have dotfiler, clone it to your home directory
git clone -q https://github.com/svetlyak40wt/dotfiler ~/.files

# add this repo to dotfiler
~/.files/bin/dot add https://gitlab.com/dpremy/dot-tmux.git

# update the symlinks in your home directory
~/.files/bin/dot --skip-pull update
```

## Usage

See [tmux_cheatsheet.pdf](./cheatsheets/tmux_cheatsheet.pdf) or [tmux_cheatsheet.md](./cheatsheets/tmux_cheatsheet.md) for some of the most common key bindings. [.tmux.conf](.tmux.conf) also has comments and may be worth reviewing.