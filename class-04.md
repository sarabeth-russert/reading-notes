## Code 201
#### Day 3

**HTML & CSS Reading**

Chapter 4 

- URL: Uniform Resource Locator

Create links using the `<a></a>` element. Specify the location of the link by using the attribute `href`.
- Links to other sites: use full web address
- Other pages on the same site: relative URL
- Email links: mailto:address.com
- Opening links into a new window: add attribute `target="_blank"`
- Links to a specific part of the same page: give the area an id attribute and href="#id"

Chapter 15

Layout

Each HTML element is treated as it's own box, either inline or block-level. A *containing* or *parent* element is the box that another box sits within. `<div>` is a good example of a containing element.

Positioning Schemes
- `position: static;`
- `position: relative;`
- `position: absolute;`
- `position: fixed;`
- `float: right/left;`
- `z-index:`

Other considerations are screen size and resolution. A lot of designers try to create pages 960-1000 pixels in width to fit the majority of screens. 
- fixed width layouts: do not change based on window size
- liquid layouts: stretch and contract to fit the window

The book gives examples for grids as reference.

**Javascript Reading**

Chapter 3

*Function* lets you group a series of instructions together to perform a specific task. "Calling" a function refers to asking it to run it's series of instructions. Some functions require *parameters* refered to as *arguments*. *return value* refers to any information a function passes out. To use the return value, assign your function call to a variable. Functions can only return a single variable, you can get around this by returning an array.

> Declare a Function 

> `function functionName(parameters) {block of code;}`

>Call a Function

>`functionName(argument);`

*Named functions* are functions that are given a name when declared to use by name later in your code. 

*Anonymous functions* are declared by assigning them to a variable and not by declaring them with a name. 

*Immediately invoked function expressions* or IIFE are unnamed and executed when the interpreter comes to them. The function is not stored for later use.

Anonymous functions and IIFE are frequently used for code that only needs to run once within a task.
- As an argument when a function is called
- To assign the value of a property to an object
- In event handlers and listeners
- To prevent conflicts between two scripts that might use the same variable names.

*Scope* determines the range of effect a variable can have. You can only effect a variable within the scope you are working. *Local Variables* are created inside a function and they stay within the function. *Global Variables* are created outside of a function. You can access them within the function but whatever you do to them in the function does not affect them outside of the function.

**Article Notes: 6 Reasons for Pair Programming**

*Pair Programming* is when two developers work together with one acting as the *driver* and one as the *navigator* to complete a project. Benefits are:
1. Greater efficiency due to less mistakes
2. Engaged collaboration
3. Learning from your fellow student
4. Building social skills
5. Job interview readiness
6. Work environment readiness





[Return to the Main Page](README.md)