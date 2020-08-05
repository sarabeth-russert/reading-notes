## Code 201
#### Day 1

**HTML & CSS Reading**

Chapter 3 "Lists"

*Ordered Lists*
- numbered
- `<ol></ol>`

*Unordered Lists*
- bullet points 
- `<ul></ul>`

*Definition Lists*
- like a glossary, terms with definitions
- `<dl> creates list element </dl>`
- `<dt> definition term </dt>`
- `<dd> contains definition content </dd>`

Note that lists can be nested.

Chapter 13 "Boxes"

The default size for boxes is just large enough to hold the contents. This can be overridden using height: or width:, min-width: or max-width:, min-height: or max-height. Size can be denoted using pixels, percentages, or em. Using min/max can help ensure legibility on diverse screen sizes.
If your screen is too small overflow: hidden or :scroll can be used to control where the excess content is displayed.

- `border:` seperates the edge of one box from another
- `margin:` sits outside of the border
- `padding:` is the space between the border of the box and any content within

These properties create "white space" and "vertical margin".

`border:` has many style options which can be modified in whole or with each individual side of the border, by specifying `-top`, `-right`, `-bottom`, `-left`. Or all individually under one property moving in a clockwise direction starting with top.
- `-width`
- `-style`
- `-color`

`padding:` and `margin:` also allow each individual side to be changed independently.

To center a box use `margin: value, auto, value, auto` to center text within a box use `text-align: center`.

Here are some more helpful CSS properties
- `display: inline :block :inline-block :none` allows you to turn an inline element into a block or the reverse. Also allows you to hide an element and it will only be seen by view source
- `visibility: hidden : visible` allows you to hide a box but it will leave a blank space
- `border-radius:` allows you to round corners even making circles and elipses
- `border-image:` applies an image to the border of a box
- `box-shadow:` allows you to add a drop shadow to a box


**Javascript Reading**

[Chapter 2 review](class-02.md)

Chapter 4 (page 162 - 182)

*if/else* statements evaluate a condition and execute code when the condition is true.

*switch* statement is similar in that it executes code when a condition is met but it is formated differently and best used in specific circumstances when only one of an assortment of conditions will be true.

*type coercion* means that JS will try to make things work, it will convert a string to a number if necesarry to evaluate true. Data type does not need to be specified when declaring a variable and type can be changed, different types can even share an array, because of this JS is said to use *weak typing*.

Using strict operators like `===` and `!==` ensure data types match and give a more predictable result to comparison statements.

Every value in JS can be treated as *true* or *false*

Falsey Values
- false
- 0
- ' ' (an empty string)
- NaN
- no assignment to a declared value

Truthy Values
- true
- 1 (or any number other than 0)
- 'strings with content'
- 10/5 (number calculations)
- 'true' as a string
- 'false' as a string
- '0' as a string

*Short Circuit Evaluation* once one part makes the statement proves validity the evaluation stops.

*Loops* check a statement to see if a condition is true. If it is true, something happens, and the condition is checked again. This repeats until the condition is no longer true.

For Loops run a specific number of times at which the condition becomes false. Where `i` is the variable assigned to the counter and the count stops at `< 10` since JS is a zero indexed language count generally starts at 0.

> `for (let i = 0; 0 < 10; i++)`

While Loops have no set count but also evaluate a condition for truth, the condition can change due to user input, environmental change, or you can put a counter on it.

> `while (i > 10) {do something;}`


[Return to the Main Page](README.md)