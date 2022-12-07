### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
  - A description of the syntax
- An example
- An explanation of the example
- Any additional notes/details

---
Your documentation here: 


**Higher order functions** are functions that take other functions as arguments or return functions as output. They are used to abstract away common patterns of code and make code more concise and readable.

Syntax for higher order functions typically follows the same pattern as other functions. The function takes one or more arguments, which can be either functions or values, and returns a value or a function. 
For example, a higher order function might look like this:
```js
function higherOrderFunction(arg1, arg2, callback) {
  // do something with arg1 and arg2
  const result = // some computation
  return callback(result);
}
```

In this example, `arg1` and `arg2` are the arguments passed to the higher order function, and callback is a function that is passed as an argument. The higher order function does some computation with `arg1` and `arg2`, and then passes the result to the callback function. The callback function then returns a value or a function.


