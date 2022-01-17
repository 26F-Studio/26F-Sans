# 26F-Sans

[点击这里来阅读简体中文版本 Click here for the Simplified Chinese Version](README_SC.md)

The theme font for 26F Studio.
**WARNING: THIS FONT IS CURRENTLY UNDER CONSTRUCTION AND IS NOT COMPLETED YET.**

This repository stores the theme font of 26F Studio, the 26F Sans. We plan to use this font in our games and website in the future.

## Features (Planned)
- Multi-language support
- Rich OpenType Features
- Variable font weigh and width

## Font families (Planned)
- 26F Sans
- 26F Mono
- 26F Serif

## Install 26F Sans to your device

Please download the stable build of the font in the latest Release. You can always find the latest preview version (beta) in GitHub Actions.

1. Download and extract 26F Sans to your computer.

### macOS
2. Open the font files in Font Book and then Click on the “Install Font” button.

### Linux
2. Move the font files to `~/.local/share/fonts` (or `/usr/share/fonts` if you want to install fonts system-wide).
3. Run `fc-cache -f -v` in your terminal.

### Windows
2. Select all font files in the folder, right-click any of them, then pick “Install” from the menu.

## Editing
The source files are located in the `Source` folder. To open them,

### macOS
1. Download and install the Glyphs app (if you have’t done so).
2. Open the `.glyphs` files using Glyphs.

### Other platforms
1. Locate the `.ufo` (Universal Font Object) files and open them using a font editing app on your platform.

## Build from source
You can either build the fonts from Glyphs or other font editing programs directly, or you can choose to build them in the command line use the Google Font Tools (`gftools`). Notice that you have to install Python 3.7 or later to use `gftools`.

1. Install `gftools` by executing the following command:
   ```
   $ pip install gftools
   ```
2. Navigate to `../Source/glyphs/` in the command line.
3. Execute the following command:
   ```
   gftools builder config.yaml
   ```
4. Find the compiled fonts in the `fonts` folder.

## License
26F Sans is under a [SIL Open Font License, Version 1.1](OFL.txt). You can use, modify, redistribute the compiled fonts and the source files free of charge and you do not need to attribute to 26F Studio (But we would really appreciate that if you do so).

The [build.yml](.github/workflows/build.yml) files was adapted from the [JetBrains Mono Repository](https://github.com/JetBrains/JetBrainsMono/blob/master/.github/workflows/build-fonts.yml), which was under a [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

The other part of the source code in this repository is under a [MIT License](MIT.txt).

## Credits
**Type Designer**
C29H25N3O5 <michaelgu495@gmail.com>
