## Code 102
#### Day 3

**Design Web Pages with CSS**

**Chapter 10**

We use CSS to create rules that specify how the contents of an HTML element will appear. A helpful tip is to pretend there is a box around every element so you can visualize the area for styling. Use CSS in it's own file, if you type it inline people will not think you are cool. Different browsers, especially antiquated ones may display your styling differently. There are special websites that will show you how your website looks in a variety of browsers, should be noted.

CSS is written using a *selector* and one or more *declarations* composed of a *property* and a *value* which are sepparated using a *colon*.

#### SELECTOR `{PROPERTY: VALUE;}`

**Combining your HTML and CSS**

You can use the code `<link>` within the `<head>` tag to refer the browser to your css file. `<link>` is used in the following manner:

#### `<link href="filename.css" type="text/css" rel="stylesheet" />`

Some additional notes
- If there is more than one instance of a rule that applies to the same element the last rule will override the others.
- Unless **!important** is used which will cause it to override any others.
- Some things like *font styling* will be inherited. Other things like *border properties* will not be.
- You can also use the value **inherit** when it isn't automatic.

Beyond not wanting people to think you are a noob here are some other reasons to sepparate your style sheet from your html
- The css page can be shared by many pages or the whole site. 
- Makes your HTML clean and easier to read.
- Makes it easier to debug issues with cleaner separated code.

**Chapter 11**

Color can be specified for the foreground `<color>` and the background `<background-color>`. There are three traditional ways of denoting color
- RBG Values - rbg(val, val, val)
- Hex Code - #123456
- Color Names - ColorName (147 available)

CSS3 has also added two more ways to denote color but they are not recognized by older browsers. Hue, Saturation, Lightness, and Alpha are considered in this markup.
- HSL Colors - hsl(val, val%, val%)
- HSLA Colors - hsla(val, val%, val%, val) 

**Hue** is a way of refering to color

**Saturation** refers to the amount of gray in the color

**Brightness** refers to how much black is in the color

**Lightness** in contrast to brightness lightness contains white on one end of the spectrum and black on the other

**Contrast** refers to the difference between two colors, low contrast is hard to see, high contrast can wear on the eyes

**Opacity** introduced in css3, allows you to specify the opacity of an element and it's children








[Return to the Main Page](README.md)