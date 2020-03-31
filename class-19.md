## css grid
*CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns.*
* Grid gives us control over how wide or narrow each of the ‘grid cells’ get. This allows us to maintain a sensible aspect ratio to their height.
* The repeat() function takes two arguments, the first will define the number of column tracks and the second, what width the tracks should be.
#### property of Grid Container: display; grid,inline-grid
* grid-column-start.
* grid-column-end.
* grid-template-columns ,grid-template-rows: `track-size`,`line-name`
* grid-template-areas: `grid-area-name`,`none`
* grid-template:`none`,`grid-template-columns`,`grid-template-rows`,`grid-template-areas`
* Instead of defining a grid item based on the start and end positions of the grid lines, you can define it based on your desired column width using the `span` keyword
* One of the things that sets CSS grids apart from flexbox is that you can easily position items in two dimensions: columns and rows. `grid-row-start` works like `grid-column-start` except along the vertical axis.
* grid-area
* `order` property, which is one of the advantages of grid over table-based layout, similar to z-index.
* grid-template-columns
* grid-template-rows
* grid-column-gap,grid-row-gap:`line-size`
* grid-gap:A shorthand for `grid-row-gap and grid-column-gap`
* justify-items: `start`,`end`,`center`,`stretch`.
* align-items:`start`,`end`,`center`,`stretch`.
* place-items: both the `align-items and justify-items` properties
* justify-content: `start`,`end`,`center`,`stretch`,`space-around`,`space-between`,`space-evenly`.
* align-content:`start`,`end`,`center`,`stretch`,`space-around`,`space-between`,`space-evenly`.
* place-content:sets both the align-content and justify-content properties
* grid-auto-flow: `row`,`column`,`dense`.
#### property of Grid Item
* grid-column-start,grid-column-end,grid-row-start,grid-row-end:`line`,`span<number>`,`span<name>`,`auto`
* grid-column,grid-row:`<start-line>`,`<end-line>`
* grid-area:`<name>`,`<row-start>`,`<column-start>`,`<row-end>`,`<column-end>`
* jusify-self: `start`,`end`,`center`,`stretch`.
* align-self:`start`,`end`,`center`,`stretch`.
*place-self: `auto`,`<align-self>`,`<justify-self>`
