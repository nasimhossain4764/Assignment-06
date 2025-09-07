1) Difference between var, let, and const:-

    **var: can be re-declared & updated, function-scoped, and hoisted with undefined.

    **let: can not be re-declared but can be updated, block-scoped, and hoisted but not initialized.

    **const: can not be re-declared or updated, block-scoped, and hoisted but not initialized.
    

2) Difference between map(), forEach(), and filter():-

    **forEach():- Iterates through each element of an array but does not return a new array.

    **map():- Iterates & applies a function to each element of an array and returns a new array with transformed values.

    **filter():- Iterates and checks a condition and returns a new array with elements that match the condition.


3) Arrow Functions in ES6:-

    **Arrow function is the shorter syntax for writing functions. We need not to use 'function' keyword to declare a function.
    **Example:-  const add = (a, b) => a + b;   


4) Destructuring Assignment in ES6:- 

    **Extracts values from arrays or objects and assigns them to variables in a single step.

    **Example:- const user = { name: "Nasim", age: 23 };
                const { name, age } = user;
                console.log(name, age);  // Nasim 23


5) Template Literals in ES6:-

   **Use backticks (`) instead of quotes.

   **Allow ${} for inserting variables/expressions.

   **Can write multiline strings easily.
                 
    