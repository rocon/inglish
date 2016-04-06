# Inglish

Phonetic English

Version: 0.1

Datetime: 2016-03-30T21:36:15Z

## Overview

Inglish is a way to spell English phonetically while at the same time keeping the current spelling conventions. It does this by adorning the 26 letters of the Latin alphabet with various punctuation symbols and formatting markup.

Inglish adheres to the following principles:
- Keep the current spelling conventions for English as its basis
- However, only use lowercase letters for dictionary words
- Do not spell names phonetically: keep uppercase letters
- Do not spell foreign words phonetically: keep vowels and consonants as-is
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with different punctuation, which symbolizes 1 distinct sound per punctuated character
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are not pronounced are formatted with italic markup
- Sounds that do not appear in the spelling of the word are shown as characters that are formatted with inserted markup
- The primary stress is shown with bold (strong) markup
- The aspirated unvoiced stop is shown as a Unicode character U+00B4 acute accent (&#x00B4;) appended to the 't', 'p', 'k' or 'q' character
- Syllables in a word are separated with a Unicode character U+00B7 middle dot (&#x00B7;) in between

## Charts

### Vowels

#### Closed
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|bad|b<ins>&#x00E0;</ins>d||
|e|bed|b<ins>&#x00E8;</ins>d||
|i|did|d<ins>&#x00EC;</ins>d||
|o|nod|n<ins>&#x00F2;</ins>d||
|u|bud|b<ins>&#x00F9;</ins>d||
|y|hymn|h<ins>&#x1EF3;</ins>m<sub><sup>n</sup></sub>||

#### Open
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|ate|<ins>&#x00E1;</ins>t<sub><sup>e</sup></sub>||
|e|me|m<ins>&#x00E9;</ins>||
|i|hi|h<ins>&#x00ED;</ins>||
|o|no|n<ins>&#x00F3;</ins>||
|u|sue|s<ins>&#x00FA;</ins><suins><sub><sup>e</sup></sub>||
|y|why|w<sub><sup>h</sup></sub></suins><ins>&#x00FD;</ins>||

### Consonants

#### Basic
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|b|bad|b<ins>&#x00E0;</ins>d||
|c|arc|<ins>&#x00E2;</ins>rc||
|d|did|d<ins>&#x00EC;</ins>d||
|f|far|f<ins>&#x00E2;</ins>r||
|g|gun|g<ins>&#x00F9;</ins>n||
|h|hi|h<ins>&#x00ED;</ins>||
|j|jar|j<ins>&#x00E2;</ins>r||
|k|skin|sk<ins>&#x00EC;</ins>n||
|l|lid|l<ins>&#x00EC;</ins>d||
|m|me|m<ins>&#x00E9;</ins>||
|n|no|n<ins>&#x00F3;</ins>||
|p|spin|sp<ins>&#x00EC;</ins>n||
|q|quiz|q&#x016B;<ins>&#x00EC;</ins>z||
|r|rod|r<ins>&#x00F2;</ins>d||
|s|sue|s<ins>&#x00FA;</ins><sub><sup>e</sup></sub>||
|t|stop|st<ins>&#x00F2;</ins>p||
|v|vet|v<ins>&#x00E8;</ins>t||
|w|why|w<suins><sub><sup>h</sup></sub><ins>&#x00FD;</ins>||
|x|six|s<ins>&#x00EC;</ins>x||
|y|yes|y<ins>&#x00E8;</ins>s||
|z|zip|z<ins>&#x00EC;</ins>p||

#### Aspirated voiceless stops
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|c|can|&#x010B;<ins>&#x00E0;</ins>n||
|k|keep|&#x1E33;<ins>&#x00E9;</ins><sub><sup>e</sup></sub>p||
|p|pan|&#x1E57;<ins>&#x00E0;</ins>n||
|t|top|&#x1E6D;<ins>&#x00F2;</ins>p||

#### Other fricatives
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|ch|chip|&#x0109;<sub><sup>h</sup></sub></suins><ins>&#x00EC;</ins>p||
|ch|loch|l<ins>&#x00F2;</ins><sub><sup>c</sup></sub></suins>&#x0125;||
|g|gel|&#x011D;<ins>&#x00E8;</ins>l||
|gh|rough|r<sub><sup>o</sup></sub><ins>&#x00F9;</ins>&#x01F5;<sub><sup>h</sup></sub>||
|j|raj|r<ins>&#x00E3;</ins>&#x0135;||
|ph|phone|&#x1E55;<sub><sup>h</sup></sub><ins>&#x00F3;</ins>n<sub><sup>e</sup></sub>||
|s|measure|m<ins><b>&#x00E8;</b></ins><sub><sup>a</sup></sub>&#x00B7;&#x0161;<ins>&#x016D;</ins>r<sub><sup>e</sup></sub>||
|sh|ship|&#x015D;<sub><sup>h</sup></sub><ins>&#x00EC;</ins>p||
|z|azure|<ins><b>&#x00E0;</b></ins>&#x00B7;&#x017E;<ins>&#x016D;</ins>r<sub><sup>e</sup></sub>||
