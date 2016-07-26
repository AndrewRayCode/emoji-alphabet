# Emoji Alphabet

A mapping from plain text characters to their pseudo-Emoji equivalents.

## Usage

You can look up alphabet characters (including punctuation):

```javascript
var alphabet = require('emoji-alphabet').alphabet;
var a = alphabet['A']; // Emoji "A" symbol
```

Or whole words (where available):

```javascript
var compounds = require('emoji-alphabet').compounds;
var cool = alphabet['COOL']; // Emoji "COOL" symbol
```

Where multiple Emojis are available, the result will be an array with the options listed from most popular to least popular.

## Alphabet

The alphabet looks something like this:

![Alphabet Emoji Screenshot](https://raw.githubusercontent.com/DelvarWorld/emoji-alphabet/master/alphabet-emoji.png)
