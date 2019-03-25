# Your Dotfiles
This is the default initialized dotfiles provided for you
when you first `pydotfiles init` a directory.

> A solid starting-set of dotfiles to quickly hit the ground
  running

current version: v3

## Overview
TODO

## Features
- [macOS] Sets your background automatically to a given image
  when `pydotfiles install` is ran
- Downloads common utilities that are useful to **YOU**, e.g.:
  - `coreutils`
  - `wget`
  - `bash`
  - `unrar`
  - `grep`
  - `vim`
  - And so many more! Adding in new utilities to install is as
    simple as editing the `settings.yaml` file in the `linux`
    or `macos` directory
- [macOS] Downloads for you any third-party applications that
  you want, e.g.:
  - [flux](#TODO)
  - [atom](#TODO)
  - [Google Chrome](#TODO)
  - [Firefox](#TODO)
  - [VLC](#TODO)
  - [iTerm 2](#TODO)
  - And so many more! Adding in new applications to install is as
    simple as editing the `settings.yaml` file in the `linux`
    or `macos` directory
- [macOS] Tired of your cluttered Dock when you first boot into
  your laptop? Don't bother! This repo will clear out the clutter,
  and only add in the applications that you want, e.g.:
  - Notes
  - iTunes
  - Firefox
  - ![](#TODO-add-in-before-after-image-of-dock)
  - And so many more! Adding in new applications for your default dock
    is as simple as editing the `settings.yaml` file in the `linux`
    or `macos` directory
- Adds in a [Message of the day](#TODO) for when you log into a terminal
  session
- Provides some pretty nice quality-of-life improvements to your normal
  terminal experience, described in the [utilities file](#TODO):
  - Sets auto completion to on without worrying about case
  - Adds in auto-coloring of listing and grepping actions
  - Automatically lists a directory when you `cd` into it
  - [macOS] Enables you to enter `f` in any directory to open up Finder
  - Provides some convenience backtracking command. If you've ever
    worked in a heavily nested directory structure, the ability to
    enter `.6` to go up 6 directories at one time instead of having
    to type `cd ../../../../../../` really shines.
  - And so much more that can be customized however you want!

## Forking Guide
TODO

## Installation
TODO

## Repo Navigation Help
```
.
├── common
│   ├── bashrc.symlink
│   ├── inputrc.symlink
│   ├── motd.symlink
│   ├── settings.json
│   └── utilities.symlink
├── img
│   └── background.png
├── linux
│   └── settings.yaml
└── macos
    ├── bash_profile.symlink
    ├── settings.yaml
    └── start
```

### Common Directory
- Contains configurations that can be applied to both linux
  and macOS environments

### Linux Directory
- Contains configurations and start-up scripts specific to
  linux environments

### MacOS Directory
- Contains configurations and start-up scripts specific to
  the macOS environment
