### UTF-8

Earlier days computer has to display only a small set of characters, around 128 and most of us familiar with characters in form of ASCII.

For the characters other than ASCII we needed encoding scheme that accomodates that more that 128 characters.
Thus we have Unicode(not a encoding) and UTF-8.

The 8 in the UTF-8 represents the numbers are represented in 8-bit blocks. The number of blocks can be about 1 or 2 or upto 4.
it shares some similar features with ASCII. It supports null terminated strings.

# what is unicode

Unicode is character encoding scheme. it basically provides a unique number for every character for almost every language and symbols.

Before Unicode was invented, there were hundreds of different systems, called character encodings, for assigning these numbers. These early character encodings were limited and could not contain enough characters to cover all the world's languages. Even for a single language like English no single encoding was adequate for all the letters, punctuation, and technical symbols in common use.
Also there is conflicts like a same character has different number in two encoding schemes. This was a pain, when the world is connected with internet, like an email from Europe or Asia, will be visible as corrupted to a in North America.

FAQs.

**Does all the characters in the unicode can be represented in UTF-8?**

Yes, UTF-8 supports any unicode character. 

**What are the languages/symbols covered by Unicode ?**

Checkout the list for supported scripts and symbols here http://www.unicode.org/charts/index.html

**Source**
https://www.fileformat.info/info/unicode/utf8.htm
http://www.unicode.org/standard/WhatIsUnicode.html

