# Aseprite Palettes for GB Studio 🎨

These are the colors [GB Studio](https://gbstudio.dev/) uses when interpreting PNG files as [GameBoy sprites and tiles](https://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial).
This repository exists primarily so that I can easily install these palettes after installing Aseprite.


## Colors 🏷️

These are the colors that GB Studio 3.2 uses.

- `#071821` - "Black"
- `#306850` - "Dark" (Not valid in sprite asset files.)
- `#86c06c` - "Light"
- `#e0f8cf` - "White"
- `#65ff00` - "Transparent" (Valid in sprite asset files only.)
- `#ff00ff` - "Magenta" (Valid in variable width font asset files only.)


## Format 📜

They are stored here in the text `gpl` format that [Aseprite](https://www.aseprite.org/) accepts as built-in palettes (i.e., the [GNU Image Manipulation Program palette format](https://docs.gimp.org/en/gimp-concepts-palettes.html)).
Note that this is different than the binary `.aseprite` format that Aseprite exports and which are provided by the official [GB Studio documentation](https://gbstudio.dev/docs/sprites/).


## Installation 📁

### Automatic Install

Download the extension file from [GB Studio Aseprite Palettes](https://mxashlynn.itch.io/gb-studio-aseprite-palettes) to your machine and double-click it.


### Manual Install

1. Copy the `package.json` file and every `.gpl` file from this repository to `<Application Path>\Aseprite\data\extensions\gb-studio-palettes`, where `<Application Path>` is the install location of Aseprite on your machine.
2. Restart Aseprite.


## Rights 🏳️‍🌈

The files in this repository are in the public domain.

