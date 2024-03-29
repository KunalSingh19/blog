---
layout: post
title:  "Termux Style"
subtitle: "Simple script to change color-schemes and fonts for Termux."
categories:
  - Technology
  - How To
  - Termux
tags:
  - Termux
  - Phone
  - Theme
series:
  - Termux
thumbnail: "https://raw.githubusercontent.com/adi1090x/termux-style/master/images/main.gif"
usemathjax: false
---
# Termux Style

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

![gif](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/main.gif) <br />

> **`termux-style` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# go to home dir - 
cd $HOME

# clone this repository - 
git clone https://github.com/adi1090x/termux-style

# change to termux-style dir -
cd termux-style

# to install it, run -
./install

# And Follow the steps, it'll be installed on your system.
```

### Run

Run `termux-style` & select the right option -

```bash
$ termux-style

    ┌──────────────────────────────────────────────────┐
    │░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░▄▄▄░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────┘
    [*] By- Aditya Shakya // adi1090x

    [C] Colors (89)
    [F] Fonts (20)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 90 popular color-schemes.
+ 20 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />

### Previews

|Colorschemes|Fonts|
|--|--|
|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/colors.gif)|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/fonts.gif)|

|Import - URL|Import - Local|
|--|--|
|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/url.gif)|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/local.gif)|

|Install|Uninstall|
|--|--|
|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/install.gif)|![img](https://raw.githubusercontent.com/adi1090x/termux-style/master/images/uninstall.png)|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
