# REGULAR-EXPRESSION-RegExp

Regular expressions (Regex) are patterns to help search for matching data strings, addresses or passwords 

The Regex character sequences defines the characteristics to match a character sequence within another string.

A RegExp object is used to match pattern it also contains flags to change how matches are performed.

##### Syntax
2 methods create a RegExp object.

    // Using literal notation
        let re1 = /foo?/i;

    // Using RegExp constructor - compiled at runtime
        let re2 = new RegExp('foo?', 'i');

    // Both create a RegExp object with a pattern = "foo?" and a flag = "i"

Literal notation compiles when the expression is evaluated. Best used when the pattern will remain constant.

Object constructor compiles at runtime. Best used when the RegExp object changes, or the pattern is obtained during runtime.


|***RegExp*** | ***PROPERTIES***|
|:---:|:---:|
|Property |	Description|
|.flags |	Returns a string containing the flags of the RegExp object.|



