# ZMK configuration for a Corne keyboard (36 keys) in bépo

This is a repo for a bépo layout on Corne keyboard with 36 keys. Being used to bépo (or, to be correct, "bwpo") on a Minidox, a quite similar keyboard using qmk, I wanted to have the same layout for a wireless Corne. 

For more information on the layout, you can go directly to [the qmw page](https://github.com/qmk/qmk_firmware/tree/user-keymaps-still-present/keyboards/maple_computing/minidox/keymaps/bepo).

I made some modifications :
- A capslock key and a printscreen key have been added.
- On the third layer, the numeric one, I added a dot and a comma, for easy access.
- I put altgr on the right, as the original keyboard didn’t have one. Which means that now, alt+y is unavailable. Altgr+h too. Don’t know if it’s a problem for anybody. Maybe there’s a way to make them available, but I don’t have a use for them.
- There are two possible apostrophes : ' and ’.
- The compose key has to be chosen as the left windows key. It can be accessed by holding for a short time Z or F.

To make it work, you have, of course, to choose the bépo layout (the keymap editor, which is really useful, will not give you the proper letters).

Here is the layout :

![bepo layout](https://github.com/SultanRahi/zmk-config-corne-bepo/blob/master/bepokeymap.svg?raw=true)
