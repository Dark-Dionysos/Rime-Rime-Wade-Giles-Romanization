# Wade-Giles Romanization Input Schema for Rime

This is an input schema for Rime, with which you can input Chinese characters through Wade-Giles Romanization.

This is a standalone schema (independent of any other schemas), suitable for those who don't want other schemas on their disk.
The schema provides the reverse lookup function, which depends on luna_pinyin, stroke, cangjie5, and the jyut6ping3 schema.

# Installation

For Windows 11 users:
1. Download and install the Weasel
1. Download the schema files, you can download directly on the website or use the git clone command.
1. Copy the YAML files to %APPDATA%\Roaming\Rime.
1. Open the Starting Menu, click All > Weasel > Weasel Setting.
In the prompted windows tick the Wide-Giles Romanization and detick all others, then press the Enter key twice.

For Mac and Linux users, please refer to the tutorial on the Rime official website.

# Usage
- Press the `Win + Space` key to call the input method.
- Type `v` for the ü.
- Press `F4` then press `2` to toggle simplified Chinese character output.
- Press `u` for jyutping (Cantonese phonetic) reverse lookup. Then input a Cantonese phonetic and the corresponding Wade-Giles Romanizationwill be output.
- Press the grave for pinyin reverse lookup.
- Press the `X` key for stroke reverse lookup.
- Press the `v` key for tsangchieh code reverse lookup.
