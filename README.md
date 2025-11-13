# kanata-config
This is my config for Kanata.

The config is based on a Swedish full size keyboard.

It does 5 main things:
- Remaps ESC to CAPSLOCK and vice versa
- Home row mods
- Toggleable arrow layer, where it turns h j k l into arrow keys
- Coding mode remapping of å ä ö and some other keys for better coding ergonomics
- Swaps the shift layer functionality for number row

## Remapping  ESC to CAPSLOCK
This is very simple. In every kanata layer in this configuration the ESC and CAPSLOCK key are swapped.

## Home row mods
This is based upon the example from offical kanata github, where they a simple home row mod configuration. It is adjusted for my personal preference for hold times and also duplicated into the coding layer.

## Toggleable arrow layer
Holding ESC for a short time turn the h j k l into arrow keys, for easier navigation. Exiting the arrow layer is done by pressing i. This is of course based on Vim transtions between normal and insert mode. 

## Coding mode layer
You enter this layer by pressing LCTL + LALT + ,. It remaps according to the following scheme:

| Key | Remap | Shift remap |
| --- | ----- | ----------- |
| å   | [     | }           |
| ¨   | ]     | }           |
| ö   | ;     | :           |
| ä   | \     | \|          |
| <   | ^     | ~           |
| ,   |       | <           |
| .   |       | >           |

Going back to the base layer is done via pressing LCTL + LALT + ..

## Number row shift layer swap
For all layers in this config, the number row (only the number keys) has been shift swapped. Meaning that to type a number you need to press SHIFT + NUMBER. Pressing only the number key will result in ! for key 1 and " for key 2 and so on. For the key 4, the AltGr behaviour has been swapped as well with it's Shift behaviour. Meaning that pressing 4 will produce $ instead of ¤.
