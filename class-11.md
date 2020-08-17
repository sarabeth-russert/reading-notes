## Code 201
#### Weekend 8/15

**HTML Reading Ch 16 - Images**

Control image size using the height and width properties, in px.

Image alignment can be adjusted using:
- for center
  - `display: block;`
  - `margin-left/right: auto;`
- or
  - `display: block;`
  - (on container) `text-align: center;`

- for left/right
  - `float: left/right;`

To control background images:
- `background-image: url(file path);` will repeat by default

To control repeat
- `background-repeat: repeat-x/repeat-y/no-repeat;`
- `background-attachment: fixed/scroll`

If the image is not repeated you can specify where you want it to sit on the screen using background-position
- `background-position: left/right/center-top/bottom/center;`

Shorthand for assigning background properties:
- `background: colorValue imageValue repeatValue attachmentValue positionValue`

Rollover and Sprites
- `:hover`
- `:active`
- and modify background position for each event

Gradients are available in CSS3 but not in all browsers.

Use low contrast background images or a screen to make text more readable.

**Chapter 19 - Practical Information**

Search Engine Optimization, SEO, helps your site to come up closer to the top of search engine results. It is basically determined by figuring out what terms people will use to find a site like yours and putting them in the right places on your page. Also having lots of other sites link to your page.

Place key search terms on your page in the following areas to help with SEO:
- page title (in head)
- URL, web address
- headings, `<h#>` elements
- body text
- link text, between `<a></a>` tags
- image alt text
- page descriptions (meta in head)

To identify and utilize key search terms and phrases
1. make a list of words that describe your page
2. group the words into seperate lists for the different sections or catagories of your page
3. explore keyword search sites for additional words to add or ormit
4. compare the popularity and competition for your targeted keywords
5. refine your list to your most relevant and your best search options
6. map out where on your site you want to put your chosen key words

Use an analytics tool like google analytics to track your visitor metrics, like what they look at and where they were referred from. 


Things to consider when choosing a host
- disk space
- bandwidth
- backups
- email accounts
- server side languages & databases

FTP - to transfer your files to your hosts web server

**Video and Audio API's article**

HTML5 added `<video>` and `<audio>` elements. The `controls` attribute places the default set of playback controls on the media pane. If you leave off `controls` it will hide the native controls and you can program your own with html, css, and JS. The htmlMediaElementAPI allows you to customize your own tool bar.

[review the article to implement a custom control bar](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)


[Return to the Main Page](README.md)