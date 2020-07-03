## Introduction

No Troublian is a set of bash scripts that automatically setup your Debian10 system with useful packages and definitions.

No Troublian adds:
+ Buster-backports;
+ Fonts (FiraCode, IBM-Plex and Roboto);
+ Icons (Moka, Obsidian and Papirus);
+ Themes (Adapta and Arc);
+ ElementaryOS's wallpapers;
+ Flatpak;
+ Gaming packages (Nvidia, Steam, Wine and Lutris).

## Requirements

These scripts were made to only work on Debian10 Stable because of the packages available and Buster-backports. If you want to run Debian Testing, install No Troublian first and then update your sources to testing.

You also need:
+ Sudo privileges or be root;
+ Deb sources (/etc/apt/sources.list) must have **non-free** and **contrib**.

## Usage

Run 'setup' file with sudo or in root:

```bash
$ sudo ./setup

or

$ su
your root password: (*)
$ ./setup
```
> The 'setup' file was already made an executable.

## Why This Exists? & Bash?

I made No Troublian to help me setup a system automatically and keep track of all the things that I want to have from the beginning. This may only help setup a Debian10 system but you can take advantage of this to make a script which works with your package manager and system.

Bash is powerful on its own and because I wanted to learn a language that would help me better communicate with my system.
