### API Server
##### Express: Router Parameters
route parameters it is URL segments used to capture the specified at the position in URL we populated in req.params object with name of the route parameters, we can read the prameters in the route and we can run middle-ware on any route and run it in every request, expert let you run the middle-ware when certain prameter are present and expected.
##### Router Param()
it have name and callback as parameter , the parameter of callback function are req, res, nest the name of parameter and the value of name, param callback are local to the route it callend once in req-res cycle.
##### Sub Documents in Mongoose
are document embaded in other document, it is nested schema it have middle-ware it is schema ORM the feature of it is provide structure to mongo document because mongo not structured for that mongoose allow us to put rule and validation, sub documentation help you to descripe deeper part od data model, it help to keep the shape of data the same, it is good for supportive data,the differnet sub documentation not save individual, it save whit top-level parent document, it have `save()` and `validate()` it will execute before or after top level document , you can found it by id, you can add it to array by: push, unshift, addToSet, we can remove it by pull(),remove(), you access perent by parent().
##### Joining Data/Documents in Mongo
in noSQL database dont join in mongoose we can use populate() to join two collection, t will execute before or after top level document , you can found it by id, you can add it to array by: push, unshift, addToSet, we can remove it by pull(),remove(), you access perent by parent().
##### Virtual Joins
it work by create virtual field then do the population as we find or load document, you can use the populate match option to add filter populate().query, it not include toJSON() then use res.json(), there is count option.