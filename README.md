# Kanata Keymap

`config.kbd` loads the keyboard source, layers, modifier aliases, chords, and composer.

## Home-row modifiers

Same-hand rolls type the key; opposite-hand presses activate the modifier.

- Left: `a` Super, `s` Alt, `d` Shift, `f` Ctrl, `g` App
- Right: `h` App, `j` Ctrl, `k` Shift, `l` Alt, `scln` Super

## Layers

- Hold `space` for Vim navigation.
- Hold `tab`, `grv`, `caps`, or `ret` for their modifier and function layers.
- Hold a modifier with the other hand to use its layer mappings.

## Files

- `layers/`: physical key source and layer maps.
- `lib/mods.kbd`: modifier aliases.
- `lib/utils.kbd`: reusable modifier templates (`mod`, `mod-long`, `mod-timeout`).
- `lib/options.kbd`, `lib/chords.kbd`: timing/configuration and key chords.
- `composer/`: text expansion definitions.

Check the config with `kanata --check --cfg config/keymap/kanata/config.kbd`.
