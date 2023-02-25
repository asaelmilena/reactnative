25/Feb Aprendo un poco más sobre TypeScript.
https://fullstackopen.com/es/part9/antecedentes_e_introduccion

Define a function that takes two arguments of type number and returns a number.
function addNumbers(num1: number, num2: number): number {
  return num1 + num2;
}

Call the function and pass in two numbers as arguments.
const sum = addNumbers(1, 2);

Print the result of the function call to the console.
console.log(sum);

In this example, we define a function called addNumbers that takes two arguments of type number and returns a number. We then call this function and pass in the values 1 and 2 as arguments. The function returns the sum of these two numbers, which we store in the variable sum. Finally, we log the value of sum to the console using the console.log method.

Note that we have added type annotations to the function parameters and return type using the colon : syntax. This helps us catch type errors at compile-time and improves the overall code quality and readability.
