# AudioConverterMenu
A dolphin menu to convert files to flac or to mp3 high quality.

## Usage on Dolphin (KDE)

Use right-clic on a multimedia file, and enter in the **Audio** submenu:

![Audio submenu](illustration/audioconverter.png)

## Installation

Use `kf5-config --path services` to find your kservice directory. A commonly used directory is `$HOME/.local/share/kservices5/`

Add `audioConverterMenu.desktop` file in your kservice directory. It will add a new "Audio" entry in the right-clic menu.

Note: On plasma6, the directory is now `$HOME/.local/share/kio/servicemenus/`.

## Dependancies

* [ffmpeg](https://ffmpeg.org/) to convert files
* [lame](http://lame.sourceforge.net/) for mp3 support
