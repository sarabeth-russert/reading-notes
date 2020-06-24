## Code 102
#### Day 2

**Structuring Web Pages with HTML**

We read three chapters of our textbook [HTML & CSS - design and build websites](http://www.htmlandcssbook.com) tonight and I took 8 pages of notes so I am going to do my best to sum up each chapter and not type out the *entirety* of my writing.

**Chapter 18**

*Process and Design* 
- Understand Your Audience - consider the age, gender, location, income, education level, marital status, occupation, and whatever else you can think of that describes your target audience. Make up fictional people that represent your target audience to see how your website appeals to them and meets their needs. Consider their motivation and goals when using your website. 
- Organize Information - use wireframes and sitemaps to plan your design with a focus on clear organization and taking your audience where they need to go. Your main goal is to communicate.
- Use Design Theory and Helpful Tips - design theory like visual hierarchy, grouping and similarity, carefully designed navigation can help you to clearly lead users to their goal. This reminds me of the concept of a "weiner" that Disney uses in park designs to lead guests through the park and help with crowd control.

**Chapter 17**

*HTML Layout*

There are many new elements replacing the blanket use of the `<div>` tag with the release of HTML5. Here are some tags for reference, some of which are new or have new uses.

| Tag | Notes |
| ------------ | ------------- |
| `<header>` `<footer>` | can be used as normal at the top and bottom of the page but also within articles and sections |
| `<nav>` | contains major navigational blocks |
| `<article>` | acts as a container for any section of the page that could stand alone |
| `<aside>` | can be used within an article to contain something directly related or in the main section for a general use |
| `<section>` | groups related content together, typically each section has a heading |
| `<hgroup>` | groups headings together, some people think it's stupid |
| `<figure>` `<figcaption>` | contains images, videos, graphs, diagrams, text, etc that supports the article |
| `<div>` | still used when another element is not appropriate |
| `<a>` | can now additionally be used around block level elements |

**Chapter 8**

*Extra Markup*

There have been two updates to html since the first version I learned in the 90's, HTML4. The current version HTML5 is still in progress but introduces several new elements I listed above. In addition here are some additional markup notes.
- Use `<!DOCTYPE HTML>` at the top of the page to indicate you are writing in HTML5 to the browser.
- To comment out code for notes use `<!-- -->`
- ID attributes are used to identify specific places to add style choices with CSS `<p id= "value">` value must start with a letter or _. Each value must be unique.
- Class attributes are used the same as ID but for several elements at once. The same class value can be used many times within a page to denote the same style. `<p class="value">`
- Block elements always appear to start on a new line `<ul>` `<li>` `<p>` `<h1>`
- Inline elements always appear inline `<a>` `<b>` `<em>` `<img>`
- Use `<span>` to group inline elements for class or id markup to alter the style.
- `<iframes>` place a frame on the page that contains another html page. Use with other attributes like height, width, src, scrolling, frameboarder, etc.
- `<meta>` lives inside head and contains information your browser reads about your site. 
- There are a ton of different escape characters used to allow you to type characters used in code as regular text. I should probably print a reference list.



[Return to the Main Page](README.md)