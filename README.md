# Zap Interpreter

The Zap Interpreter is an interpreter written in Java for a toy language named "Zap". 
It supports 4 data types: Booleans, Strings, Numbers, and Nil.

It also has all the four basic arithmetic expressions and all the comparison operators we see in C. 
Subsequently, it has all 3 basic logic operators. The precedence order is the same as C. Statements must end with `;` and can be block-scoped. 
Variables can be declared using `var`.

The language has the usual `if`, `else`, `while`, and `for` statements, but it does not have ternary operators. 
Printing to the console can be done through `print "Hello World"`. 

The language is dynamically typed and functions and classes will be implemented soon.

## Prerequisites

To run the Zap Interpreter, you need to have [Java](https://www.java.com/en/download/) installed on your computer.

## How to run the Interpreter

1. Clone the repository to your local machine using the command:

    `git clone https://github.com/42eggs/Zap-Interpreter.git`

2. Open the project in IntelliJ Idea.
3. Navigate to the `Zap` class and run the main method with or without arguments.
4. If you want to run Zap code from a file, you can include a path to the file as an argument when running the main method. 
   For example, you can run: `java Zap {path-to-zap-file}`


## Sample Zap code

Here's a sample Zap code that you can use to test the interpreter:

```
var x = 10;
var y = 5;

if (x > y) {
print "x is greater than y";
} else {
print "x is not greater than y";
}

while (x > 0) {
print x;
x = x - 1;
}
```



When you run this code using the Zap Interpreter, it should output the following:

```
x is greater than y
10
9
8
7
6
5
4
3
2
1
```

## License

The Zap Interpreter is released under the [MIT License](https://opensource.org/licenses/MIT).