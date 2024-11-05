# ZMK configuration for a Corne keyboard (36 keys) in bépo

This is a repo for a bépo layout on Corne keyboard with 36 keys. Being used to bépo (or, to be correct, "bwpo") on a Minidox, a quite similar keyboard using qmk, I wanted to have the same layout for a wireless Corne. 

For more information on the layout, you can go directly to [the qmw page](https://github.com/qmk/qmk_firmware/tree/user-keymaps-still-present/keyboards/maple_computing/minidox/keymaps/bepo).

I made some modifications :
- A capslock key and a printscreen key have been added.
- On the third layer, the numeric one, I added a dot and a comma, for easy access.
- I added altgr on the left and on the right, as the original keyboard didn’t have one.
- There are two possible apostrophes : ' and ’.
- I added an en dash and an em dash, as well as French double angle quote, as I’m using them quite often.
- The compose key has to be chosen as the left windows key. It can be accessed by holding for a short time Z or F.

To make it work, you have, of course, to choose the bépo layout (the keymap editor, which is really useful, will not give you the proper letters).

Here is the layout :

![bepo layout](https://github.com/SultanRahi/zmk-config-corne-bepo/blob/master/bepokeymap.png?raw=true)
