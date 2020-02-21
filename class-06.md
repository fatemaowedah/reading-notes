## JavaScript
### Object:
* *Object is a set of variable and function to create a model of a something , we call variable in object as a property (tell us about object) and called function as a methods (represnt task that are associated with object).* in the properties we call name as a key,the value can be string,number,boolean,array we put betwwen key and value `:`.we put object between `{}`.
* To access property or methods of an object we use:
  * name of object followed by poroperty name.
  * name of object followed by `['name of property']`.
  * name of object followed by method name.
  
  ### Document object model
  When the browser load web page it create model of that page (DOM tree) it consists of four main type of nodes:
  * The Document Node.
  * The Element Node.
  * Attribute Nodes.
  * Text Node.
  #### Working with Dom Tree :
  * Access The elements
    * Select Individual Elements : `getElementById()`,`querySelectors()`.
    * Select Multiple Elements : `getElementByClassName()`,`getElementsByTagName()`, `querySelectorsAll()`.
    * Traversing between Elements Node: `parentNode`, `previousSlibling`, `nextSlibling`, `firstChild`, `lastChild`.
 * Work with those elements
    * Access/ update text node.
    * Work with html content .
    * Access or update attribute values. 
 * Access and update text with textContent and innerText: `textContent`, `innerText`.
 * Adding elements using Dom Mainpulation : 
   * Create the element :`createElement()`
   * Give it content:`createTextNode()`
   * Add it to the dom: `appendChild()`
 * Removing Elements Via Dom Manipulation :
   * Store The Element to be removed in a variable.
   * Store the parent of that element in a variable.
   * Remove the element from containing element.
 * Attribute Nodes : we write Dom Query then put member operator after that the method like `document.getElementById('one').getAttribute('class');` 
   * Method : getAttribute(), has Attribute(), setAttribute(), removeAttribute().
   * Property : className, id.

### Understanding The Problem Domain Is The Hardest Part Of Programming
*The hardest thing about programming is learning a problem domain.*
 * Why problem domains are hard ?
 *because problem domain are like a puzzle with a blurry picture or no picture at all.*
 * programming is easy if you understand the problem domain: 
 * What can you do about it ?
   * make the problem domain easier by cutting out cases and narrowaing your focus to particular part of problem.
   * become better at understanding problem domains.







