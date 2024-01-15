# Aseprite Palettes for GB Studio 🎨

These are the colors [GB Studio](https://gbstudio.dev/) uses when interpreting PNG files as [GameBoy sprites and tiles](https://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial).
This repository exists primarily so that I can easily install these palettes after installing Aseprite.


## Format 📜

They are stored here in the text `gpl` format that [Aseprite](https://www.aseprite.org/) accepts as built-in palettes (i.e., the [GNU Image Manipulation Program palette format](https://docs.gimp.org/en/gimp-concepts-palettes.html)).
Note that this is different than the binary `.aseprite` format that Aseprite exports and which are provided by the official [GB Studio documentation](https://gbstudio.dev/docs/sprites/).


## Installation 📁

To install these, copy the entire content of this repository to `<Application Path>\Aseprite\data\extensions\gb-studio-palettes`, where `<Application Path>` is the install location of Aseprite on your machine.


## Rights 🏳️‍🌈

The files in this repository are in the public domain.


## Colors

These are the colors that GB Studio 3.2 uses.

<ul>
<li><span style="background-color: rgb(  7,  24,  33); color: rgb(0, 0, 0);">#071821 - "Black"</span></li>
<li><span style="background-color: rgb( 48, 104,  80); color: rgb(0, 0, 0);">#306850 - "Dark"</span> <small>Not valid in sprite asset files.</small></li>
<li><span style="background-color: rgb(134, 192, 108); color: rgb(0, 0, 0);">#86c06c - "Light"</span></li>
<li><span style="background-color: rgb(224, 248, 207); color: rgb(0, 0, 0);">#e0f8cf - "White"</span></li>
<li><span style="background-color: rgb(101, 255,   0); color: rgb(0, 0, 0);">#65ff00 - "Transparent"</span> <small>Valid in sprite asset files only.</small></li>
<li><span style="background-color: rgb(255,   0, 255); color: rgb(0, 0, 0);">#ff00ff - "Magenta"</span> <small>Valid in variable width font asset files only.</small></li>
</ul>
