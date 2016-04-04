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
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with different punctuation, which symbolizes 1 distinct sound per punctuated character
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are not pronounced are formatted with del markup
- Sounds that do not appear in the spelling of the word are shown as characters that are formatted with inserted markup
- For words that have at least two syllables the primary stress is shown with bold (strong) markup
- For words with more than two syllables the secondary stress is shown with italic (emphasized) markup
- The aspirated unvoiced stop is shown as a Unicode character U+00B4 acute accent (&#x00B4;) appended to the 't', 'p' or 'k' character
- The glottal stop is shown as Unicode character U+00B7 middle dot (&#x00B7;)

## Charts

### Closed vowels
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|bad|b&#x00E0;d||
|e|bed|b&#x00E8;d||
|i|did|d&#x00EC;d||
|o|nod|n&#x00F2;d||
|u|bud|b&#x00F9;d||
|u|hymn|h&#x1EF3;m<i>n</i>||

### Open vowels
|English|Inglish|IPA|
|:-----:|:-----:|:-:|
|<b>a</b>te|<b>&#x00E1;</b>t<i>e</i>||
|m<b>e</b>|m<b>&#x00E9;</b>||
|h<b>i</b>|h<b>&#x00ED;</b>||
|n<b>o</b>|n<b>&#x00F3;</b>||
|s<b>u</b>e|s<b>&#x00FA;</b><i>e</i>||
|wh<b>y</b>|w<i>h</i><b>&#x00FD;</b>||

### Basic consonants
|English|Inglish|IPA|
|:-----:|:-----:|:-:|
|b<b>a</b>d|b<b>&#x00E0;</b>d||
|c<b>a</b>n|c<b>&#x00E0;</b>n||
|did|d&#x00EC;d||
|nod|n&#x00F2;d||
|bud|b&#x00F9;d||
|hymn|h&#x1EF3;m<i>n</i>||
