## Concepts of Functional Programming in Javascript
* Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
* pure functions: 
  * it returns the same result if given the same arguments.
    * Reading Files:it’s not a pure function — the file’s contents can change.
    * Random number generation:Any function that relies on a random number generator cannot be pure.
  * It does not cause any observable side effects. 
    * mutability is discouraged in functional programming.
* Pure functions benefits:
  * The code’s definitely easier to test. We don’t need to mock anything.
* Immutability: tate cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
* Referential transparency: `pure functions + immutable data = referential transparency`
* Functions as first-class entities: functions are also treated as values and used as data.
* Higher-order functions: takes one or more functions as arguments, or returns a function as its result.
* Filter: expects a true or false value to determine if the element should or should not be included in the result collection.

## Refactoring JavaScript for Performance and Readability:
* URL-shortening:We accept a long URL and return a short URL that forwards visitors to the long URL.
* friendly-words package that the Glitch team works on. They use this to generate the random names for your recently created projects!
