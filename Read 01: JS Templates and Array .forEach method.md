## JS Templates

## Template literals (Template strings)

- Template Literals are in backticks ( ``) and use the dollar sign and curly braces. Ex:`${name}, Thank you for your info!'
- It default function concatenates the expression into a single string.

- Multi-line strings:

  - With normal strings you use the \n syntax to get a new line.
  - With template literals you use the backticks to acomplish the same thing.

- Using template literals as 'syntactic sugar' it makes the code more readable.
- Template strings use placeholders
- Can also use expressions inside the template literals ex: let total = `The total price is ${price * tax`};

## Array Methods

- forEach() array method executes a function one time for each array element. This function calls a callback function once for
  each element in the array, in ascending order.
- forEach() only works on arrays.
- They read better that regular for loops
  -- callback: It accepts between 1 and 3 arguments, and is a function to execute on each element.
  #1. The value of the element
  #2. The index
  #3. The array object
  -- currentValue: the current element in the array.
