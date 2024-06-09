## Most common structures in Programing languages Javascript, Python, C#:
### Table of Contents
- [Input/Output](#inputoutput) Operations that handle interaction with the user or other systems, such as print or console.log for output, and input for input.
- [Variables](#variables) Used to store data that can be used and manipulated throughout a program.
- [Data Types](#data-types) Define the type of data a variable can hold, such as integers, floats, strings, booleans, etc.
- [Operators](#operators) Symbols that perform operations on variables and values. Common operators include arithmetic operators (+, -, *, /), comparison operators (==, !=, <, >, <=, >=), and logical operators (&&, ||, !).
- [Control Structures](#control-structures)
    - Conditional Statements: Allow the execution of code based on certain conditions (if, else if, else, switch).
    - Loops: Allow the repeated execution of a block of code (for, while, do while, foreach).
- [Functions/Methods](#functionsmethods) Blocks of code designed to perform a particular task, which can be reused throughout a program.
- [Collections](#collections) Data structures that store multiple values, such as arrays, lists, sets, and dictionaries (or maps).
- [Classes and Objects](#classes-and-objects) Fundamental to object-oriented programming, these are blueprints for creating objects (instances of classes) that encapsulate data and behaviors.
- [Exception Handling](#exception-handling) Structures to handle errors and exceptions to ensure the program can deal with unexpected situations (try, catch, finally).

| Structure               | JavaScript                               | Python                                      | C#                                      |
|-------------------------|------------------------------------------|---------------------------------------------|-----------------------------------------|
| **Variables**           | `let x = 10;`                            | `x = 10`                                    | `int x = 10;`                           |
| **Data Types**          | `Number`, `String`, `Boolean`, `Object`  | `int`, `float`, `str`, `bool`, `list`, `dict` | `int`, `float`, `string`, `bool`, `List<>` |
| **Operators**           | `+`, `-`, `*`, `/`, `==`, `!=`, `&&`, `||` | `+`, `-`, `*`, `/`, `==`, `!=`, `and`, `or` | `+`, `-`, `*`, `/`, `==`, `!=`, `&&`, `||` |
| **Conditionals**        | `if`, `else if`, `else`, `switch`        | `if`, `elif`, `else`                        | `if`, `else if`, `else`, `switch`       |
| **Loops**               | `for`, `while`, `do while`, `for...of`   | `for`, `while`                              | `for`, `while`, `do while`, `foreach`   |
| **Functions**           | `function name(params) { ... }`          | `def name(params): ...`                     | `void Name(params) { ... }`             |
| **Input/Output**        | `console.log("message");`                | `print("message")`                          | `Console.WriteLine("message");`         |
| **Collections**         | `Array`, `Object`                        | `list`, `set`, `dict`                       | `Array`, `List<>`, `Dictionary<>`       |
| **Classes and Objects** | `class MyClass { constructor() { ... } }` | `class MyClass: def __init__(self): ...`    | `class MyClass { public MyClass() { ... } }` |
| **Exception Handling**  | `try`, `catch`, `finally`                | `try`, `except`, `finally`                  | `try`, `catch`, `finally`               |

[Back to top](#table-of-contents)

## inputoutput
Outputs a message to the console 

| Feature              | JavaScript                      | Python                           | C#                                 |
|----------------------|---------------------------------|----------------------------------|------------------------------------|
| **Basic Syntax**     | `console.log(message);`         | `print(message)`                 | `Console.WriteLine(message);`      |
| **Printing Variables** | `console.log("Value is " + x);` | `print("Value is", x)`           | `Console.WriteLine("Value is " + x);` |
| **Multiple Arguments** | `console.log(a, b, c);`         | `print(a, b, c)`                 | `Console.WriteLine("{0} {1} {2}", a, b, c);` |
| **Formatting Strings** | `console.log(\`Value is ${x}\`);` | `print(f"Value is {x}")`         | `Console.WriteLine($"Value is {x}");` |
| **Example**          | `let x = 10;`                   | `x = 10`                         | `int x = 10;`                       |
|                      | `console.log("x is", x);`       | `print("x is", x)`               | `Console.WriteLine("x is " + x);`   |

[Back to top](#table-of-contents)

## variables
| Feature                | JavaScript                        | Python                            | C#                                   |
|------------------------|-----------------------------------|-----------------------------------|--------------------------------------|
| **Variable Declaration** | `let x = value;`                | `x = value`                       | `int x = value;` (for integers)      |
|                        | `const y = value;`               |                                   | `string y = "value";` (for strings)  |
| **Variable Assignment** | `x = newValue;`                 | `x = newValue`                    | `x = newValue;`                      |
| **Variable Types**     | Dynamic typing                   | Dynamic typing                    | Static typing                        |
| **String Variables**   | `let name = "John";`             | `name = "John"`                   | `string name = "John";`              |
| **Integer Variables**  | `let age = 30;`                  | `age = 30`                        | `int age = 30;`                      |
| **Boolean Variables**  | `let isValid = true;`            | `is_valid = True`                 | `bool isValid = true;`               |
| **Example**            | `let x = 10;`                    | `x = 10`                          | `int x = 10;`                        |
|                        | `const y = 20;`                  | `y = 20`                          | `const int y = 20;`                  |
|                        | `let name = "Alice";`            | `name = "Alice"`                  | `string name = "Alice";`             |
|                        | `let isTrue = false;`            | `is_true = False`                 | `bool isTrue = false;`               |

[Back to top](#table-of-contents)
## conditional (if-else) syntax

| Feature           | JavaScript                                   | Python                                    | C#                                         |
|-------------------|----------------------------------------------|-------------------------------------------|--------------------------------------------|
| **If Statement**  | `if (condition) {`                          | `if condition:`                           | `if (condition)`                           |
|                   | `  // code to execute if condition is true`  | `  # code to execute if condition is true`| `{`                                        |
|                   | `}`                                          |                                           | `  // code to execute if condition is true`|
|                   |                                              |                                           | `}`                                        |
| **Else If Statement** | `else if (condition) {`                  | `elif condition:`                         | `else if (condition)`                      |
|                   | `  // code to execute if else-if is true`    | `  # code to execute if condition is true`| `{`                                        |
|                   | `}`                                          |                                           | `  // code to execute if condition is true`|
|                   |                                              |                                           | `}`                                        |
| **Else Statement** | `else {`                                    | `else:`                                   | `else`                                     |
|                   | `  // code to execute if all conditions are false`| `  # code to execute if all conditions are false` | `{`                                        |
|                   | `}`                                          |                                           | `  // code to execute if all conditions are false` |
|                   |                                              |                                           | `}`                                        |
| **Example**       | `if (x > 10) {`                              | `if x > 10:`                              | `if (x > 10)`                              |
|                   | `  console.log("x is greater than 10");`     | `  print("x is greater than 10")`         | `{`                                        |
|                   | `} else if (x > 5) {`                        | `elif x > 5:`                             | `  Console.WriteLine("x is greater than 10");`|
|                   | `  console.log("x is greater than 5");`      | `  print("x is greater than 5")`          | `}`                                        |
|                   | `} else {`                                   | `else:`                                   | `else if (x > 5)`                          |
|                   | `  console.log("x is 5 or less");`           | `  print("x is 5 or less")`               | `{`                                        |
|                   | `}`                                          |                                           | `  Console.WriteLine("x is greater than 5");` |
|                   |                                              |                                           | `}`                                        |
|                   |                                              |                                           | `else`                                     |
|                   |                                              |                                           | `{`                                        |
|                   |                                              |                                           | `  Console.WriteLine("x is 5 or less");`   |
|                   |                                              |                                           | `}`                                        |

[Back to top](#table-of-contents)

## Loop

| Loop Type     | JavaScript                          | Python                             | C#                                   |
|---------------|-------------------------------------|------------------------------------|--------------------------------------|
| **For Loop**  | `for (let i = 0; i < 5; i++) {`     | `for i in range(5):`               | `for (int i = 0; i < 5; i++) {`      |
|               | `  console.log(i);`                 | `  print(i)`                       | `  Console.WriteLine(i);`            |
|               | `}`                                 |                                    | `}`                                  |
| **While Loop**| `let i = 0;`                        | `i = 0`                            | `int i = 0;`                         |
|               | `while (i < 5) {`                   | `while i < 5:`                     | `while (i < 5) {`                    |
|               | `  console.log(i);`                 | `  print(i)`                       | `  Console.WriteLine(i);`            |
|               | `  i++;`                            | `  i += 1`                         | `  i++;`                             |
|               | `}`                                 |                                    | `}`                                  |
| **Do-While**  | `let i = 0;`                        | No direct equivalent               | `int i = 0;`                         |
|               | `do {`                              |                                    | `do {`                               |
|               | `  console.log(i);`                 |                                    | `  Console.WriteLine(i);`            |
|               | `  i++;`                            |                                    | `  i++;`                             |
|               | `} while (i < 5);`                  |                                    | `} while (i < 5);`                   |
| **For-Each**  | `let arr = [1, 2, 3];`              | `arr = [1, 2, 3]`                  | `int[] arr = {1, 2, 3};`             |
|               | `arr.forEach(function(item) {`      | `for item in arr:`                 | `foreach (int item in arr) {`        |
|               | `  console.log(item);`              | `  print(item)`                    | `  Console.WriteLine(item);`         |
|               | `});`                               |                                    | `}`                                  |

[Back to top](#table-of-contents)

## Switch 

| Feature           | JavaScript                                                | Python (if-elif-else)                             | C#                                                        |
|-------------------|-----------------------------------------------------------|--------------------------------------------------|-----------------------------------------------------------|
| **Basic Syntax**  | `switch (expression) {`                                   | `if expression == value1:`                        | `switch (expression) {`                                   |
|                   | `  case value1:`                                          | `  # code for value1`                             | `  case value1:`                                          |
|                   | `    // code for value1`                                  | `elif expression == value2:`                      | `    // code for value1`                                  |
|                   | `    break;`                                              | `  # code for value2`                             | `    break;`                                              |
|                   | `  case value2:`                                          | `else:`                                           | `  case value2:`                                          |
|                   | `    // code for value2`                                  | `  # default code`                                | `    // code for value2`                                  |
|                   | `    break;`                                              |                                                  | `    break;`                                              |
|                   | `  default:`                                              |                                                  | `  default:`                                              |
|                   | `    // default code`                                     |                                                  | `    // default code`                                     |
|                   | `}`                                                       |                                                  | `    break;`                                              |
|                   |                                                           |                                                  | `}`                                                       |
| **Example**       | `switch (day) {`                                          | `day = "Monday"`                                  | `switch (day) {`                                          |
|                   | `  case "Monday":`                                        | `if day == "Monday":`                             | `  case "Monday":`                                        |
|                   | `    console.log("Start of the work week");`              | `  print("Start of the work week")`               | `    Console.WriteLine("Start of the work week");`        |
|                   | `    break;`                                              | `elif day == "Friday":`                           | `    break;`                                              |
|                   | `  case "Friday":`                                        | `  print("End of the work week")`                 | `  case "Friday":`                                        |
|                   | `    console.log("End of the work week");`                | `else:`                                           | `    Console.WriteLine("End of the work week");`          |
|                   | `    break;`                                              | `  print("Weekend!")`                             | `    break;`                                              |
|                   | `  default:`                                              |                                                  | `  default:`                                              |
|                   | `    console.log("Weekend!");`                            |                                                  | `    Console.WriteLine("Weekend!");`                      |
|                   | `}`                                                       |                                                  | `    break;`                                              |
|                   |                                                           |                                                  | `}`                                                       |
[Back to top](#table-of-contents)

## function/method syntax


| Feature               | JavaScript                                | Python                                | C#                                      |
|-----------------------|-------------------------------------------|---------------------------------------|-----------------------------------------|
| **Function Declaration** | `function name(parameters) {`          | `def name(parameters):`               | `void Name(parameters) {`               |
|                       | `  // code to execute`                    | `  # code to execute`                 | `  // code to execute`                  |
|                       | `}`                                       |                                       | `}`                                     |
| **Function Call**     | `name(arguments);`                        | `name(arguments)`                     | `Name(arguments);`                      |
| **Return Statement**  | `function name(parameters) {`             | `def name(parameters):`               | `int Name(parameters) {`                |
|                       | `  return value;`                         | `  return value`                      | `  return value;`                       |
|                       | `}`                                       |                                       | `}`                                     |
| **Parameters**        | `function greet(name) {`                  | `def greet(name):`                    | `void Greet(string name) {`             |
|                       | `  console.log("Hello " + name);`         | `  print("Hello " + name)`            | `  Console.WriteLine("Hello " + name);` |
|                       | `}`                                       |                                       | `}`                                     |
| **Default Parameters** | `function greet(name = "Guest") {`       | `def greet(name="Guest"):`            | `void Greet(string name = "Guest") {`   |
|                       | `  console.log("Hello " + name);`         | `  print("Hello " + name)`            | `  Console.WriteLine("Hello " + name);` |
|                       | `}`                                       |                                       | `}`                                     |
| **Example**           | `function add(a, b) {`                    | `def add(a, b):`                      | `int Add(int a, int b) {`               |
|                       | `  return a + b;`                         | `  return a + b`                      | `  return a + b;`                       |
|                       | `}`                                       |                                       | `}`                                     |
|                       | `console.log(add(2, 3));`                 | `print(add(2, 3))`                    | `Console.WriteLine(Add(2, 3));`         |

[Back to top](#table-of-contents)
## Array and List
**Collections**: Data structures that store multiple values, such as arrays, lists, sets, and dictionaries (or maps).

- JavaScript
    - Array: Used to store multiple values in a single variable. Can contain elements of different types.
    - Object: Used to store collections of key-value pairs. Keys are strings, and values can be of any type.
- Python
    - List: An ordered collection of items which can be of any type. Lists are mutable.
    - Set: An unordered collection of unique items. Sets are mutable.
    - Dictionary: A collection of key-value pairs. Keys are unique and must be immutable, and values can be of any type. Dictionaries are mutable.
- C#
    - Array: Used to store a fixed-size sequential collection of elements of the same type.
    - List: A dynamic array that can grow as needed. Elements must be of the same type.

| Feature              | JavaScript Array                | JavaScript Object                   | Python List                          | Python Set                           | Python Dictionary                   | C# Array                            | C# List                             |
|----------------------|---------------------------------|-------------------------------------|--------------------------------------|-------------------------------------|-------------------------------------|-------------------------------------|-------------------------------------|
| **Declaration**      | `let arr = [1, 2, 3];`          | `let obj = {key1: 'value1'};`       | `list = [1, 2, 3]`                   | `set_var = {1, 2, 3}`               | `dict = {'key1': 'value1'}`         | `int[] arr = {1, 2, 3};`            | `List<int> list = new List<int>{1, 2, 3};` |
| **Accessing Elements** | `arr[0]`                       | `obj.key1`                          | `list[0]`                            | N/A                                 | `dict['key1']`                      | `arr[0]`                            | `list[0]`                           |
| **Modifying Elements** | `arr[0] = 10;`                 | `obj.key1 = 'value2';`              | `list[0] = 10`                       | N/A                                 | `dict['key1'] = 'value2'`           | `arr[0] = 10;`                      | `list[0] = 10;`                     |
| **Length/Size**      | `arr.length`                    | `Object.keys(obj).length`           | `len(list)`                          | `len(set_var)`                      | `len(dict)`                         | `arr.Length`                        | `list.Count`                        |
| **Adding Elements**  | `arr.push(4);`                  | `obj['key2'] = 'value2';`           | `list.append(4)`                     | `set_var.add(4)`                    | `dict['key2'] = 'value2'`           | N/A                                 | `list.Add(4);`                      |
| **Removing Elements** | `arr.pop();`                    | `delete obj.key1;`                  | `list.pop()`                         | `set_var.remove(3)`                 | `del dict['key1']`                  | N/A                                 | `list.Remove(4);`                   |
| **Iterating Elements** | `for (let i of arr) { ... }`   | `for (let key in obj) { ... }`      | `for i in list: ...`                 | `for i in set_var: ...`             | `for key, value in dict.items(): ...` | `foreach (int i in arr) { ... }`    | `foreach (int i in list) { ... }`   |
| **Uniqueness**       | No                              | Keys are unique                     | No                                   | Yes                                 | Keys are unique                     | No                                  | No                                  |
| **Ordering**         | Ordered                         | Unordered                           | Ordered                              | Unordered                           | Unordered                           | Ordered                             | Ordered                             |
| **Mutability**       | Mutable                         | Mutable                             | Mutable                              | Mutable                             | Mutable                             | Fixed-size                          | Mutable                             |
| **Example**          | `let arr = [1, 2, 3];`          | `let obj = {key1: 'value1'};`       | `list = [1, 2, 3]`                   | `set_var = {1, 2, 3}`               | `dict = {'key1': 'value1'}`         | `int[] arr = {1, 2, 3};`            | `List<int> list = new List<int>{1, 2, 3};` |
|                      | `arr.push(4);`                  | `obj['key2'] = 'value2';`           | `list.append(4)`                     | `set_var.add(4)`                    | `dict['key2'] = 'value2'`           | N/A                                 | `list.Add(4);`                      |
|                      | `for (let i of arr) { ... }`    | `for (let key in obj) { ... }`      | `for i in list: ...`                 | `for i in set_var: ...`             | `for key, value in dict.items(): ...` | `foreach (int i in arr) { ... }`    | `foreach (int i in list) { ... }`   |


[Back to top](#table-of-contents)