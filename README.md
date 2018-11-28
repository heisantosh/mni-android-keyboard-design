# Virtual keyboard layout design for Meetei Mayek script for Manipuri language

The existing Gboard methods provide two ways to enter in Meetei Mayek script - direct and transliteration. This effort tries to improve the direct input method.

### Unicode charts of Meetei Mayek script

https://unicode.org/charts/PDF/UABC0.pdf

https://unicode.org/charts/PDF/UAAE0.pdf

Number of total characters in meitei mayek script:
* 56 standard characters
* 23 extension characters

56 standard characters:
* 27 mapi characters
* 8 lonsum characters
* 8 cheinap characters
* 3 khudam characters
* 10 cheising characters (10 digits)

## Issues with the existing layout in Gboard
* Some characters are missing - (apun), (onap), (nung), (lum)
* Standard and historical characters are mixed up

## New design

![Primary layout](https://raw.githubusercontent.com/heisantosh/mni-android-keyboard-design/master/primary_layout.png)

![Extensions layout](https://raw.githubusercontent.com/heisantosh/mni-android-keyboard-design/master/extensions_layout.png)

![Numbers layout](https://raw.githubusercontent.com/heisantosh/mni-android-keyboard-design/master/numbers_layout.png)

## Rationale of this design

This design includes all the standard characters. It also separates the standard and historical characters into separate views.

### Primary layout:
* The characters are placed in a similar way to how it's taught in school. This will make it easier to look for a character. 
* (ꯒ,ꯘ) (ꯕ,ꯚ) (ꯗ,ꯙ) (ꯏ,ꯢ) are grouped because of the similarity -

    |character|romanized|character|romanized|
    |--|--|--|--|
    |ꯒ|g|ꯘ|gh|
    |ꯕ|b|ꯚ|v or bh|
    |ꯗ|d|ꯙ|dh|
    ꯢ is the <em>lonsum</em> of ꯏ
* The <em>lonsum</em>s are in a separate row which makes it a little easier to find.
* All the <em>cheitap</em> characters are grouped together.

### Extension characters layout:
* The extension characters are historical and not usually used in print and media. So a separate view.
