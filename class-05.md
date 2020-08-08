## Code 201
#### Day 4 and 5

**HTML & CSS Reading**

Chapter 5 Images

The right image should:
- be relevant
- convey information
- convey a mood
- be recognizable
- fit the color palette

To insert images us:
- `<img>` empty tag
- `src` attribute tells the browser where to find the image
- `alt` attribute provides a text description of the image
- `title` provides additional information about the image

Three rules for creating images
1. Save in the right format .jpeg, .gif, .png
2. Save at the right size, Lena says a little larger than the size of the box (10%?)
3. Measure in percentages to scale to the screen or ems/pixels for fixed height/width

Use *GIF* or *PNG* when saving images with few colors or large blocks of the same color. Use JPEG when saving an image with a greater variety of colors.

Other notes
- vector images are resolution independent and can be made for plain graphics or logos
- animated gifs take up memory and should be simple
- `<figure><figcaption></figcaption></figure>` can be used to hold images and image captions

[Chapter 11](design_web_pages_css.md)

Chapter 12 Text

Typeface Terminology
- Serif - fonts with serifs
- San Serif - fonts with no serifs
- Monospace - fonts where all the letters are the same width

- Weight - light, medium, bold, black
- Style - normal, italic, oblique
- Stretch - condensed, regular, extended

- Ascender - above the Cap Height
- Cap Height - top of flat letters
- Baseline - line the letters sit on
- Descender - below the baseline

Use `font-family:` to specify typefaces. Types are grouped together, good to specify a generic backup that will work if the user doesn't have the font you want. 

Use `font-size:` to specify size... pixels, percentages, or ems. Refer to the text for a sizing chart.

@font-face allows you to use a font even if the user doesn't have it on their computer. Must include the path of the font and the font will be downloaded if the user doesn't have it. The font must be licensed to permit the download.

Some font styling can be specified in html like Bold, Italic, Underline, Strikethrough, etc.

[Return to the Main Page](README.md)