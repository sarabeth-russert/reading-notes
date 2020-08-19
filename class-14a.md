## Code 201
#### Day 12 - 1

**CSS Articles and Demos**

[CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

CSS3 introduced the Transform property which gives us new ways to size, position, and change elements.
- has a 2d and 3d setting with their own properties
- transform is not yet widely supported by browsers there are prefixes you can use that help

`transform:`
- `:scale(num)`
- `:rotate(deg)`
- `:translate(px, %)`
- `:skew(xdeg, ydeg)`
- `:perspective(px)`

to combine transforms list them with no comma between

also
- `transform-origin: %/xpx ypx/top left`
- `perspective-origin: %/xpx ypx/top left`

[CSS Transitions and Animation](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

For transitions to take place an element must have a changing state like a pseudo-class - :hover, :active, :focus, :target.

4 transition properties
- `transition-property:` 
- `transition-duration: seconds/ms`
- `transition-timing-function: linear/ease-in/ease-out/ease-in-out`
- `transition-delay: seconds/ms`

Not all properties can be transitioned, only those that have a halfway point. Here are some commonly used properties for transitions:
- background-color
- background-position
- border-color
- border-width
- border-spacing
- bottom
- clip
- color
- crop
- font-size
- font-weight
- height
- left
- letter-spacing
- line-height
- margin
- max-height
- max-width
- min-height
- min-width
- opacity
- outline-color
- outline-offset
- outline-width
- padding
- right
- text-indent
- text-shadow
- top
- vertical-align
- visibility
- width
- word-spacing
- z-index

For animations use @keyframes and give the animation a name. We have the same properties as transition and also 
- `animation-iteration-count`
- `animation-direction`
- `animation-play-state`

[8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS](http://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

All on hover:
1. fade in
2. change color
3. grow/shrink
4. rotate
5. change border radius
6. 3d shadow effect
7. swing element
8. inset border

[6 Buttons Animated - DEMO](https://codepen.io/retyui/pen/ByoaXV)

[CSS3 Keyframes Animation - DEMO](https://codepen.io/akshaychauhan/pen/oAfae)

[404 Animation - DEMO](https://codepen.io/kieranfivestars/pen/MYdQxX)

[Pure CSS Bounce Animation - DEMO](https://codepen.io/dp_lewis/pen/gCfBv)

[Return to the Main Page](README.md)