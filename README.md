# javascript
learning JS All Notes outside block codes stay here.

Fundamentals:

// single line comment
/*
multiple lines comment
*/

alert("some code");
// "use strict" below is ignored--it must be at the top

"use strict"; Flags JS works "modern" way. "use strict"

// strict mode is not activated

There’s no way to cancel use strict

There is no directive like "no use strict" that reverts the engine to old behavior.

Once we enter strict mode, there’s no going back.

Data Types Summary:
Summary

There are 8 basic data types in JavaScript.

    * number for numbers of any kind: integer or floating-point, integers are limited by ±(253-1).
    * bigint is for integer numbers of arbitrary length.
    * string for strings. A string may have zero or more characters, there’s no separate single-character type.
    * boolean for true/false.
    * null for unknown values – a standalone type that has a single value null.
    * undefined for unassigned values – a standalone type that has a single value undefined.
    * object for more complex data structures.
    * symbol for unique identifiers.

The typeof operator allows us to see which type is stored in a variable.

    * Two forms: typeof x or typeof(x).
    * Returns a string with the name of the type, like "string".
    * For null returns "object" – this is an error in the language, it’s not actually an object.
