# Terminal Configuration

This is one of the most important components of my life. I spend like 90% of my time in the terminal, so getting this setup is very important.

Disclaimer my full set of dotfiles can be found at [github.com/KritR/dotfiles](https://github.com/KritR/dotfiles).

## Unix Configuration

### Terminal Emulator

For our terminal on a Unix system, we adopt [Kitty](https://github.com/kovidgoyal/kitty) or [Alacritty](https://github.com/alacritty/alacritty).
These are both high performance GPU accelerated terminal emulators with a boatload of features. And they work cross platform.

Current choice is Kitty on OS X because you can get rid of the window borders and it has a higher degree of customization. We can also render PDF's in the terminal :)

The theme we use with the terminal is [Iceberg](https://cocopon.github.io/iceberg.vim/), a nice plain dark blue theme which is relatively visually appealing.

### Shell

For our shell of choice we use Zsh with [OhMyZsh](https://github.com/ohmyzsh/ohmyzsh)

#### Shell Plugins

The current list of plugins is relatively large and will be constantly up to date in the config files stored on Github.

The primary ones to keep note of are the following:

- [zsh-z](https://github.com/agkozak/zsh-z)
  which offers immediate jumping to recent directories without full path names.

- [wd](https://github.com/mfaerevaag/wd)
  which allows you to set bookmarks to directories with like short names

- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
  which automatically suggests full commands. very useful if you're following a similar workflow over and over or needed to search for a command.

- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
  which automatically highlights different parts of commands. just kinda nice :)

## Windows Configuration

### Terminal Emulator

Currently [Windows Terminal](https://github.com/microsoft/terminal) is well suited for our needs. It supports tabs, and the fluent design, and is relatively performant. It's also agnostic to backends and supports WSL natively.

### Shell

We use the open source [PSCore](https://github.com/PowerShell/Powershell) for all our windows shell operation needs. This way it's compatible with other OS's if need be.

### Shell Plugins

We use [Z for Powershell](https://github.com/vincpa/z) and that's about it for the moment.
