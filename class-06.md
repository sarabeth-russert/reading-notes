## Code 201
#### Day 6

**Article Notes**

*Understanding the Problem Domain is the hardest part of programming*

Understanding what the problem is before you try to solve it saves time and effort.

Break complicated problems down into pieces to make them easier to solve.

**Javascript Reading**

Chapter 3 - Object Literals

An *Object* groups together a set of variables and functions to create a model of something you would recognize from the real world. 

In objects:
- variables are called "properties"
- functions are called "methods"
- names of variables are called "keys"

Literal notation to create and object:

`var newObject = {`

` key1 = value1,`

` key2 = value2,`

` methodForNewObject: function () {`

` return or do something`

` }`

`}`

To access properties or methods use dot notation or square brackets. 

`newObject.key1;`

`newObject['key1'];`

Chapter 5 - Document Object Models

- DOM - Document Object Model, specifies how the browsers should create an HTML page and how JS can access and update the contents of a web page while it is in the browser window.

- API - Application Programming Interface, lets programs and scripts talk to each other.

- DOM Tree - a model of the web page that is loaded and stored in the browsers memory.

There are 4 types of *nodes* on a DOM tree:
- Document
- Element
- Attribute - part of the element node, not a child
- Text - always the end of a branch, no further branch can come from a text node

Methods that find elements in the DOM tree are called *DOM Queries*

To select and individual element node:
- `getElementByID()` 
- `querySelector()`

To select multiple element nodes:
- `getElementsByClassName()`
- `getElementsByTag()`
- `querySelectorAll()`

Traversing between element nodes:
- `parentNode`
- `previousSibling / nextSibling`
- `firstChild / lastChild`

`nodeValue` property allows you to access or update contents of a text box.

Several methods allow you to create, add, or remove nodes from a tree, called DOM manipulation:
- `createElement()`
- `createTextNode()`
- `appendChild() / removeChild()`

To access or update attribute values use the id or class name:
- `hasAttribute()`
- `getAttribute()`
- `setAttribute()`
- `removeAttribute()`

Store elements you will need to access more than once in a variable, this is called *caching* the selections. You are storing a reference to the object, its location, not the actual object.

If a method can return more than one node it will always return a *node list* which is a *collection* of nodes and acts like and array, accessable by index number or by the `item()` method.

`getElementsBy...()` methods return live node lists, which update as elements change.

`querySelector...()` methods return static node lists, which do not change.

You should always aim to fint the fasted route to access and element as it is more efficient for the computer.


[Return to the Main Page](README.md)