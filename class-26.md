## EJS 
### What is EJS?
*EJS is a simple templating language that generate HTML with JavaScript. No reinvention of iteration and control-flow. It's just plain JavaScript.*
* Install by `npm install ejs`, `npm install --save ejs`
* use `let ejs = ejs = require('ejs')`
* browser support `<script src="ejs.js"></script>`
* option: cache,filename,context,compileDebug,client,delimiter,debug,_with,localsName,rmWhitespace,escape,outputFunctionName,async.
* Tags:  
  * `<%` 'Scriptlet' tag, for control-flow, no output
  * `<%_` ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it.
  * `<%=` Outputs the value into the template (HTML escaped)
  * `<%-` Outputs the unescaped value into the template
  * `<%#` Comment tag, no execution, no output
  * `<%%` Outputs a literal '<%'
  * `%>` Plain ending tag
  * `-%>` Trim-mode ('newline slurp') tag, trims following newline
  * `_%>` ‘Whitespace Slurping’ ending tag, removes all whitespace after it
* Includes: ` <%- include('user/show', {user: user}); %>`
* Caching:EJS ships with a basic in-process cache for caching the intermediate JavaScript functions used to render templates. `let LRU = require('lru-cache');`
## APIs
### Working with volumes:
* Performing a search: `https://www.googleapis.com/books/v1/volumes?q=search+terms`
* `q`: Search for volumes that contain this text string. There are special keywords you can specify in the search terms to search in particular fields, such as:
  * intitle,inauthor,inpublisher,subject,isbn, lccn,oclc.
* Optional query parameters: You use the download parameter to restrict the returned results to volumes that have an available download format of epub by setting the to the value epub.
* Filtering: partial,full, free-ebooks,paid-ebooks,ebooks.
* Pagination : startIndex, maxResults.
* Print Type: all, books, magazines.
* Projection:full, lite.
* Sorting: relevance,newest.
