#### answer the questions
- Why would a developer choose to make data models?In order to create a standardized way to store large amounts of data formatted in uncertain ways,helps us to define the relational tables, primary and foreign keys.
- What purpose do CRUD operations serve?
Create, Read, Update, Delete. These special functions place the actions onto rails so that they have to follow the defined structure of the data model.
- What kind of database is Postgres? What kind of database is MongoDB?Postgres is a SQL database. Mongo is a NoSQL database.
- What is Mongoose and why do we need it?
Mongoose is the package that MongoDB uses,it do the mange relations between data and delivery method between our application and our database. `node.js -> mongoose -> MongoDB`
- Describe how NoSQL Databases scale horizontally?adding more machines into your pool of resources, it devide the data in multi servers, it had a benifits it is cheap, better performance, Chances of downtime are less.
- Give one strong argument for and against NoSQL Databases? for: it work with large amount od data,it id quick, low cost, use to used and efficient but: don’t have the reliability functions, not safe.
- Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department?For an apparel brand: Clothing, Accessories, and Hats. Clothing would be in a separate data pool than the other two. Accessories would be adjacent to Clothing. And Hats would fall under Accessories. Perhaps Accessories could fall under Clothing as well but in my head, they are different enough that they should be separate categories of item.
- Name 3 cloud based NoSQL Databases?
Amazon Web Services, Microsoft Azure, Rackspace, and Google Cloud Platform.



#### Document the following Vocabulary Terms
- database: collection of information and data it is organized we can in access, manege and update.
- data model: the model which organized the element of data.
- CRUD: four basic function `create, read, update, and delete` to conti storage 
- schema:represent the storage of data in a database. 
- Structured Query Language (SQL):language for storing,manipulating and retrieving data in databases.
- Non SQL (NoSQL):non relational database
- MongoDB: type of database , it is NoSQL database program use json to documentation.
- Mongoose:package that MongoDB uses,it do the mange relations between data.
- record:object that can contain one or more values.
- document:program use to storing, retrieving and managing document-oriented
- Object Relation Mapping (ORM):converting data between systems using object-oriented.