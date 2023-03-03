# st - simple terminal

st is a simple terminal emulator for X which sucks less.

## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```
    make clean install
```

## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```
    tic -sx st.info
```

See the man page for additional details.

## Patches

- scrollback-mouse-20220127-2c5edf2
- scrollback-reflow-0.8.5
- scrollback-0.8.5
- copyurl-multiline-20220221-0.8.5
- desktopentry-0.8.5
- newterm-0.9
- delkey-20201112-4ef0cbd
- hidecursor-0.8.3
- dynamic-cursor-color-0.9
- xresources-20200604-9ba7ecf
- ligatures-boxdraw-20221120-0.9
- font2-0.8.5
- boxdraw_v2-0.8.5

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
