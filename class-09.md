# Html
## Forms
### Form Controls 
* adding Text :
  * text input.
  * password input.
  * text area.
* making choise:
  * Radio buttons.
  * Checkboxes.
  * drop-down boxes.
* Submitting Forms:
  * submit buttons.
  * image buttons.
* uploading file.
### How Forms Work 
* presses button
* the name of form is set with the value 
* store information in database.
* server create a new page based in information recived.
### Form Structure 
*to use form `<form>` it have attribute : action, method(get or post),id .*
*information from form is sent in name/value pairs.*
### input 
* text input :use `<input>`it have attribute: name,type="text",maxlength,size.
* password input :use `<input>`it have attribute: name,type="password",maxlength,size.
* textarea :use `<textarea>`it have attribute: name,cols,rows.
* radio button :use `<input>`it have attribute: name,value, checked
* checkbox :use `<input>`it have attribute: name,value, checked.
* Drop Down list box: use `<select name = "">`indide it put `<option value="" selected>`
* file input box :use `<input>`it have attribute: type="file".
* submit button :use `<input>`it have attribute: name,type="submit",value.
* image button :use `<input>`it have attribute: type="image"
## List, Tables and forms
### Style
* list-style-type :
  * unordered list : none,disc,circle,square
  * ordered list: decimal,lower-alpha,upper-alpha,lower-roman,upper-roman.
* list-style-image it have `url`
* list-style-position: outside,inside.
* list shorthand `list-style`example`list-style: inside circle;`
* table properties: width,padding,text-transform,letter-spacing,font-size,text-align,background-color.
* empty cells: show,hide,inherit.
*gaps between cells:border-spacingmborder-collapse,separate.
* style text input: font-size,color,background-color,border,border-radius.
* style submit buttons: color, text-shadow,border-bottom,background-color.
# JavaScript
## Events
### Diffrent event type:
* ul events:load,unload,error,resize,scroll.
* Keyboard event:keypress,keydown,keyup.
* mouse event: click, dbclick,mousedown,mouseup,mousemove,mouseover,mouseout.
* foucus events: focus, focus in, blur, focusout.
* form events: input, change, submit, rest, cut, copy, past, select.
* mutation event:DOMSubtreeModified, DOMNodeInserted, DomNodeRemoved, DOMNodeInsertedIntoDocument, DOMNodeRemoveFormDocument.
### Traditional Dom Event handlers
*put element then dot then the event = code.*
### Event Listeners
*put element then dot then adds event listener to the dom element node*
### using parameters with event handlers
Because you cannot have parentheses after the 
function names in event handlers or listeners passing arguments requires a workaround. 

