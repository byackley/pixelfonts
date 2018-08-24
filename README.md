# pixelfonts

## What are these?

These are tiny monospaced pixel fonts in a variety of sizes. These top-level directories are all named after the pixel size of a single character, and the files within are named for the 256-character segment of Unicode they contain (so, for instance, 02.png in any directory will contain U+0200 through U+02FF).

All of the files are PNGs, with a transparent background and a default character color of white (although emoji and other characters can be in color). This is to make them easily recolorable using a "multiply" operation.

## About versioning

This package will not be version 1.0 until everything I intend to be in a full release is at least in the 8x12 directory (which is where active development is happening). Until then, the minor version number is a very rough estimate of how far along the project is.

Currently included:
* 00 through 05 (Latin, IPA, Greek, Cyrillic, Armenian, Hebrew)
* 16 (last part of Canadian syllabics, Ogham, Runic)
* 1F (tone-marked Greek)
* 20 through 27 (punctuation, geometric shapes, Dingbats, and assorted symbols)
* 30 (CJK symbols and Japanese kana)
* 1F0 (game symbols)
* 1F3, 1F4, 1F5 (most of the emoji)

In progress:
* 2B (more miscellaneous symbols)
* 32, 33 (CJK enclosed symbols and compatibility glyphs)
* 1F6, 1F9 (the remaining emoji blocks)

Missing but planned for short-term inclusion:
* 1F1, 1F2 (enclosed characters)

Planned for inclusion before 1.0 release:
* 06, FB, FC, FD (Arabic and its presentation forms)
* 09 (Devanagari and Bengali)
* 14, 15 (remaining Canadian syllabics)
* 1D, 1E (extended phonetic and Latin stuff)
* 28 (Braille; this seems easy to automate)
* 29, 2A, 2E (more symbols)

Post-1.0 plans:
* 0A through 11 (more Asian/Indic blocks)
* 12 and 13 (Ethiopic and Cherokee)
* Some reasonable subset of IICore characters (for Chinese/Kanji)
  * Note: at these small pixel sizes, most characters will be illegible, so I will only implement characters that are distinctive and commonly used.
* Hangul syllables
* The proposed Legacy Computing block at 1FB, which is not yet actually in Unicode proper but is on the roadmap

2.0 and later:
* Everything else that can reasonably fit into an 8×12 block of pixels
