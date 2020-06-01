### Express Routing & Connected API
##### Express Routing
refers to how an application’s endpoints (URIs) respond to client requests, as jQuery and js the request consist of `/:parameters` and quey string, response it dend the data to browser by send or status ,the output maybe be status code or cookies, the route define by method ad HTTP methods app.get(),app.post(),app.all(),app.use(), the routing method maybe have more than one callback function for that we put next as argument .
##### Route methods
it is like HTTP methods such as app.post(),app.all(),app.use(),app.put(),app.delete().
##### Route paths
it is compain with req method , it can be string/string patterns/requkar expressions, route parameters it is URL segments used to capture the specified at the position in URL we populated in req.params object with name of the route parameters.
##### Route handlers
middleware it provide multiple callback function to handle request, can be in the form of a function, an array of functions, or in both. there is response method to send it to client like ,res.download(),res.end(),res.json(),res.jsonp(),res.redirect(),res.render(),res.send(),res.sendFile(),res.sendStatus().


