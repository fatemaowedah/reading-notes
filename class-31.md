## Readings: Node Ecosystem, TDD, CI/CD
1- Why would you want to run JavaScript code outside of a browser?
*it using Node.js it just took V8 engine and made it run independently as javaScript runtime, to generate dynamic page content, can create, open, read, write, delete, and close files on the server, can collect form data, can add, delete, modify data in your database*
2- What is the difference between a module and a package? 
*A package is a directory with one or more modules inside of it,contains all the files you need for a module.and a package.json file which has list of other packages the application depends upon to install use `npm install <package>`* AND *A module is a single JavaScript file that A set of functions you want to include in your application.,to lood the module use `const name = require('package')`*
3- What does the node package manager do?
*npm is the default package manger for Node.js , we use it to install third-party libraries(packages) and manage dependencies butween them,and when you register is a puplic repo for modules puplished by people delivery javascript modules.*
4- Provide code snippets showing 3 different ways to export a function from a node module?
* anonymous function: `module.exports=function () {console.log('bars was called);};`
* Export function as a class: 
>module.exports = function (firstName, >lastName) {
    >this.firstName = firstName;
    >this.lastName = lastName;
    >this.fullName = function () { 
        >return this.firstName + ' ' + this.>lastName;
    >}
>}
* >module.exports = {
    >film101: film101,
    >film102: film102
>}
#### I use book of Full stack web app development to unswer the questions

### Document the following Vocabulary Terms
* Node.js: open source server environment, allows you to run JavaScript on the server.
* V8 Engine:  open-source JavaScript engine developed by The Chromium.
* Module: same as JavaScript libraries, A set of functions you want to include in your application.
* Package: contains all the files you need for a module.
* npm: Open-source developers use npm to share software.
* server: is a computer program or a device that provides functionality for other programs or devices, called "clients".
* Enviroment: object that is similar to process.env but behaves like a real object.
* Interpreter: Tool for managing different language files for an application
* Compiler: is a special program that processes statements written in a particular programming language and turns them into "code" .
### NPM 
* npm is open source develper a lot of software register in it we can share our code in it ,and use code of another developer, it is a node.js packages and modules and we can dawnload the packages and module,
