## Code 201
#### Day 6

**Article Notes - Domain Modeling**

> "The process of creating a conceptual model for a specific problem"

Constructors can be created using a function expression that takes in parameters representing the properties of the object. Use a constructor to define multiple objects with the same properties. 

To define a new object via constructor:

`let newObj = new constructorFunction(value1, value2);`

- Key word *new* instantiates or creates a new instance of an object
- The constructor function initializes properties inside the object using the contextual *this*
- The object is stored in a variable for later use

Methods can be added to a constructor functions prototype:

`constructorFunction.prototype.newMethod function(){}`

The program will look for a method in the object and when it doesn't find it will look in the constructors prototype.

**HTML - Ch 6 "Tables" pg.126-145**

When representing information in a table think of a grid or spreadsheet.
- `<table></table>` creates the table element
- `<tr></tr>` indicates the start of each row
- `<td></td>` represents each cell of the table, `<td>` goes within `<tr>`
- `<th></th>` table heading
- `<colspan="number">` stretches a cell across more than one column
- `<rowspan="number">` stretches a cell over more than one row
- `<thead></thead>` header for table
- `<tbody></tbody>` body of table
- `<tfoot></tfoot>` footer of table

**JS - Ch 3 “Functions, Methods, and Objects” pg.106-144**

To add  or delete properties to an object after it is created use dot notation
- `objectName.newKey = value;`
- `delete objectName.oldKey;`

There are several kinds of built in objects that we will interact with.

[DOM](class-06.md)

Browser Object Model - Window
  - document
  - history
  - location
  - navigation
  - string

Global Javascript Objects 
- string
- number
- boolean
- date
- Math
- regex

Object Model Window
- Properties
  - `window.innerHeight`
  - `window.innerWidth`
  - `window.pageXOffset`
  - `window.pageYOffset`
  - `window.screenX`
  - `window.screenY`
  - `window.location`
  - `window.document`
  - `window.history`
  - `window.history.length`
  - `window.screen`
- Methods
  - `window.alert()`
  - `window.open()`
  - `window.print()`

The Document Object
- Properties
  - `document.title`
  - `document.lastModified`
  - `document.URL`
  - `document.domain`
- Methods
  - `document.getElementbyID()`
  - `document.querySelector()`
  - `document.createElement()`
  - `document.createTextNode()`

Global Objects - String
- Properties
  - `.length`
- Methods
  - `.toUpperCase()`
  - `.toLowerCase()`
  - `.charAt(position)`
  - `.indexOf(string)`
  - `.lastIndexOf(string)`
  - `.substring(1stIndexIncl, lastIndexExcl)`
  - `.split('split at char')` - returns array
  - `.trim()`
  - `.replace('this', 'that')`

Global Objects - Number
- Methods
  - `.isNaN()`
  - `.toFixed()`
  - `.toPrecision()`
  - `.toExponential()`

Global Objects - Math
- Properties
  - `Math.PI`
- Methods
  - `Math.round()`
  - `Math.sqrt(n)`
  - `Math.ceil()`
  - `Math.floor()`
  - `Math.random()`

Global Objects - Date
- Methods
  - `.getDate() .setDate()`
  - `.getDay() `
  - `.getFullYear() .setFullYear()`
  - `.getHours() .setHours()`
  - `.getMinutes() setMinutes()`
  - `.getMonths() .setMinutes()`
  - `.getSeconds() .setSeconds()`
  - `.getTime() .setTime()`
  - `.toDateString()`
  - `.toTimeString()`

[Return to the Main Page](README.md)