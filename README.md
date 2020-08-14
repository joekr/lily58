# lily58 keymap

This is my lily58 keymap build using the [QMK firmware](https://github.com/qmk/qmk_firmware)

## steps

- use https://jhelvy.shinyapps.io/qmkjsonconverter/ to convert json to keymap.c

### old manual way

- `vim keymaps/ergodox/keymap.c`
- `qmk compile -kb lily58 -km my_lily58_keymap`
- Then use [QMK Toolbox](https://qmk.fm/toolbox/)
