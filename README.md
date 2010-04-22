# JSON library

## Information

A light-weight, ECMAScript 5 compliant library for serializing data to JSON and
back.

Nothing will be done if a `JSON` object is already defined (for example, if a
browser has native support for JSON). Note that some libraries define a global
`JSON` object, but do not adhere to the ECMAScript 5 standard and use other
method names than `parse` and `stringify`. To avoid this, simply do not use
that library and this library together.

## Example

    var json = JSON.stringify({abc: 123, def: "ghi", jkl: [4, 5, 6]});
    // Same result as:
    var json = '{"abc":123,"def":"ghi","jkl":[4,5,6]}';

## MIT license

This project is licensed under an MIT license.  
<http://www.opensource.org/licenses/mit-license.php>

Copyright (c) 2009-2010 Andreas Blixt <andreas@blixt.org>
