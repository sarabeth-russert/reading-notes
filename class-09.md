## Code 201
#### Day 8

**HTML Ch 7 - Forms**

Form Controls
- Adding Text
  - single line `<input type="text" name="" maxlength="" />`
  - password `<input type="password" name="" size/maxlength="" />`
  - story box `<textarea name="" size=""></textarea>`
- Choice Fields
  - radio `<input type="radio" name="" value="" checked="" />`
  - checkboxes `<input type="checkbox" name="" value="" checked="" />`
  - dropdown `<select size="" multiple="" />`
- Submitting
  - submitting a file `<input type="file" />`
  - submit `<input type="submit" name="" value="" />`
  - submit image-button `<input type="image" />`
- Added with HTML5
  - form validation: add `required="required"` to input element
  - date `<input type="date" />`
  - email `<input type="email" />`
  - url `<input type="url" />`
  - search `<input type="search" />`
  - placeholder `<input placeholder="image" />`


Others
- buttons `<button>`
- to send form data to a page `<form><action><get><repost>`
- accessability `<label> for`
- to group form controls `<fieldset>`
- captions the purpose of the form `<legend>`

**HTML Ch 14 - Lists, Tables, Forms**

Bullet Point Styles
- `list-style-type:`
  - UL `: none, disc, circle, square`
  - OL `: decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman`

Positioning the Marker
  - `list-style-position`
    - `: outside`
    - `: inside`

List Shorthand
- `list-style` allows condensed styling

Table Properties
- `width`
- `padding`
- `text-transform`
- `letter-spacing font-size`
- `border-top border-bottom`
- `text-align`
- `background-color`
- `:hover`

Table Tips
- give cells padding
- distinguish headings
- shade alternate rows
- align numerals

`empty-cells: show/hide`
`border-spacing:` takes spacing values
`border-collapse: sepperate/collapse` 

**JS Ch 6 - Events**

Events
1. interactions create events
2. events trigger code
3. code responds to users

There are a ton of event types for UI, Keyboard, Mouse, Focus, Form, Mutation... will have to refer to the book for reference

How events reactions work:
1. select the element node you want the script to respond to
2. indicate which event will trigger the response
3. state the code you want to run when the event occurs

Event Listeners
- `elementName.addEventListener('event', functionName, boolean)`

The boolean is to manage *event flow* which is important when your code has event handlers on an element AND one of it's ancestors or decendants.

The Event Object
- Properties
  - `event.target`
  - `event.type`
  - `event.cancelable`
- Methods
  - `event.preventDefault()`
  - `event.stopPropagation()`

Event Delegation
- place event handlers on containing elements and use the event objects `.target` to find which of it's children the event is happening on


[Return to the Main Page](README.md)