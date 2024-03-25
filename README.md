# Corne keymap config


> Chordic layout example from [here](keyboards/crkbd/keymaps/gfolgert/images/01-chordic-layout-full.png)

![image](https://github.com/ryodeushii/corne-wireless-choc/assets/15180311/00b69699-dbac-4242-8059-8a9e66b67ef9)




# actual chords setup::



```bash
# generate chords from wordlist
node filter.js > chords.txt
# import macros & chords to keymap file
node import-chords.js corne.keymap
```

[Sample of the setup](https://dlip.github.io/posts/hybrid-keyboard-chording-with-zmk/)
