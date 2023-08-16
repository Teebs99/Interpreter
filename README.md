# Interpreter

This interpreter is written in Go to create a new programming language. Although the language is fairly limited it supports math expressions, variables, functions, application of functions, conditionals, returns, higher-order functions, and closures. The language's supported data types are integers, booleans, strings, arrays, hashes, and supports null values. 

The language also has several built-in functions to make development easier. 
  - len(): returns len of object/array
  - first(): returns the first item in the array or null
  - last(): returns the last item in the array or null
  - rest(): returns a new array without the first element of the given array or null
  - push(): returns a new array with the given item appended to the end of the array
  - print(): prints every argument on a new line.

# Installation

Download [GoLang](https://go.dev/) and clone the repo.

# Running the REPL

Navigate into the directory that the repo has been cloned to.

Once there run ```go run main.go``` to start the REPL. Once the repl has been started you can begin writing code using the created language.

## Example Code
Here is a short snippet of some example code. The unit tests have more examples of what code should & should not work.

```
let five = 5;
let ten = 10;

let add = fn(x, y) {
  x + y;
};

let result = add(five, ten);
!-/*5;
5 < 10 > 5;

if (5 < 10) {
    return true;
} else {
    return false;
}
```

# Next Steps
I built this interpreter as a way to challenge myself and have a better understanding of how things work under the hood. I will move on to other challenges and projects, the next step for this project is to turn it into a compiled language. 

Other than compilation, there will most likely be no further feature updates to the language/interpreter. 

I learned how to make this interpreter with the help of Thorsten Ball's book [Writing An Interpreter In Go](https://interpreterbook.com/)

I will be following along with his next book [Writing A Compiler In Go](https://compilerbook.com/)
