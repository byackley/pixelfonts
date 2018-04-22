# pixelfonts

## What are these?

These are tiny monospaced pixel fonts in a variety of sizes. These top-level directories are all named after the pixel size of a single character, and the files within are named for the 256-character segment of Unicode they contain (so, for instance, 02.png in any directory will contain U+0200 through U+02FF).

All of the files are PNGs, with a transparent background and a default character color of white (although emoji and other characters can be in color). This is to make them easily recolorable using a "multiply" operation.

## About versioning

This package will not be version 1.0 until everything I intend to be in a full release is at least in the 8x12 directory (which is where active development is happening). Until then, the minor version number is a very rough estimate of how far along the project is.

Currently included:
* 00 through 05 (Latin, IPA, Greek, Cyrillic, Armenian, Hebrew)
* 20 through 26 (punctuation, geometric shapes, and assorted symbols)
* 1F0 (game symbols)
* 1F3, 1F4 (some of the emoji)

In progress:
* 30 (CJK symbols and Japanese kana)
* 1F5 (more emoji)

Missing but planned for short-term inclusion:
* 27 (Dingbats, miscellaneous math and arrows)
* 1F1, 1F2 (enclosed characters)
* 1F6, 1F9 (the remaining emoji blocks)

Planned for inclusion before 1.0 release:
* 06 (Arabic, but not until I learn more about monospaced Arabic rendering)
* 09 (Devanagari and Bengali)
* 14, 15, 16 (Canadian syllabics, plus Ogham and Runic)
* 28 (Braille; this seems easy to automate)
* 29, 2A, 2B (more symbols)

Post-1.0 plans:
* 0A through 11 (more Asian/Indic blocks)
* 12 and 13 (Ethiopic and Cherokee)
* Some reasonable subset of IICore characters (for Chinese/Kanji)
  * Note: at these small pixel sizes, most characters will be illegible, so I will only implement characters that are distinctive and commonly used.
* Hangul syllables
* The proposed Legacy Computing block at 1FB, which is not yet actually in Unicode proper but is on the roadmap

2.0 and later:
* Smaller sizes of more than just 8x12
