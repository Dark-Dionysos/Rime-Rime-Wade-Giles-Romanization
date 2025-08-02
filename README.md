# Wade-Giles Romanization Input Schema for Rime
This is an input schema for [Rime](https://rime.im/), with which you can input Chinese character through Wade-Giles Romanization.

This schema is standalone (independent of any other schemas) which is suitable for those who don't want to have other schemas on their disk. Further, the schema provides the reverse lookup function, and this function depends on the existence of luna_pinyin, stroke and jyut6ping3 schema.
## Installation
For Windows 11 user:
1. Download and install the [Weasel](https://rime.im/download/)
1. Download the schema files, you can download directly on the website or use `git clone` command.
1. Copy the yaml files to your user directory. The default user directory path is `%APPDATA%\Roaming\Rime`(just copy it to your file explorer).
1. From `Starting Menu`, click `All > Weasel > Weasel Setting`.
1. In the prompted windows tick the Wide-Giles Romanization and detick all others, then press enter key twice.

For Mac and Linux user, please refer the tutorial on how to install new input schema at [Rime](https://rime.im/) official website.
## Usage
- Press `win+space` key to call the input method.
- Type `v` for the `ü`.
- Press `F4` then press `2` to toggle simplified Chinese character output.
- Press `u` for jyutping (Cantonese phonetic) reverse lookup, that input a Cantonese phonetic and meanwhile output a Wade-Giles Romanization for the same character.
- Press the grave for pinyin reverse lookup.
- Press the `x` for stroke reverse lookup.
