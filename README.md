# strint – a JavaScript library for string-encoded integers

**Experimental code – beware**

This library lets you work with arbitrarily large integers, by storing them in strings. The focus has been on ease of understanding, not on performance. This library should still be useful for applications where performance isn’t critical, but you need to work with large integers.

The following operations are available:

* `lt(x, y)`: is x < y (“less than”)?
* `lte(x, y)`: is x ≤ y (“less or equal”)?
* `gt(x, y)`: is x > y (“greater than”)?
* `gte(x, y)`: is x ≥ y (“greater or equal”)?
* `eq(x, y)`: is x = y (“equals”)?
* `add(x, y)`
* `sub(x, y)`
* `mul(x, y)`
* `divmod(x, y)`
* `div(x, y)`
* `mod(x, y)`
* `abs(x)`
* `isNegative(x)`
* `isPositive(x)`
* `negate(x)`

Interaction:
    <script src="strint.js"></script>
    <script>
      console.log(StrInt.add("9007199254740992", "1"))
    </script>
    
    > '9007199254740993'

Compare:
    <script>
      console.log(9007199254740992 + 1)
    </script>
    
    > 9007199254740992
