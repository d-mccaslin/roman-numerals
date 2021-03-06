# _Roman Numerals}_

#### _Application that converts numbers into roman numerals, 8/20/20_

#### By _**David McCaslin and Brian Harvey**_

## Description

_this app utilizes javascript functionality to convert user inputted numbers into roman numerals. Input will be analyzed with loops and various array methods to output new elements and/or arrays._

## Setup/Installation Requirements

* _Retrieve from GitHub_
* _open index.html in browser._

## Specs

* The program will convert numbers into Roman Numerals, returning a string representing the converted number
* (Rule 1) The value of all symbols will be added
* (Rule 2a) Roman numeral cannot contain more than three of the same characters in a row
* (Rule 2b) Roman numeral symbols must be in descending order in terms of value. If a lower value symbol is placed left of a higher value symbol, the left symbol will be subtracted from the right symbol
* (Rule 3) Numbers will be broken into thousands, hundreds, tens, and ones and then converted and placed together

## Tests

Describe: convertToRomanNumeral()
Test: "The value of symbols will be added in the converted form"
Expect: convertToRomanNumeral(2).toEqual("II");

Test: "Converted numerals cannot contain the same letter more than three times in a row"
Expect: convertToRomanNumeral(8).toEqual("VIII");
Expect: convertToRomanNumeral(9).toEqual("IX");

Test: "A symbol appearing after a larger value symbol will be added to that symbol"
Expect: convertToRomanNumeral(6).toEqual("VI");

Test: "A symbol appearing before a larger value symbol will be subtracted from that symbol"
Expect: convertToRomanNumeral(90).toEqual("XC");

Test: "Converted numerals will be broken into thousands, hundreds, tens, and ones and added together"
Expect: convertToRomanNumeral(990).toEqual("CMXC");

## Known Bugs

_No known bugs_

## Support and contact details

_For any questions or feedback feel free to reach to [Brian](mailto:brian.harv3y@gmail.com) or [David](mailto:davidmccaslin94@gmail.com)._

## Technologies Used

_HTML_
_CSS_
_Javascript_
_Bootstrap_
_JQuery_

### License

*This app operates under the GPL license*

Copyright (c) 2016 **_David McCaslin and Brian Harvey_**