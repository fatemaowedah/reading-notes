### Authentication
#### User Modeling
as a develper we have the responsibility to store inforemation there is some sevsitive information about user such as: email, user name , but there is sensetive information like passward we do not sent them to client application, and the developer have the responsibility to do not client access other client sensetive information.
#### Cryptography
it is related to method to do encoded msg which mean this sensitive information can be read only the person who know this secret information, there is a type of cryptography: Hash Algorithms, Cypher Algorithms.
#### Hash Algorithms
type of cryptography, it take the data then a hash that is deliberately difficult to reverse, we use the hash algorithms to check the integrity of data, when the user put the passward can be stores when the user signs up when the user want to resign it will send the passward.
#### Cypher Algorithms
type of cryptography, it take a piece of data and a key and produces encrypted data, we can recoded this data to origin data by using the key, token seed it will create when the user create a random unique string, 
#### Basic Authorization
 process of verifying that an individual, entity or website is whom it claims to be, way to send username and password in an HTTP request, this data it joind `Authorization: Basic <credentials>`with`:base64 encoded”`  the server can retrieve the username and password, HTTPS to protect the username and password as it travels across the network, Microsoft Internet Explorer caches the credentials for fifteen minutes by default, 
#### Introduction to JSON Web Tokens
is an open standard, it transmit the information between as JSON object, this information is trusted because it is  digitally signed,  by using HMAC algorithm or puplic/ private key use RSA or ECDSA. it use JWTs to provide secrecy between parties, we use JWT Authorization: when user sign in allow user to access route, services and resources, because it is small easy to used, Information Exchange, JSON Web Tokens consists of header: consist of alg and typ, payload: registered, public, and private claims , Signature.
#### bcrypt docs
A library to help you hash passwords, node-gyp only works with stable/released versions of node, node-gyp, you can install in by `$ npm install -g node-gyp`

