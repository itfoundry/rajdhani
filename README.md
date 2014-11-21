# Rajdhani

Rajdhani is an open source typeface supporting both the Devanagari and the Latin scripts. The font family was developed for use in headlines and other display-sized text on screen. Its initial release includes five fonts.

Each of these fonts contains 1,098 glyphs. The letterforms are modularised; their squared and condensed appearance may be interpreted as being technical or even futuristic. Typically round bowls and other letterform elements have straight sides in Rajdhani. Its stroke terminals typically end in flat line segments that terminate either on a horizontal or a vertical, rather than on a diagonal. Their corners are slightly rounded, giving stroke-endings a softer feeling, rather than a pointy one.

Satya Rajpurohit and Jyotish Sonowal developed the Devanagari component in the Rajdhani fonts together, while the Latin was designed by Shiva Nalleperumal. The Indian Type Foundry first published the family in 2014.

## Code base

This working directory is forked from the common code base, [ITF Base Devanagari (for Google Fonts)](https://github.com/itfoundry/base-devanagari-gf).

## Dependencies

- [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO), version 2.5 build 63209 (Sep 18 2014) or newer.
- A script [`UFOInstanceGenerator.py`](https://github.com/adobe-type-tools/python-scripts/blob/master/FDK%20Extras/UFOInstanceGenerator.py) (to be placed in AFDKO’s directory `FDK/Tools/osx`) and two [modules](https://github.com/adobe-type-tools/python-modules) (to be placed in Python’s `site-packages` directory) from Adobe.
