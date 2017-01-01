Croatian US keyboard for Linux

This is standard US keyboard layout where you get Croatian characters or layout by pressing AltGR (right Alt) key.
In Linux, this keyboard is known as hr-US (in X11) or crous (in console).
In short, developers like it.

Keyboard layout for different operating systems:
* [Croatian-US-linux](https://github.com/kost/Croatian-US-linux)
* [Croatian-US-windows](https://github.com/kost/Croatian-US-windows)
* [Croatian-US-mac](https://github.com/kost/Croatian-US-mac)

## Installation

crous.map is console map 
the rest is for X11 or Xorg. If you have decent Xorg release, layout is already
included - you don't have to install anything - you can just set it by:

```
setxkbmap hr us
```

or by setting up in xorg.conf:

```
Option "XkbLayout" "hr(us)"
```

## Acknowledgements

It is collection of different keyboard definitions from different authors.

