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
|***RegExp***| ***METHODS***|
|Method|	Description|
|.exec(str)|	Execute a search on its str string parameter|

|***RegExp***| ***FLAGS***|
|:---:|:---:|
| | Flags change the default match behavior of the RegExp object|
|Flag|	Description|
|g|	Performs a global match, finding all matches rather than just the first.|
|i|	Makes matches case-insensitive. Matches both uppercase and lowercase.|
|m|	Performs multiline matches. (Changes behavior of ^,$)|
|s|	Allows . to match newline characters.|
|u|	Enables Unicode support.|
|y|Matches are sticky, looking only at exact position in the text.|

##### USAGE

    let re1 = /foo?/gim;
    let re2 = new RegExp('foo?', 'gim');

    // Create a RegExp object that performs a global, case-insensitive, multiline search









