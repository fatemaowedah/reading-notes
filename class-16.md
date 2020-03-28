## Responsive Web Design:
*building a website suitable to work on every device and every screen size*
### Components of Resonsive design:
* Flexible layouts: build website with flexible grid,capable of dynamically resizing to any width, using length unit `em`,`%`,`vmax`,`vmin`,`vh`,`vw`.
  * turn fixed unit to relative :`target/context=result`
* Media queries: use by (`@media rule`,`@import rule`).
* Viewport 
  * Viewport height &width `<meta name="viewport content="width=device-width>`
  * Viewpor Scale,Viewport Resolution.
* Flexible media: media scalable using max-width 100% .Doing so ensures that as the viewport gets smaller media will scale down according to containers width.
## Float:
*used for positioning and formatting content image float left to the text in a container.* 
* value:(left,right,none,in the text).
* clearing float `clear`:what elements can float beside the cleared element and on which side.
* techniques for clearing float : empty div,overflow,easy clearing.
* problem in float: double margin,3px jog.
## Grid context:
* Columns
* Clearing Context
* Gutters: use fixed pixel size.
  * first step: `box-sizing: border-box;`
  * second step: use fixed padding right.
* Outside Gutters:
  * first step:  left padding to the grid parent
  * second step: restore the right padding to the last column.
## SMACCSS
  *keep CSS more organized and more structured, leading to code that is easier to build and easier to maintain*
  #### There are five types of categories:
  * Base: defining the default styling for how element should look in all occurrences on the page,heading sizes, default link styles, default font styles, and body backgrounds.
  * Layout: general positioning, major elements (header, footer, nav, aside),Classes and IDs.
  * Module: minor element (sit inside Layout, list items, individual images, specific paragraphs), classes
  * State: contain any styling that changes upon user interaction(hover,focus,blur),pseudo classes and element.
  * Themes: small changes on top of all other normal styling, temporary changes.



