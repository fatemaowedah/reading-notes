# JAvascript
## Charts
### Create charts
* to create charf `<canvas>`
* before pull request the project Look over contributing guidelines.
### Canvas Elements
* it is look like image, but doesn't have src and alt attributes.
* canvas have just two attribute : width, height.
* id attribute isn't specific to canvas.
* canvas element can styled like any normal image.
* diff from image : it's easy to define some fallback content, providing fallback cntent
* Required `</canvas>`
### Rendering context
* Canvas create fixed-size drawing surface.
* rendering context used to create and mainplute the contant shown.
### Drawing shapes with canvas
* the grid or coordinate space canvas element have wide 150 px - 150px heigth.
* drawing restangle :fillRect, strokeRect, clearRect.
* drawing path: path is a list of point connected by segments of line can be of different shapes
  * create path
  * draw into path.
  * beginPath(), path methods, closePath(), stroke(), fill().
* Moving the pen: moveTo(x, y)
* lines : lineTo(x,y)
* Arcs: `arc(x, y, radius, startAngle, endAngle, anticlockwise)`, `arcTo(x1, y1, x2, y2, radius)`.
* Bezier and quadratic curves: `quadraticCurveTo(cp1x, cp1y, x, y)`, `bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)`.
* Cubic Bezier curves.
* path2d object :`Path2D.addPath(path [, transform])`
### Applying styles and color
* Colors: `fillStyle = color`,`strokeStyle = color`
* Transparency: `globalAlpha = transparencyValue`.
* line styles: `lineWidth = value`, `lineCap = type`, `lineJoin = type`, `miterLimit = value`, `getLineDash()`, `setLineDash(segments)`, `lineDashOffset = value`.
* lineCap: butt, round, square.
* lineJoin: round, bevel, miter
* Gradients: `createLinearGradient(x1, y1, x2, y2)`, `createRadialGradient(x1, y1, r1, x2, y2, r2)`, `gradient.addColorStop(position, color)`
* Patterns: repeat, repeat-x, repeat-y, no-repeat.
* shadow: `shadowOffsetX = float`, `shadowOffsetY = float `, `shadowBlur = float`, `shadowColor = color`.
### Drawing text
* render text: `fillText(text, x, y [, maxWidth])`, `strokeText(text, x, y [, maxWidth])`.
* styling Text: `font = value`, `textAlign = value`, `textBaseline = value`, `direction = value`
* Advanced text measurements: measureText()
