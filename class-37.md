### Express
##### Express Routing
refers to how an application’s endpoints (URIs) respond to client requests, as jQuery and js the request consist of `/:parameters` and quey string, response it dend the data to browser by send or status ,the output maybe be status code or cookies, the route define by method ad HTTP methods app.get(),app.post(),app.all(),app.use().
##### Express Middleware
a sries of function have access to req and res object every function have req, res and next as a parameters,there is application in it like: error handler, bring other route, apply default,JSON. But the route it work with specific things, and there is a lot of advantage of it as dynamic model, logging, browser,location,specific content.
##### Modularization & Separation of Concerns
which mean do separting to the functionality into independat and each module contain everythings necessary to execute one aspect of the desired functionality
###### CRUD Operations with REST and Express 
it is Create, read, update, destroy.
##### Server Testing
export server as a module, use supertest to run the test to avoide problem, and put the superagent in module and invoke the file as`jest.mock()`, supertest  provide a high-level abstraction for testing HTTP, while still allowing you to drop down to the lower-level API provided by superagent, you can install it by `npm install supertest --save-dev`and after install it you must reqauire it.
##### HTTP Status Codes
1xx Informational like 100 Continue/ 101 Switching Protocols/102 Processing (WebDAV),2xx Success like:200 OK/201 Created/ 204 No Content, 3xx Redirection like: 304 Not Modified, 4xx Client Error like: 400 Bad Request/401 Unauthorized/403 Forbidden/404 Not Found/409 Conflict, 5xx Server Error ike:500 Internal Server Error.
