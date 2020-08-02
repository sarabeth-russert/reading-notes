## Code 201
#### Prework

**Prework Reading Assignments**

HTML & CSS

[Chapter Reviews](structure_web_pages_html.md)

JAVASCRIPT

Chapter 1

Javascript makes web pages more interactive
- access content
- modify content
- program rules into your page (like a series of steps)
- react to events (like a button click)

Can make lots of content more dynamic
- slideshows
- forms
- reload only portions of the page to update
- filter data

*Script* A series of instructions. Comparable to recipes, handbooks, and manuals. A browser may use different parts of the script depending on the users interaction with the page. Can run different sections of code in response to conditions. When writing a script think like a computer with every step written out
- define the goal
- design the script (split it into steps)
- code each step

Javascript uses *objects* to represent things. An *instance* is an occurance of an object. Objects can have *properties*, *events*, and *methods*.
- Properties are characteristics of an object and are comprised of a name and a value.
- Events are things that can happen to trigger a response from the object.
- Methods act on the object to give information or change a value. Instructions that act on the object.

They work together when an event calls a method which retrieves or updates a property of the object.

Web Browsers are programs built using objects. The "document" object displays code from your html file. 

Javascript is an *interpreted programming language*. Each line of code is translated one by one as the script is run. 

How a browser sees a web page:

1. Recieves a page as HTML code
2. Creates a model of the page and stores it in memory
3. Uses a rendering engine to display the page

Javascript fits together with HTML and CSS. Each language goes in it's own file and forms a seperate layer with a different purpose for your page.

- HTML - content layer
- CSS - presentation layer
- JS - behavior layer

To create a basic javascript for your page:

- create a file with the extension .js and write a task for your page to perform. 
- use the `<script>` element in your HTML document where you would like the javascript to run.
- use the *src* attribute within the `<script></script>` element to direct the browser to your .js file.

Adding a javascript `<script>` to your HTML document will not display the .js code to your HTML source code. It will just show the .js file name. 




[Return to the Main Page](README.md)