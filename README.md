# Svorak A5

My Swedish Dvorak programmer keyboard layout

This layout is based on [Svorak A5](http://aoeu.info/layouts/files/magnus-xkb-se) from [aoeu.info](http://aoeu.info/). Then I have moved, added and removed some keys.

## Installation

To install the layout into your X server you copy the layout into the Swedish symbols file:
```bash
$ cat svorak_a5 >> /usr/share/X11/xkb/symbols/se
```

Now the layout can be activated with:
```bash
$ setxkbmap se svorak
```
