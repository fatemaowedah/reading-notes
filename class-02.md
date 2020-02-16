# HTML

## Text:
* **Headings** 
*HTML has six level of Heading "h1-h6"* 
`<h1>` use for main heading
`<h6>` use for subheadings
* **Paragraphs** 
  paragraph use `<p>`,  Bold `<b>` , Italic `<i>` , Superscipt `<sup>`, Subscript `<sub>`, Line Breaks `<br />`, Horizontal Rules `<hr />`Strong `<strong>` content  has strong importantce , Emphasis`<em>` , Quotations`<blockqoute>` large quote ,`<q>` use it for short quote Abbreviations`<abbr title=" ">` the title apper when you hover the mouse in the world,Citations`<cite>`,Definitions`<dfn>`,Author Details`<address>`Change to Content:`<ins>` the word have underline in it,`<del>` the word have line through it, `<s>`  the word  have line through the center.
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


# JavaScript
## Basic javascript:
* Statments 
* `{}` indicate the start and end of code block.
**JAVASCRIPT IS CASE SENSITIVE**
* Comments :
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
* Assign a value to a variable.
* Use two or more values to return a single value.
### Operators:
* Assignment.
* Arthmatic.
* String .
* Compration.
* logical.

## Decisions & Loops :

### Evaluating Conditions :
* we can comparing one value in the script to what you expect.
* the result will be aboolean : true or false.
 is equal to `==`, is not equal to `!=` ,strict equal to `===`, strict not equal to `!==`,Grater than `>`, Less than `<`, Greater than or equal to `>=`, Less than or equal to `<=` 

*Logical operators allow you to compare the result of more than one comparison operator by :*
*  `&&` test more than one condition.
*  `||`at least one condition.
*  `!`takes a single Boolean value and inverst it.

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






