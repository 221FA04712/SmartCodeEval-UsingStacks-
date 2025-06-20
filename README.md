SmartCodeEval is a unique and powerful mathematical expression evaluator that supports a wide range of inputs including arithmetic operations, variables, nested parentheses, and built-in functions such as sin, cos, log, sqrt, max, min, and average. What makes it stand out is its ability to handle user-defined variables across multiple expressions, accurately parse and compute nested and multi-argument functions, and robustly detect and report mismatched brackets or invalid syntax. Its custom implementation of infix to postfix conversion and stack-based evaluation allows for precise and efficient computation. The modular design makes it easy to extend with additional features or functions, making it a flexible and educational tool for learning expression parsing and evaluation in Java.


## SmartCodeEval - Intelligent Mathematical Expression Evaluator in Java

SmartCodeEval is a console-based Java application that can parse, tokenize, and evaluate mathematical expressions with support for:

* Variables
* Assignment operations
* Mathematical functions like sin, cos, log, sqrt
* Operators including plus, minus, multiply, divide, power, and unary minus
* Custom error handling and automatic correction of parentheses
* Infix to postfix conversion using the Shunting Yard algorithm

---

### Features

* Tokenization of variables, constants, operators, and functions
* Infix to postfix conversion with proper precedence and associativity
* Stack-based evaluation of expressions
* Supports functions such as sin, cos, tan, sqrt, log, ln, abs, max, min, sum, avg
* Allows variable assignments such as a equals 3 plus 5, then using a in later expressions
* Handles errors such as division by zero and undefined variables
* Logs evaluation steps and postfix expressions for better understanding

---

### Example Usage

Input: a = 5 + 3
Output: 

Token: 5 
| Stack before: []
Stack after: [5.0]

Token: 3 
| Stack before: [5.0]
Stack after: [5.0, 3.0]

Token: + 
| Stack before: [5.0, 3.0]
Stack after: [8.0]

Assigned: a = 8.0
Result: 8.0

---

### Project Structure

SmartCodeEval.java - Contains the main logic for tokenization, parsing, evaluation, and user interaction

---

### How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/SmartCodeEval.git
cd SmartCodeEval
```

2. Compile and run the program:

```
javac SmartCodeEval.java
java SmartCodeEval
```

---

### Algorithms Used

* Shunting Yard Algorithm for converting infix to postfix expressions
* Stack-based evaluation for postfix notation
* Regular expression based token classification for parsing

---

### Topics Covered

This project demonstrates the following concepts:

* Expression parsing
* Stack data structures
* Recursion and function evaluation
* Use of Java collections such as Map, Stack, and List
* Exception handling and validation

---

### Author

Bhargavi - Computer Science Engineering student

