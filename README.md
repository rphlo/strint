# strInt – a JavaScript library for string-encoded integers

This library lets you work with arbitrarily large integers, by storing them in strings. The focus has been on ease of understanding, not on performance. This library should still be useful for applications where performance isn’t critical, but you need to work with large integers.

Forked to work in the browser.

The following operations are available:

* `lt(x, y)`: is x < y (“less than”)?
* `lte(x, y)`: is x ≤ y (“less or equal”)?
* `gt(x, y)`: is x > y (“greater than”)?
* `gte(x, y)`: is x ≥ y (“greater or equal”)?
* `eq(x, y)`: is x = y (“equals”)?
* `add(x, y)`
* `sub(x, y)`
* `mul(x, y)`
* `divMod(x, y)`
* `div(x, y)`
* `mod(x, y)`
* `abs(x)`
* `negate(x)`
* `isNegative(x)`
* `isPositive(x)`
* `isOdd(x)`
* `isEven(x)`

Interaction:

    console.log(strInt.add("9007199254740992", "1"))
    > '9007199254740993'

Compare:

    console.log(9007199254740992 + 1)
    > 9007199254740992
