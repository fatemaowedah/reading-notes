# HTML

## Text:
* **Headings** 
*HTML has six level of Heading "h1-h6"* 
`<h1>` use for main heading
`<h6>` use for subheadings
* **Paragraphs** 
*when you want to write paragraph use `<p>`*
* **Bold** use `<b>` to make words in tags bold
* **Italic** use `<i>` to make words in tag italic
* **Superscipt** use `<sup>` 
* **Subscript** use `<sub>`
* **Line Breaks** use `<br />` to add line breaks.
* **Horizontal Rules** use `<hr />`
* **Strong** use `<strong>` to indecate that its content  has strong importantce.
* **Emphasis** use `<em>` to indicate emphasis.
* **Quotations** 
  * `<blockqoute>` use it for large quote
  * `<q>` use it for short quote.
* **Abbreviations** use `<abbr title=" ">` the title apper when you hover the mouse in the world.
* **Citations** use `<cite>` to indicate where the citation is from.
* **Definitions** use `<dfn>` to indicate the defining instance of new term.
* **Author Details** use `<address>` will display in italics.
* **Change to Content** 
  * `<ins>` the word have underline in it.
  * `<del>` the word have line through it.
  * `<s>`  the word  have line through the center.
## Introduction Css
*Css is casecading style sheets*
*Css rule consist of:* `selctor {decaration}`
example : `p {font-family:Arial;}`
*decaration consist of:
* property.`font-family`
* value.`Arial`
### How to write Css:
* Externial CSS :`<link rel="stylesheet" href=" " />`
* Internial CSS : inside `<style>` which usually inside `<head>`
### CSS Selectors
* Universal selector `*{}`
* Type Selectors `element name{}`
* Class Selectors `.class name {}`
* Id selectors `# id name {}`
* child selectors `li>a{}`
* Descendant selector `p a {}`
* Adjacent slbling `h1+p{}`
* General Slbling `h1~p {}`
### How Css Rules Casecade:
* Last Rule.
* Specificity.
* Important.

# JavaScript
## Basic javascript:
* Statments :
* Each of the lines of code in green is a statement
* `{}` indicate the start and end of code block.
* line in purple determine code should run.
**JAVASCRIPT IS CASE SENSITIVE**
* Comments :
* to explain what your code does.
* Multi-line Comments `// ....`
* single-line Comments `/* .....*/`
* Variable :
* the data stored in a variable can change each time a script runs.
* `var quantity= 3;` 
  *var:keyword
  *quantity:variable name.
  *3:variable value.
### using of variable:
* store number, use number (0-9)
* store string
* Store a boolean, have to value true & False.
### Arrays
*Array is a special type of variable*
we use it when you are working with a list or a set of value that are related to each other.`color = ["white","black","custom"];`
* Numbering items : index value start at 0 
* Accessing items : varName = color[2];
* Number of items : varName = color.lengeh;

### Expressions:
* Assign a value to a variable.`var color = 'being';`
* Use two or more values to return a single value. `var area = 3 * 2;`
### Operators:
* Assignment: `color = 'being';`
* Arthmatic: `area = 3 * 2;`
  * Addition `+`
  * Subtraction `-`
  * Division `/`
  * Multiplication `*`
  * Modulus `%`
  * Increment `++`
  * Decrement `--`
* String: `greeting = 'hi' + 'molly';`
* Compration: `buy = 3 > 5;`
* logical: `buy = (3 > 5) && (2<4);`

## Decisions & Loops :

### Evaluating Conditions :
* we can comparing one value in the script to what you expect.
* the result will be aboolean : true or false.
* is equal to `==` compare two value if they are same.
* is not equal to `!=`compare two value if they are not same.
* strict equal to `===` to check that both the data type and value are the same.
* strict not equal to `!==`to check that both the data type and value are not the same.
* Grater than `>`
* Less than `<`
* Greater than or equal to `>=`
* Less than or equal to `<=` 

*Logical operators allow you to compare the result of more than one comparison operator by :*
* Logical and`&&` test more than one condition.
* Logical and`||`at least one condition.
* Logical and`!`takes a single Boolean value and inverst it.

### If Statement:
`if (score >= 50){
    congratulate();
}else{
    encourage();
}'
* `if`: keyword
* `(score >= 50)` : Condition
* `congratulate();` : Code to execute if value is true
* `else` : Keyword 
* `congratulate();` : Code to execute if value is true






