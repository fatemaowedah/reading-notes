## Sending form data
### Client/server architecture:
 *a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.*
* On the client side: defining how to send the data:The     `<form>` element defines how the data will be sent.
  * The action attribute:  Its value must be a valid relative or absolute URL.
  * The method attribute: the most common being the GET method and the POST method
    * The GET method: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.
    * The POST method: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.
* On the server side: retrieving the data: Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. The way you access this list depends on the development platform you use and on any specific frameworks you may be using with it.





