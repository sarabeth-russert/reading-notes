## Code 201
#### Day 1

**HTML & CSS Reading**

Chapter 2

Text

Structural Markup: the elements you use to describe both headings and paragraphs
- Headings `<h1> through <h6>`
- Paragraphs `<p></p>`
- Bold `<b></b>`
- Superscript `<sup></sup>`
- Subscript `<sub></sub>`
- Inline Line Break `<br />`
- Horizontal Rules `<hr />`

Semantic Markup: provides extra information such as where emphasis is placed in a sentence, quotations, etc.
- `<strong></strong>` contents with strong importance
- `<em></em>` indicates emphasis, default display is italic
- `<blockquote></blockquote>` used to quote out text in a block format
- `<q></q>` quotes out text inline
- `<abbr></abbr>` shows long form of acronym when you hoover over
- `<cite></cite>` to indicate citation from a book or other work
- `<dfn></dfn>` defining instance of a new term
- `<address></address>` contact details for the author
- `<ins></ins>` content inserted (default underline)
- `<del></del>` content deleted (default strikethrough)
- `<s></s>` something no longer accurate but not removed (default strikethrough)


[Chapter 10](design_web_pages_css.md)


**Javascript Reading**

Chapter 2

Javascript is case sensitive and made up of statements. Each statement starts on a new line and is ended by a semicolon. A code block is started and ended by curly braces.

*Script* is a series of instruction that a computer can follow one by one.

To comment out code for notes or to prevent it from being run you can use `//` for a single line of comment or wrap a larger block to be commented out using `/* commented out code */`

A *variable* is a container used to hold a value we need to remember. Variables must be declared using a keyword *var*, *let*, or *const* and given a name or *identifier*. Javascript uses camelCase to name variables. We use the assignment operator `=` to give a value to the variable. Prior to assignment the variable will be *undefined*. You can change the value of a variable by simply assigning a new value. 

An *array* is a special type of variable that stores a list of values. Arrays are assigned using `[value1, value2, value3]` syntax. Array items can be accessed using arrayName[index#] starting with an index 0. 

*Expressions* evalute into a single value. Some assign a value to a variable, and some perform an opperation to result in a sinlge value.

*Operators* allow programers to create a single value from one or more values using 
- assignment
- arithmetic
- string
- comparison
- logical (and/or)

*Arithmetic* follows pedmas + - / * ++ -- %

*Strings* concatenation, if uou try to use arithmetic operators on strings the retun is NaN

*Function* lets you group a series of instructions together to perform a specific task. "Calling" a function refers to asking it to run it's series of instructions. Some functions require *parameters* refered to as *arguments*. *return value* refers to any information a function passes out. To use the return value, assign your function call to a variable.

> Declare a Function 

> `function functionName(parameters) {block of code;}`

>Call a Function

>`functionName(argument);`

[Chapter 4](operators_and_loops.md)


[Return to the Main Page](README.md)