# Javascript - TLDR;

<p align="center">
<img align="center" alt="JavaScript" width="96px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
</p>

<p align="center">	
Made as a personal project to gather and organize concepts for learning.
</p>

Guide:   

🟢 Easier to grasp concepts

🟡 Probably best to feel comfortable with green topics prior

🔴 Probably best to feel comfortable with yellow topics prior



## Table of Contents

0. ## **[Fundamentals](#0-fundamentals)**
    + 0.1 **[🟢 Primitive data types](#01-primitive-data-types)**
    + 0.2 **[🟢 Console.log](#02-consolelog)**
    + 0.3 **[🟢 Variable declarations & definitions](#03-variables)**
    + 0.4 **[🟢 Variable types - const / let / var](#04-variable-declarations---const--let--var)**
    + 0.5 **[🟢 Operators - assignment / comparison / logical / unary](#05-operators-assignment--comparison--logical--unary)**
    + 0.6 **[🟢 = vs == vs === (assignment & equality)](#06--vs--vs--assignment--equality)**
    + 0.7 **[🟢 Typeof operator](#07-typeof-operator)**
    + 0.8 **[🟡 Type conversion](#08-type-conversion)**
    + 0.9 **[🔴 Template literals - \`${name}`](#09-template-literals---name)**
 
 
 1. ## **[Strings](#1-Strings)**
    + 1.1 **[🟢 length / charAt / charCodeAt](#11-length--charat--charcodeat)**
    + 1.2 **[🟢 concat / split / repeat](#12-concat--split--repeat)**
    + 1.3 **[🟢 search / replace](#13-search--replace)**
    + 1.4 **[🟢 slice / substring / substr](#14-slice--substring--substr)**
    + 1.5 **[🟢 toUpperCase / toLowerCase](#15-touppercase--tolowercase)**
    + 1.6 **[🟢 indexOf / lastIndexOf](#16-indexof--lastindexof)**
    + 1.7 **[🟢 trim / padStart / padEnd](#17-trim--padstart--padend)**
    + 1.8 **[🟢 startsWith / endsWith / includes](#18-startswith--endswith--includes)**
    + 1.9 **[🟡 Chaining methods](#19-chaining-methods)**

2. ## **[Control flow](#2-control-flow)**
    + 2.1 **[🟢 For loops (for/for in/for of/forEach/backwards for)](#21-for-loops-forfor-infor-offoreachbackwards-for)**
    + 2.2 **[🟢 While loops (while & do-while)](#22-while-loops-while--do-while)**
    + 2.3 **[🟢 If else statement (conditionals)](#23-if-else-statement-conditionals)**
    + 2.4 **[🟡 Ternary if statements (conditionals)](#24-ternary-if-statements-conditionals)**
    + 2.5 **[🟢 Return (conditionals)](#25-return-conditionals)**
    + 2.6 **[🟢 Break (conditionals)](#26-break-conditionals)**
    + 2.7 **[🟢 Continue (conditionals)](#27-continue-conditionals)**
    + 2.8 **[🟢 Break vs continue vs return (conditionals)](#28-break-vs-continue-vs-return-conditionals)**
    + 2.9 **[🟡 Switch statements (conditionals)](#29-switch-statements-conditionals)**


3. ## **[Functions](#3-Functions)**
    + 3.1 **[🟢 Higher order functions & first class citizenship](#31-higher-order-functions---first-class-citizenship)**
    + 3.2 **[🟢 Function declarations (traditional functions)](#32-function-declarations-traditional-functions)**
    + 3.3 **[🟢 Function expressions](#33-function-expressions)**
    + 3.4 **[🟢 Arrow functions & concise arrow functions](#34-arrow-functions--concise-arrow-functions)**
    + 3.5 **[🟢 Anonymous functions](#35-anonymous-functions)**
    + 3.6 **[🟡 Immediately invoked function expressions (IIFE)](#36-immediately-invoked-function-expressions-iife)**
    + 3.7 **[🟡 Recursive functions](#37-recursive-functions)**
    + 3.8 **[🔴 Callback functions](#38-callback-functions)**
    + 3.9 **[🔴 Asynchronous functions](#39-asynchronous-functions)**


4. ## **[Scope](#4-scope)**
    + 4.1 **[🟢 Global scope variables](#41-global-scope-variables)**
    + 4.2 **[🟢 Local scope variables](#42-local-scope-variables)**
    + 4.3 **[🟢 Block scope](#43-block-scope)**
    + 4.4 **[🟢 Function scope](#44-function-scope)**
    + 4.5 **[🟡 Scope chain](#45-scope-chain)**
    + 4.6 **[🟡 Hoisting](#46-hoisting)**
    + 4.7 **[🔴 Lexical scope](#47-lexical-scope)**
    + 4.8 **[🔴 Module scope](#48-module-scope)**
    + 4.9 **[🔴 Closures](#49-closures)**

5. ## **[Arrays](#5-arrays)**
    + 5.1 **[🟢 Console.table](#51-consoletable)**
    + 5.2 **[🟢 push / pop / shift / unshift](#52-push--pop--shift--unshift)**
    + 5.3 **[🟢 length / fill / toString / sort / reverse](#53-length--fill--tostring--sort--reverse)**
    + 5.4 **[🟢 concat / join / slice / splice](#54-concat--join--slice--splice)**
    + 5.5 **[🟢 find / findIndex / indexOf / lastIndexOf](#55-find--findindex--indexof--lastindexof)**
    + 5.6 **[🟢 includes / some / every / forEach](#56-includes--some--every--foreach)**
    + 5.7 **[🔴 filter / map / reduce](#57-filter--map--reduce)**
    + 5.8 **[🟡 Two-dimensional (2D) arrays](#58-two-dimensional-2d-arrays)**
    + 5.9 **[🔴 Three-dimensional (3D) arrays](#59-three-dimensional-3d-arrays)**
6. ## **[Objects](#6-objects)**
    + 6.1 **[🟢 Object declaration & definition](#61-object-declaration--definition)**
    + 6.2 **[🟢 Object properties](#62-object-properties)**
    + 6.3 **[🟢 Object manipulation](#63-object-manipulation)**
    + 6.4 **[🟢 Object methods](#64-object-methods)**
    + 6.5 **[🟢 Object destructuring ](#65-object-destructuring)**
    + 6.6 **[🟡 Core (built-in) objects](#66-core-built-in-objects)**
    + 6.7 **[🟡 Primitive vs non-primitive](#67-primitive-vs-non-primitive)**
    + 6.8 **[🔴 Primitive wrappers](#68-primitive-wrappers)**
    + 6.9 **[🔴 Value vs reference](#69-value-vs-reference)**

7. ## **[Object-oriented](#7-object-oriented)**
    + 7.1 **[🟡 This](#71-this)**
    + 7.2 **[🟡 Constructors & new](#72-constructors--new)**
    + 7.3 **[🟡 Constructors vs literals](#73-constructors-vs-literals)**
    + 7.4 **[🟡 Factories](#74-factories)**
    + 7.5 **[🔴 Classes (Constructor 2.0)](#75-classes-constructor-20)**
    + 7.6 **[🔴 Class inheritance & extends](#76-class-inheritance--extends)**
    + 7.7 **[🔴 Prototype model](#77-prototype-model)**
    + 7.8 **[🔴 Prototype chain & inheritance](#78-prototype-chain--inheritance)**
    + 7.9 **[🔴 Overview of OOP - prototype-based vs class-based](#79-overview-of-oop---prototype-based-vs-class-based)**

8. ## **[Data structures & memory](#8-data-structures--memory)**
    + 8.1 **[🟢 Stack & queue](#81-stack--queue)**
    + 8.2 **[🟡 Arrays - indexed & associative](#82-arrays---indexed--associative)**
    + 8.3 **[🟡 Linked lists - array vs linked list](#83-linked-lists---array-vs-linked-list)**
    + 8.4 **[🔴 Trees](#84-trees)**
    + 8.5 **[🔴 Graphs](#85-graphs)**
    + 8.6 **[🔴 Hash tables (hash maps)](#86-hash-tables-hash-maps-)**
    + 8.7 **[🔴 Javascript memory model - value vs reference under the hood](#87-javascript-memory-model---value-vs-reference-under-the-hood)**
    + 8.8 **[🔴 Javascript memory model - call stack & heap](#88-javascript-memory-model---call-stack--heap)**
    + 8.9 **[🔴 Defining & interpreting change (in memory)](#89-defining--interpreting-change-in-memory)**



9. ## **[Algorithms & time complexity](#9-algorithms--time-complexity)**
    + 9.1 **[🔴 Big-O notation](#91-big-o-notation)**
    + 9.2 **[🔴 CRUD operations on data structures](#92-crud-operations-on-data-structures)**
    + 9.3 **[🟡 Sorting algorithms](#93-sorting-algorithms)**
    + 9.4 **[🔴 Quick sort](#94-quick-sort)**
    + 9.5 **[🔴 Merge sort](#95-merge-sort)**
    + 9.6 **[🔴 Insertion sort](#96-insertion-sort)**
    + 9.7 **[🟡 Search algorithms](#97-search-algorithms)**
    + 9.8 **[🔴 Linear search](#98-linear-search)**
    + 9.9 **[🔴 Binary search](#99-binary-search)**

**[⬆ Back to Top](#table-of-contents)**

# 0 Fundamentals 

JavaScript, often abbreviated as JS, is a programming language that is often described as some variation of: 

- **High-level** - is the abstraction the language provides over the machine’s bare-metal hardware. JavaScript is considered high-level because it does not require direct interaction with the operating system, hardware.

- **Dynamically typed** - check the variable types and look for type errors during runtime.

- **Weakly typed** - make conversions between unrelated data types implicitly.

- **Interpreted** (or **just-in-time compiled**) - source code is converted to bytecode and executed at runtime, as opposed to being compiled to a machine code binary (ones and zeros) at build time.

- **Single-threaded** - means that JS can only run one instruction at a time, even if your CPU has multiple cores and available threads.

- **Multi-paradigm** - can be used for procedural, declarative (functional) or imperative (object-oriented) programming styles.

---

### High-level vs low-level

Comparison of the differences of high level languages vs low level languages:

![](https://894532.smushcdn.com/2098219/wp-content/uploads/2020/02/codinglanguage2.jpeg?lossy=0&strip=1&webp=1)

---

### Dynamic vs static & strong vs weak

**Javascript is a dynamically typed language.**

* `Statically typed` languages check the types and look for type errors during compile time.

* `Dynamically typed` languages check the types and look for type errors during runtime.

> Another way to think about it: static typing means checking the types before running the program; dynamic typing means checking the types while running the program.

**JavaScript is also a weakly typed language.**

* `Weakly typed` languages make conversions between unrelated types implicitly.

* `Strongly typed` one typically disallow implicit conversions between unrelated types.

> It has a notion of types, but it's relaxed about them, and can treat values somewhat arbitrary. The stronger the typing system is — the stricter the rules are.

![](https://i.imgur.com/TBBbpCG.jpg)

---

### Compiled vs. Interpreted

Compiled vs Interpreted Programming: 

- In a **compiled language**, the target machine directly translates the program. 

- In an **interpreted language**, the source code is not directly translated by the target machine. Instead, a different program, aka the interpreter, reads and executes the code.

![](https://miro.medium.com/max/603/1*oUPhgu1G22fxhl8L6g3YCg.png)

**[⬆ Back to Top](#fundamentals)**

## 0.1 Primitive data types
 

In programming, data types is an important concept.

To be able to operate on variables, it is important to know something about the type.


JavaScript variables can hold many data types: numbers, strings, objects and more.

A `primitive` (primitive value, primitive data type) is data that is not an object and has no methods:

| Type          | Description   |
|:-------------:|---------------| 
| **number**     | Integer and floating-point(decimal) numbers |
| **boolean**    | True and False      |
| **string** | "Sequence of character or numbers within quotes"     |
| **symbol**     | A unique and immutable data type and may be used as an identifier for object properties |
| **null**    | Explicity set a variable with no value      |
| **undefined** | Variables that have not yet been defined     |

```javascript
// Primitive data types
let foo = 42;    // foo is now a number
foo = 'bar'; // foo is now a string
foo = true;  // foo is now a boolean
foo = 'hello there'; // foo is now a string again
```


**[⬆ Back to Top](#fundamentals)**

## 0.2 Console.log

`console.log()` is a console method known as log() that outputs a message to the console.

The console is also useful for testing purposes.

```javascript
// Console.log
console.log(24); // 24
console.log('Hello'); // 'Hello'
```

```js
// Console.log
let a = 2;
console.log(a); // 2
```


**[⬆ Back to Top](#fundamentals)**

## 0.3 Variables

`Variables` are containers for storing data values. It is a named reference to a value.

That way an unpredictable value can be accessed through a predetermined name.

We can declare a variable using the `let` keyword:

```js
// Variables
let x = 5; // assign value of 5 to variable x
let y = 6; // assign value of 6 to variable y
let sum = x + y; // assign the sum of x and y as variable sum

console.log(x); // 5
console.log(y); // 6
console.log(sum); // 11
```

**[⬆ Back to Top](#fundamentals)**

## 0.4 Variable declarations - const / let / var

`let` - Newer way of declaring a variable, as of 2015.

`const` The value of a constant can't be changed through reassignment, and it can't be redeclared.

`var` - Older way of declaring a variable.

> More on scopes in the upcoming scope chapter. For now use `let`.

```javascript
// const, let & var variable declarations
let name = 'Tom';
const age = 25;
var fruit = 'apple'

console.log(name); // 'Tom'
console.log(age); // 25
console.log(fruit); // 'apple'
```


**[⬆ Back to Top](#fundamentals)**



## 0.5 Operators (assignment / comparison / logical / unary)

An **operator** in a programming language is a symbol that tells the compiler or interpreter to perform specific mathematical, relational or logical operation and produce a final result.

### Assignement

| Operator        | Meaning           | Description  |
|:-------------:|:-------------:| -----|
| a `=` b    | a = b | Assigns the value of b to a. |
| a `+=` b   |a = a + b  |   Assigns the result of a plus b to a.    |
|  a `-=` b  |   a = a - b   | Assigns the result of a minus b to a.  |
|a `*=` b    | a = a * b      |Assigns the result of a times b to a.|
| a `/=` b |a = a / b |Assigns the result of a divided by b to a. |
| a `%=` b | a = a % b | Assigns the result of a modulo b to a. |	
| a `&=` b | a = a & b | Assigns the result of a AND b to a. |
| a `\|=` b | a = a \| b | Assigns the result of a OR b to a. |
| a `^=` b | a = a ^ b | Assigns the result of a XOR b to a. |
| a `<<=` b |a = a << b | Assigns the result of a shifted left by b to a. |
| a `>>=` b |a = a >> b |Assigns the result of a shifted right (sign preserved) by b to a.|
| a `>>>=` b | a = a >>> b | Assigns the result of a shifted right by b to a. |
		
### Comparison

| Operator | Meaning |
|:------:| ----------- |
| `<`   | less than |
| `>`   | greater than |
| `<=`  | 	less than or equal to |
| `>=`   | greater than or equal to |
| `==`   | equal to |
| `!=`   | 	not equal to |

### Logical

| Logic | Operator | Description |
|:------:|:-----------:|----------- |
| NOT    | `!` |negates a boolean value. The (!!) converts a value into its real boolean value|
| AND   | `&&` | applied to two Boolean values and returns true if both values are true|
| OR   | `\|\|` |applied to two Boolean values and returns true if one of the operands is true |


### Unary

| Operator | Name | Meaning |
|:------:| ----------- |------|
| `+`  | Unary plus | convert an operand into a number|
| `-`  | Unary minus |convert an operand into a number and negate the value after that|
| `++`  | prefix / postfix increments |add one to its operand |
| `--`   | prefix / postfix decrements  |subtract one from its operand |

**[⬆ Back to Top](#fundamentals)**

## 0.6 = vs == vs === (assignment & equality)

| Operator | Name | Meaning |
| :------: |:-----------:|------|
| `=`  | Assignment operator| assigns a value to a variable|
| `==`  | Equality operator |equal to (equality)|
| `===`  | Identity operator|equal value and equal type (strict equality) |
| `!=`  | Inequality operator |not equal (equality)|
| `!==`  | Nonidentity operator|	not equal value or not equal type (strict equality) |


```javascript
// Assignement
let a = 10;
let b = 20;
b = 'abc'
```
```javascript
// Equality
console.log(5 == 5) // true
console.log(5 == '5') // true

console.log(5 != 5) // false
console.log(5 != 99) // true
console.log(5 != '5') // false
```
```javascript
// Strict equality - compares types as well
console.log(5 === 5) // true
console.log(5 === '5') // false

console.log(5 !== 5) // false
console.log(5 !== 99) // true
console.log(5 !== '5') // true
```

**[⬆ Back to Top](#fundamentals)**

## 0.7 Typeof operator

`typeof` is an operator that is used to get the data type (returns a string) of its operand.

You can use it to find the type of a JavaScript variable.

The typeof operator returns the type of a variable or an expression:

```javascript
// Typeof
console.log(typeof ('abc')) // string
console.log(typeof (123)) // number
console.log(typeof ([])) // object
console.log(typeof ({})) // object
```

```javascript
// Typeof
let x = 24;
let y = 'hello';

console.log(typeof (x)) // number
console.log(typeof (y)) // string
```

**[⬆ Back to Top](#fundamentals)**

## 0.8 Type conversion

Type conversion is the action of changing one data type to another either implicitly or explicitly.

* **Implicit Conversion** - In certain situations, JS automatically converts one data type to another (to the right type).
* **Explicit Conversion** - Manually converting one data type to another

```javascript
// Numeric string used with + gives string type
// when a number is added to a string, JS converts the number to a string before concatenation.
let result;

result = '3' + 2; 
console.log(result) // "32"

result = '3' + true; 
console.log(result); // "3true"

console.log(typeof(3 + '')) // string
```

```javascript
// String to number with javascript's built-in Number function
result = Number('324');
console.log(result); // 324
```

**[⬆ Back to Top](#fundamentals)**

## 0.9 Template literals - `${name}`


**Template literals** - (template strings) allow you to use strings or embedded expressions in the form of a string. 

They are enclosed in backticks ``.

Template literals can contain placeholders. These are indicated by the dollar sign and curly braces (${expression}).

```javascript
// Template literal - useful for inserting dynamic values into strings
let name = 'Tom';

console.log(`Hi, ${name}`); // "Hi, Tom"
```

```javascript
// Template literal
let number = 10;

console.log(`${number * number}`); // 100
```

**[⬆ Back to Top](#fundamentals)**

# 1 Strings

```js
// Declaring a string
let myString = 'Hello, world!'
```

JavaScript strings are used for storing and manipulating text. They are useful for holding data that can be represented in text form. 

Some of the most-used operations on strings are to check their length, to build and concatenate them using the `+` and `+=` string operators, checking for the existence or location of substrings with the `indexOf()` method, or extracting substrings with the `substring()` method.

![](https://codingbat.com/doc/string1.png)
> Every character in a string has a unique positition

---

The outputs of methods can be anything from numeric, string, boolean, array, object. 

The below list shows some of the methods and their output types:

![](https://miro.medium.com/max/507/1*-pkrW0BDyLr7xu6TTjcRcw.png)

**[⬆ Back to Top](#strings)**

## 1.1 length / charAt / charCodeAt

`length` is a property that returns the length of a string (number of characters).

`charAt()` is a string method returns the character at the specified index in a string.

`charCodeAt()` is a string method which returns an integer between 0 and 65535 representing the UTF-16 code unit at the given index.

```javascript
// .length
let txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
let len = txt.length;
console.log(len) // 26

// Please note that str.length is a numeric property, not a function. 
// There is no need to add parenthesis after it.
```

```javascript
// .charAt()
const sentence = 'The quick brown fox jumps over the lazy dog.';
const index = 4;

console.log(`The character at index ${index} is ${sentence.charAt(index)}`); // "The character at index 4 is q"
```

```javascript
// .charCodeAt()
// The Unicode value for A is 65
'ABC'.charCodeAt(0)  // 65


const sentence = 'The quick brown fox jumps over the lazy dog.';
const index = 4;

console.log(`The character code ${sentence.charCodeAt(index)} is equal to ${sentence.charAt(index)}`);
// "The character code 113 is equal to q"
```

**[⬆ Back to Top](#strings)**

## 1.2 concat / split / repeat

`concat()` is a string method used to join two or more strings. 

> This method does not change the existing strings, but returns a new string containing the text of the joined strings.

`split()` is a string method which divides a string into an ordered list of substrings, puts these substrings into an array, and returns the array.  

> The division is done by searching for a pattern; where the pattern is provided as the first parameter in the method's call.  

`repeat()` returns a new string with a specified number of copies of the string it was called on.

---

```javascript
// Syntax of concat()
// string1, string2, ..., stringX - Required. The strings to be joined

string.concat(string1, string2, ..., stringX) // returns a new string
```


```javascript
// .concat()
let str1 = "Hello ";
let str2 = "world!";
let str3 = " Have a nice day!";

let res = str1.concat(str2, str3); // 'Hello world! Have a nice day!'
```
---


```javascript
// Syntax of split()
// separator - Optional. Where each split should occur.
// limit - Optional. Limit on the number of substrings to be included in the array

string.split(separator, limit) // returns new array
```

```javascript
// .split()
let str = "How are you?";
let res = str.split();
console.log(res) // [ 'How are you?' ]

res = str.split("");
console.log(res); // ['H', 'o', 'w', ' ', 'a', 'r', 'e', ' ', 'y', 'o', 'u', '?' ]

res = str.split(" ", 2);
console.log(res); // [ 'How', 'are' ]

res = str.split("o"); 
console.log(res); // [ 'H', 'w are y', 'u?' ]
```
---


```javascript
// Syntax of repeat()
// count - Required. The number of times to repeat the string

string.repeat(count) // returns new array, does not change the original string
```

```javascript
// .repeat()
let str = "Hello world!";
str.repeat(2); // new value of repeat is not assigned with below, only returned
str2 = str.repeat(2); // // assign recieved value of repeat to variable

console.log(str) // 'Hello world!'
console.log(str2) // 'Hello world!Hello world!'
```

**[⬆ Back to Top](#strings)**

## 1.3 search / replace

`search()` is a string method that searches a string for a specified value, and returns the position of the match.

`replace()` is a method that searches a string for a specified value, and replaces it with another specified value. 
> It can also accept a regular expression as an argument as well as a function, and returns a new string. The original string is left unchanged.

>**Note**: If you are replacing a value (and not a regular expression), only the first instance of the value will be replaced. To replace all occurrences of a specified value, use the **global (g) modifier** (see below examples).

---

```javascript
// Syntax of search()
// searchvalue - Required and case-sensitive. Required. The string to search for

string.search(searchvalue) // returns a number, -1 if no match is found
```

```javascript
// .search()
let str = "Mr. Blue has a blue house"
let n = str.search("blue");

console.log(n) // 15
```
---



```javascript
// Syntax of replace()
// searchvalue - Required. The value to search for
// newvalue - Required. The value to replace the search value with

string.replace(searchvalue, newvalue) // returns a new string
```



```javascript
// .replace()

// Perform a global replacement:
let str = "Mr Blue has a blue house and a blue car";
let res = str.replace(/blue/g, "red");

console.log(res) // 'Mr Blue has a red house and a red car'
```

```javascript
// .replace()

// Perform a global, case-insensitive replacement:
let str = "Mr Blue has a blue house and a blue car";
let res = str.replace(/blue/gi, "red");

console.log(res) // 'Mr red has a red house and a red car'
```

```javascript
// .replace()

// Using a function to return the replacement text:
let str = "Mr Blue has a blue house and a blue car";
let res = str.replace(/blue|house|car/gi, function (x) {
    return x.toUpperCase();
  });

console.log(res) // 'Mr BLUE has a BLUE HOUSE and a BLUE CAR'
```


**[⬆ Back to Top](#strings)**

## 1.4 slice / substring / substr

`slice()` is a string method that extracts a section of a string and returns it as a new string, without modifying the original string. **Note:** `slice()` is also an array method.

`substring()` returns the part of the string between the start and end indexes, or to the end of the string.

`substr()` extracts parts of a string, beginning at the character at the specified position, and returns the specified number of characters. 

---

```javascript
// Syntax of slice()
// start - Required. The position where to begin the extraction
// end - Optional. Default to end of string. The position up to, but not including end

string.slice(start, end) // returns a new string
```

```javascript
// Extract the whole string:
let str = "Hello world!";

let res = str.slice(0); // 'Hello world!'

res = str.slice(3); // 'lo world!'
res = str.slice(3, 8); // 'lo wo'
res = str.slice(0, 1); // 'H'
res = str.slice(-1); // '!'
res = str.slice(6, -1); // 'world'
res = str.slice(-6); // 'world!'
```

---

```javascript
// Syntax of substring()
// start - Required. The position where to start the extraction.
// end - Optional. Default to end of string. The position up to, but not including end

string.substring(start, end) // returns a new String containing the extracted characters
```

```javascript
// .substring()
let anyString = 'Mozilla'

console.log(anyString.substring(0, 1)) // 'M'
console.log(anyString.substring(1, 0)) 'M'

console.log(anyString.substring(0, 6)) // 'Mozill'

console.log(anyString.substring(4)) // 'lla'
console.log(anyString.substring(4, 7)) // 'lla'
console.log(anyString.substring(7, 4)) // 'lla'

console.log(anyString.substring(0, 7)) // 'Mozilla'
console.log(anyString.substring(0, 10)) // 'Mozilla'

console.log(anyString.substring(anyString.length - 1, anyString)) // 'Mozill'

// Extracts the characters in a string between "start" and "end", not including "end" itself.
// If "start" is greater than "end", it will swap the two arguments:
```

---


```javascript
// Syntax of substr()
// start - 	Required. The position where to start the extraction.
// length - Optional. Default to end of string. The position up to, but not including end

string.substr(start, length) // returns a new string
```

```javascript
// .substr()
let aString = 'Mozilla';

console.log(aString.substr(0, 1));   // 'M'
console.log(aString.substr(1, 0));   // ''
console.log(aString.substr(-1, 1));  // 'a'
console.log(aString.substr(1, -1));  // ''
console.log(aString.substr(-3));     // 'lla'
console.log(aString.substr(1));      // 'ozilla'
console.log(aString.substr(-20, 2)); // 'Mo'
console.log(aString.substr(20, 2));  // ''
```

**[⬆ Back to Top](#strings)**

## 1.5 toUpperCase / toLowerCase

The `toUpperCase()` method returns the calling string value converted to uppercase 

The `toLowerCase()` method returns the calling string value converted to lower case.


```javascript
// .toUpperCase()
console.log('alphabet'.toUpperCase()); // 'ALPHABET'
```

```javascript
// .toLowerCase()
console.log('ALPHABET'.toLowerCase()); // 'alphabet'
```

```javascript
// Using a string method doesn't mutate the string
var bar = "baz";

console.log(bar);               // baz
bar.toUpperCase();
console.log(bar);               // baz

bar = bar.toUpperCase();       // BAZ
```


**[⬆ Back to Top](#strings)**

## 1.6 indexOf / lastIndexOf

`indexOf()` is a case sensitive method which returns the position of the first occurrence of a specified value in a string.

`lastIndexOf()` returns the position of the last occurrence of a specified value in a string.

---

```javascript
// Syntax of indexOf()
// searchvalue - Required & case sensitive. The string to search for
// start - Optional. Default 0. At which position to start the search

string.indexOf(searchvalue, start) // returns a number, or -1 if it never occurs
```

```javascript
// .indexOf()
// Find the first occurrence of the letter "e" in a string:
let str = "Hello world, welcome to the universe.";

let n = str.indexOf("e"); // 1
let n2 = str.indexOf("e", 5); // 14

// return boolean
'Blue Whale'.indexOf('Blue') !== -1  // true
'Blue Whale'.indexOf('Bloe') !== -1  // false
```

---



```javascript
// Syntax of lastIndexOf()
// searchvalue - Required. The string to search for
// start - Optional. Default is length of string. Position to start the search (searching backwards). 

string.lastIndexOf(searchvalue, start) // returns a number (position), or -1 if it never occurs
```

```javascript
// .lastIndexOf()
// Search a string for the last occurrence of "planet":
var str = "Hello planet earth, you are a great planet.";
var n = str.lastIndexOf("planet", 20); // 6
```

**[⬆ Back to Top](#strings)**

## 1.7 trim / padStart / padEnd

`trim()` removes whitespace from both ends of a string. No parameters or arguments.

`trimLeft()` or `trimStart()` removes whitespace from the beginning of a string. No parameters or arguments.

`trimRight()` or `trimEnd()` removes whitespace from the end of a string. No parameters or arguments.


`padStart()` pads the current string from the start (left) with another string (repeated, if needed) until the resulting string reaches the given length.

`padEnd()` method pads the current string from the end with a given string (repeated, if needed) so that the resulting string reaches a given length.

---

```javascript
// .trim()
let str = "       Hello World!        ";

let str1 = str.trim(); // 'Hello World!'
let str2 = str.trimLeft(); // 'Hello World!        '
let str3 = str.trimRight(); // '       Hello World!' 
```

---



```js
// Syntax of padStart() & padEnd()
// length - Required. The length of the resulting string
// string - Optional. The string to pad the current string with

string.padStart(length, string) // returns a new string
string.padEnd(length, string) // returns a new string
```

```javascript
// .padStart()
'abc'.padStart(10);         // "       abc"
'abc'.padStart(10, "foo");  // "foofoofabc"
'abc'.padStart(6,"123465"); // "123abc"
'abc'.padStart(8, "0");     // "00000abc"
'abc'.padStart(1);          // "abc"
```

```javascript
// .padEnd()
'abc'.padEnd(10);          // "abc       "
'abc'.padEnd(10, "foo");   // "abcfoofoof"
'abc'.padEnd(6, "123456"); // "abc123"
'abc'.padEnd(1);           // "abc"
```

**[⬆ Back to Top](#strings)**

## 1.8 startsWith / endsWith / includes

`startsWith()` determines whether a string begins with a specified input, returning true or false as appropriate.

`endsWith()` determines whether a string ends with the characters of a specified string, returning true or false as appropriate.

`includes()` does a case-sensitive search on whether one string may be found within another string, returning true or false.

---

```javascript
// Syntax of startsWith()
// searchvalue - Required. The string to search for
// start - Optional. Default 0. At which position to start the search

string.startsWith(searchvalue, start) // returns a boolean - true or false
```

```javascript
// .startsWith()
let str = 'To be, or not to be, that is the question.'

console.log(str.startsWith('To be'))          // true
console.log(str.startsWith('not to be'))      // false
console.log(str.startsWith('not to be', 10))  // true

var str = "Hello world, welcome to the universe.";
var n = str.startsWith("world", 6); // true
```

---

```javascript
// Syntax of endsWith()
// searchvalue - Required. The string to search for
// start - Optional. Default is length of string. Specify the length of the string to search

string.endsWith(searchvalue, length) // returns a boolean - true or false
```

```javascript
// .endsWith()
let str = 'To be, or not to be, that is the question.'

console.log(str.endsWith('question.'))  // true
console.log(str.endsWith('to be'))      // false
console.log(str.endsWith('to be', 19))  // true

var str = "Hello world, welcome to the universe.";
var n = str.endsWith("world", 11); // true
```

---



```javascript
// Syntax of includes()
// searchvalue - Required & case sensitive. The string to search for
// start - Optional. Default 0. At which position to start the search

string.includes(searchvalue, start) // returns a boolean - true or false
```

```javascript
// .includes()
// case sensitive
'Blue Whale'.includes('blue')  // returns false

var str = "Hello world, welcome to the universe.";
var n = str.includes("world", 12); // false
```

**[⬆ Back to Top](#strings)**


## 1.9 Chaining methods

Method chaining, is a common syntax for invoking multiple method calls . 

Each method returns an object/array/string, allowing the calls to be chained together in a single statement without requiring variables to store the intermediate results.

```js
// Chaining string methods
'war'.toUpperCase().repeat(2) // 'WARWAR'

console.log('war'.toUpperCase().repeat(2)); // 'WARWAR'
```

```js
// Chaining methods
let x = 'abc';
console.log(x); // 'abc'


x = x.toUpperCase().repeat(3);
console.log(x); // 'ABCABCABC'
```

**[⬆ Back to Top](#strings)**

# 2 Control flow

Control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

The three basic types of control structures are:
* **Sequential** (procedural)
* **Selection** (conditional or decision)
* **Iteration** (loop)

They can be combined in any way to solve a specified problem.

![](https://www.wikitechy.com/tutorials/c++/img/c++-images/flow-control.png)

**[⬆ Back to Top](#control-flow)**

## 2.1 For loops (for/for in/for of/forEach/backwards for)

A **For loop (iteration)** is used to repeat a specific block of code a known number of times. 

> When the number of times is not known before hand, we would consider using a "While" loop

| Type          | Description   |
| :------------:|---------------| 
| `for`     | Loops through a block of code a number of times (**fastest, but ugly on the eyes**)|
| `for...in`    | Loops through the properties of an object     |
| `for...of` | Loops through the values of an iterable object (**slowest, but most sugary**)    |
| `.forEach`     | **Array method** which calls a function once for each element in an array, in order. (**fast and designed for functional code**) |
| `for` (but backwards) | Same as regular for loop but backwards (**absolute fastest - but terrible to look at and work with**)    |

```javascript
// For loop
for (i = 0; i < 5; i++) {
    console.log(i); // 0, 1, 2, 3, 4
  }
```

```javascript
// For/in loop - loop through the properties of an object
const person = {fname:"John", lname:"Doe", age:25}; 
let text = "";

for (x in person) {
    console.log(x) // fname, lname, age
    text += person[x] + " ";
    console.log(text) // John, John Doe, John Doe 25
}


// Example #2 with template literals
const object = { a: 1, b: 2, c: 3 };

for (property in object) {
  console.log(`${property}: ${object[property]}`); // a: 1, b: 2, c: 3
}
```

```javascript
// For/of loop - iterate through the values of an array
const tools = ['hammer', 'tape', 'screwdriver'];

for (x of tools) {
  console.log(x) // hammer, tape, screwdriver
}
```

```javascript
// forEach array loop - iterate through all items in an array (may perform a function)
let ranks = ['A', 'B', 'C'];

ranks.forEach(function (letter) {
    console.log(letter); // A, B, C
});
```

```javascript
// Backwards For loop - You evaluate .length only once here, when you declare i.
// Whereas otherwise you evaluate .length each time you increment i.
for(let i = array.length; i--;)
```

**[⬆ Back to Top](#control-flow)**

## 2.2 While loops (while & do-while)


`while` loops through a block of code while a specified condition is true, **checks the condition before iteration of the loop**.

`do/while` also loops through a block of code while a specified condition is true, but **checks the condition after the execution of the statements inside the loop**.

```javascript
// While loop
let count = 0;
while (count < 5) {
    console.log(count); // 0, 1, 2, 3, 4
    count += 1;
    console.log(count); // 1, 2, 3, 4, 5
}
```

```javascript
// Do/While loop
let count = 0;
do {
    console.log(count); // 0, 1, 2, 3, 4
    count++;
    console.log(count); // 1, 2, 3, 4, 5
} while (count < 5);
```
**[⬆ Back to Top](#control-flow)**

## 2.3 If else statement (conditionals)

The `if` statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement can be executed.


![](https://www.alphacodingskills.com/python/img/python-if-else.png)

```javascript
// If-else statement
if (hour < 18) { // conditional - if hour is less than 18
  greeting = "Good day"; // returned for truthy value, if hour is less than 18
} else {
  greeting = "Good evening"; // returned for falsy value, if hour is greater than 18
}
```

```javascript
// If else-if else
if (time < 10) { // If time is less than 10:00, create a "Good morning" greeting 
  greeting = "Good morning";
} else if (time < 20) { // If not less than 10:00, but less than 20:00, create a "Good day" greeting
  greeting = "Good day";
} else { // otherwise create a "Good evening" greeting
  greeting = "Good evening";
}
```

**[⬆ Back to Top](#control-flow)**

## 2.4 Ternary if statements (conditionals)

The conditional ternary operator in JavaScript assigns a value to a variable based on some condition and is the only JavaScript operator that takes three operands.

The ternary operator is a substitute for an `if` statement in which both the `if` and `else` clauses assign different values to the same field, like so:
```javascript
// If else statment
let age = 7;
let kindergarten_eligible;
if (age > 5) {
    kindergarten_eligible = "Old enough";
}
else {
    kindergarten_eligible = "Too young";
}


// Ternary if version of above example
let kindergarten_eligible = (age < 5) ? "Too young" : "Old enough";
```

```javascript
// Conditional ternary operator 
let age = 26;
let beverage = (age >= 21) ? "Beer" : "Juice";
console.log(beverage); // "Beer"
```

```javascript
// Nested ternaries
let bar = 'c';

let foo = (
    bar === 'a' ? 1 : // if 
    bar === 'b' ? 2 : // else if 
    bar === 'c' ? 3 : // else if
    null // else 
  );

console.log(foo) // 3
```

**[⬆ Back to Top](#control-flow)**


## 2.5 Return (conditionals)

The **return** statement is used to terminate the function and also return a value.

```js
// Return statement - terminate loop and return value
for (i = 0; i < 5; i++) {
    if (i === 2) { 
        console.log('inner:' + i + ' condition met')
        return console.log('Broke out of loop');; 
    }
    console.log('outer:' + i)
  }

// outer:0
// outer:1
// inner:2 condition met 
// Condition matches then returns string 'broke out of loop' , no further iterations
```


```javascript
// Return - behaves like break but the return statement ends function execution 
// and specifies a value to be returned to the function caller.
function square(x) {
   return x * x;
}
```

**[⬆ Back to Top](#control-flow)**

## 2.6 Break (conditionals)

The **break** statement "jumps out" of a loop.

```javascript
// Break statement - break out of a loop
for (i = 0; i < 5; i++) {
    if (i === 2) { 
        console.log('inner:' + i + ' condition met')
        break; 
    }
    console.log('outer:' + i)
  }

// outer:0
// outer:1
// inner:2 condition met // condition matches then breaks out of loop, no further iterations
```

**[⬆ Back to Top](#control-flow)**

## 2.7 Continue (conditionals)

The **continue** statement "jumps over" one iteration in the loop and continues with the next iteration in the loop.


```javascript
// Continue statement - jump over one iteration
for (i = 0; i < 5; i++) {
    if (i === 3) {
        console.log('inner:' + i + ' condition met') 
        continue; 
    }
    console.log('outer:' + i)
  }


// outer:0
// outer:1
// inner:2 condition met // continues with loop
// outer:3
// outer:4
```

**[⬆ Back to Top](#control-flow)**

## 2.8 Break vs continue vs return (conditionals)

The **break** statement "jumps out" of a loop.

The **continue** statement "jumps over" one iteration in the loop and continues with the next iteration in the loop.

The **return** statement is used to terminate the function and also return a value.

![](https://i.imgur.com/S6QzTGI.jpg)



**[⬆ Back to Top](#control-flow)**

## 2.9 Switch statements (conditionals)

The `switch` statement is used to perform different actions based on different conditions.

* The `switch` expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* If there is no match, the default code block is executed.

### Switch vs if-else
- A switch statement is usually more efficient than a set of nested `if` statements and for fixed data values.

- `if-else` conditional branches are great for variable conditions that result into a boolean.

![](https://i.imgur.com/45fzRyU.jpg)

**[⬆ Back to Top](#control-flow)**

# 3 Functions



![](https://i.imgur.com/YxoDMbq.jpg)

**Functions** are a "self contained" sequence of statements contained within the body of the function that accomplish a specific task or "encapsulate" a task.

Once a function is **"called" or "invoked"**, it usually takes in some data (**arguments and/or parameters**), process it, and returns some result or even "call" or "invoke" another function. 

In other words functions can also be "called" or "invoked" from the inside of other functions and functions can be passed to other functions as arguments.


![](https://miro.medium.com/max/1000/1*QaaVwrtutJRkO8ugJKJ3bw.jpeg)
> A function recieving a value or another function as an argument and returning a value or another function

Functions can also be referred to as "black boxes" for cases when we don't need to know how they work. Just what is supposed to go into them, and what is supposed to come out of them.

---
## Arguments vs parameters

![](https://i.imgur.com/YkyIzvU.jpg)

Note the difference between parameters and arguments with different explanations: 

* **Arguments are passed while parameters are recieved**.

* **The argument goes into the parameter and that argument is the value of the parameter**.

* **Arguments** are the actual values passed to the function and the **parameters** then initialize those same values from the supplied arguments.

* a **parameter** is one or more variables inside the declaration of a function.

---

### Function types overview
| Type           | Hoisted?      | 
|:-------------:|:--------------:|
| **Function Declaration** | **Yes** |
| **Function Expression** | No |
| **Arrow Function Expression**  | No |
| **Concise Arrow Function Expression** | No |
| **Anonymous Function** | No |
| **Callback Function** | No |
| **Immediately invoked function expressions (IIFE)** | No |
| **Self-Invoking function** | No |

**[⬆ Back to Top](#functions)**


## 3.1 Higher order functions  & first class citizenship



A programming language is said to have **first-class citizenship** for functions (objects) when functions in that language are treated like any other variable. 

In other words functions (objects) that can be: 
* stored in a variable, object, or array 
* that can be passed as an argument to other functions 
* that can be returned by other functions
* Can be assigned as a value to a variable.

**In JavaScript, functions are first-class citizens (objects)**, as we are able to create functions that can accept functions as well as return functions which in turn allows us to create higher order functions. 

**Higher Order Functions** are functions that operate on other functions, either by taking them as arguments or by returning them.

Array methods such as **.map(), .filter(), .reduce() (see array chapter) are also actually higher order functions.** All three accept a callback function as an argument which is then executed on each element in the array. See array section for more information.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--ql6-J8GL--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/uuhsczcbn8gdbpewmoe6.jpeg)

```javascript
// Without higher-order function
const arr1 = [1, 2, 3];
const arr2 = [];
for(let i = 0; i < arr1.length; i++) {
  arr2.push(arr1[i] * 2);
}

console.log(arr2); // [ 2, 4, 6 ]
```

```javascript
// With higher-order function: .map()
const arr3 = [1, 2, 3];
const arr4 = arr3.map(function(item) {
  return item * 2;
});
console.log(arr4); // [ 2, 4, 6 ]
```

```javascript
// Higher order arrow function
const arr5 = [1, 2, 3];
const arr6 = arr5.map(item => item * 2);
console.log(arr6); // [ 2, 4, 6 ]
```

**[⬆ Back to Top](#functions)**

## 3.2 Function declarations (traditional functions)

Function declarations are hoisted, which means they are loaded at the top of the scope before any other code runs.

Use **function declarations** when you want to create a function on the global scope and make it available throughout your code. Use function expressions (see below) to limit availability.

```javascript
// Function declaration
greet('Tom'); // Hello, Tom! // Hoisted, can call before declaration

function greet(who) {
    console.log(`Hello, ${who}!`); 
  }
```

**[⬆ Back to Top](#functions)**

## 3.3 Function expressions

There is no universally accepted best-practice, but function expressions are commonly preferred over function declarations for the following reasons: 

* Their ability to be reassigned
* Flexibility when composing higher order functions
* They don’t pollute the global scope. Instead of your program being aware of many different functions, when you keep them anonymous, they are used and forgotten immediately.

Use **function expressions** to limit where the function is available, keep your global scope light, and maintain clean syntax.

Use function declaration (see above) when you want to create a function on the global scope and make it available throughout your code


```javascript
// Named function expression
// greet('Tom'); // Cannot access 'greet' before initialization
const greet = function hello(who) {
console.log(`Hello, ${who}!`);
}

greet('Tom'); // Hello, Tom!
```

```javascript
// Anonymous function expression  (lambda)
// greet('Tom'); // Cannot access 'greet' before initialization
const greet = function(who) {
    console.log(`Hello, ${who}!`);
  }

greet('Tom'); // Hello, Tom!
```
```javascript
const named = function named() {} // Named function expression
const anon = function () {} // Anonymous function or lambda
```
```javascript
// Function expression visibility examples
console.log(func); // [Function: func]
console.log(func2); // ReferenceError: Cannot access 'func2' before initialization
console.log(innerFunc); // ReferenceError: innerFunc is not defined

function func() {}
let func2 = function innerFunc() {}

console.log(func); // [Function: func]
console.log(func2); // [Function: innerFunc]
console.log(innerFunc); // ReferenceError: innerFunc is not defined
```

**[⬆ Back to Top](#functions)**

## 3.4 Arrow functions & concise arrow functions

![](https://miro.medium.com/max/1066/1*nRnzjLROZcgLd8A7cHyoXQ.png)

An **arrow function expression** is a compact alternative to a traditional function expression, but is limited and can't be used in all situations.

Differences & Limitations (more advanced):

* Does not have its own bindings to `this` or `super`, and should not be used as methods.

* Does not have arguments, or new.target keywords.

* Not suitable for `call`, `apply` and `bind` methods, which generally rely on establishing a scope.

* Can not be used as constructors.

* Can not use `yield`, within its body.



```javascript
// Arrow function expression
// greet('Tom'); // Cannot access 'greet' before initialization
const greet = (who) => {
    console.log(`Hello, ${who}!`);
  }

greet('Tom'); // Hello, Tom!
```

```javascript
// Same arrow function expression as above in one line
const greet = (who) => {console.log(`Hello, ${who}!`);}

greet('Tom'); // Hello, Tom!
```

```javascript
// Concise arrow function expression
// multiply(2); // Cannot access 'greet' before initialization 
let multiply = x => x * x;

multiply(2); // 4
```

**[⬆ Back to Top](#functions)**

## 3.5 Anonymous functions

An **anonymous function** is a function that was declared without any named identifier to refer to it. 

As such, an anonymous function is usually not accessible after its initial creation. 

Anonymous functions may also be refered to as a **lambda function** or **function literal**.

**Only function expressions can be anonymous, function declarations must have a name.**

```javascript
// Anonymous function
// show(); // Cannot access 'show' before initialization
let show = function () {
    console.log('Anonymous function');
}

show(); // Anonymous function // is accessible again due to assignment to show()
```

```javascript
// Anonymous functions as arguments of other functions
setTimeout(function () {
    console.log('Execute later after 1 second')
}, 1000);
```


**[⬆ Back to Top](#functions)**

## 3.6 Immediately invoked function expressions (IIFE)

Anonymous functions can be used as an argument to other functions or as an **immediately invoked function execution (IIFE)** which is a JavaScript function that runs as soon as it is defined. 


IIFE's may also be referred to as 'self-executing anonymous function' or 'self-invoking function.

```javascript
// Anonymous and immediately invoked function execution (IIFE)
(function () {
    console.log('Immediately invoked function execution');
})(); // note extra set of () to immediately invoke
```

```javascript
// Passing an argument to an anonymous IIFE
let person = {
    firstName: 'John',
    lastName: 'Doe'
};

// We are passing 'person' object as an argument
(function () {
    console.log(`${person.firstName} ${person.lastName}`);
})(person); // 'John Doe'
```


```javascript
// Assigning the IIFE to a variable stores the function's return value, not the function definition itself.
let result = (function () {
    let name = "Barry";
    return name;
})(); // Immediately creates the output:

result; // "Barry"
```


**[⬆ Back to Top](#functions)**

## 3.7 Recursive functions

Recursion is the act of a function calling itself. 

Recursion is used to solve problems that contain smaller sub-problems. A recursive function can receive two inputs: a base case (ends recursion) or a recursive case (resumes recursion).

![](https://study.cs50.net/slideshows/1sKeGiZoBNyYlWLAOUmDqPcup063gNgBmf9JBaKvcVio/img/0.png)

```javascript
// Recursive function
function recurse(x) {
   if (x > 0) {
       console.log(x);
       recurse(x - 1);
   }
};

recurse(5) // 5, 4, 3, 2, 1
```

**[⬆ Back to Top](#functions)**

## 3.8  Callback functions

### "I will call back later!"

A callback function is a function that is passed as an argument to another function, to be “called back” (perform an operation) at a later time. 

A function that accepts other functions as arguments is called a higher-order function, which contains the logic for when the callback function gets executed.


> Eventlisteners have a callback function associated with them.


```js
// Synchronous callback function
function greeting(name) {
    console.log('Hello ' + name);
}
  
function process(callback) {
    let name = 'Tom'
    callback(name);
}
 
// Pass 'greeting' function as argument to process function
process(greeting); // 'Hello Tom'
```

---

### Asynchronous callback vs synchronous callback.

There are 2 types of callbacks by the way they’re invoked: synchronous and asynchronous callbacks.

- The synchronous callback is executed during the execution of the higher-order function that uses the callback.

- The asynchronous callback is executed after the execution of the higher-order function. 

In other words, the synchronous callbacks are blocking: the higher-order function doesn’t complete its execution until the callback is done executing.

The asynchronous callbacks are non-blocking: the higher-order function completes its execution without waiting for the callback. The higher-order function makes sure to execute the callback later on a certain event.

Where callbacks really shine are in asynchronous functions, where one function has to wait for another function (like waiting for a file to load).

Asynchronous functions are covered in the next chapter.

---

> **Why use Callback functions?**
>\
>\
> Most of the time we are creating programs and applications that operate in a synchronous manner. In other words, some of our operations are started only after the preceding ones have completed. 
> 
> Often when we request data from other sources, such as an external API, we don’t always know when our data will be served back. In these instances we want to wait for the response, but we don’t always want our entire application grinding to a halt while our data is being fetched. These situations are where callback functions come in handy.


**[⬆ Back to Top](#functions)**

## 3.9 Asynchronous functions

### "I will finish later!"

Functions running in parallel with other functions are called asynchronous. 

In the real world, callbacks are most often used with asynchronous functions.

A good example is JavaScript setTimeout():

When using the JavaScript function setTimeout(), you can specify a callback function to be executed on time-out:

```js
// Asynchronous callback
function myFunction() {
  console.log('Hello');
}

setTimeout(myFunction, 3000); // callback myFunction after 3000ms

console.log('This log is called after setTimeout call');

// Console.log prints in below order, NOTE: order of events:
// 'This log is called after setTimeout call'
// 'Hello'
```

In the example above, myFunction is used as a callback.

The function (the function name) is passed to setTimeout() as an argument.

3000 is the number of milliseconds before time-out, so myFunction() will be called after 3 seconds.

**[⬆ Back to Top](#functions)**

# 4 Scope

**Scope** is a policy that manages the accessibility of variables. It defines the idea of global and local variables.



![](https://miro.medium.com/max/2880/1*BwARRnm0-gFoh-Rq_ubbwQ.png)

**[⬆ Back to Top](#scope)**

## 4.1 Global scope variables

![](https://i.imgur.com/iZ9I8lV.png)

* A variable declared outside a function, becomes GLOBAL.

* A global variable has global scope: All scripts and functions on a web page can access it. 

```javascript

// global scope variable
var name = "Tim";

// code here can use name

function myFunction() {

  // code here can also use name

}

// code here can use name
```

**[⬆ Back to Top](#scope)**

## 4.2 Local scope variables

Variables declared within a JavaScript function, become LOCAL to the function.

**Local variables have Function scope**: They can only be accessed from within the function.

**Local scope is also referred to as function scope** because local scope is created by functions in Javascript. Variables in the local scope are only accessible within the function in which they are defined, i.e they are bound to their respective functions each having different scopes.

```javascript
// local scope variables


// code here can NOT use name
console.log(name); // ReferenceError: name is not defined


function myFunction() {
    // this function scope (also a block scope)
    var name = "Bob"; // local scope variable
    // code here CAN use name
  }


// code here can NOT use name

console.log(name); // ReferenceError: name is not defined
```

**[⬆ Back to Top](#scope)**

## 4.3 Block scope

**A block scope is the area within if, switch conditions or for and while loops**. Generally speaking, whenever you see {curly brackets}, it is a block. In ES6, const and let keywords allow developers to declare variables in the block scope, which means those variables exist only within the corresponding block

Block scope is sometimes the same as a function scope. **Block scope is everything inside a set of braces { a block scope here }**. So, at the top of a function's code, a block scope will be the same as a function scope:

```javascript
// block scope
if (true) {
  // "if" block scope
  const message = 'Hello';
  console.log(message); // 'Hello'
}


console.log(message); // ReferenceError: message is not defined
```

```javascript
// function scope and block scope example
function test(x) {
   // this is both a block scope and a function scope
   let y = 5; // local scope variable
   if (x) {
       // this is a smaller block scope that is not the same as the function scope
       let z = 1;
   }
}

console.log(y) // ReferenceError: y is not defined
console.log(z) // ReferenceError: z is not defined
```

**[⬆ Back to Top](#scope)**

## 4.4 Function scope

Each function creates a new scope.

Scope determines the accessibility (visibility) of these variables.

Variables defined inside a function are not accessible (visible) from outside the function.

```javascript
function run() {
  // "run" function scope
  var message = 'Run, Forrest, Run!';
  console.log(message); // 'Run, Forrest, Run!'
}

run();
console.log(message); // ReferenceError: message is not defined
```

**[⬆ Back to Top](#scope)**


## 4.5 Scope chain


The **scope chain** is used to resolve the value of variable names in javascript. Without a scope chain the Javascript engine wouldn't know which value to pick for a certain variable name if there are multiple defined at different scopes. 

Scope chain in javascript is lexically defined, which means that we can see what the scope chain will be by looking at the code

- `let`  declares a block-scoped local variable, optionally initializing it to a value.

- `const` is block-scoped, much like variables declared using the let keyword. The value of a constant can't be changed through reassignment, and it can't be redeclared.

- `var` declares a function-scoped or globally-scoped variable, optionally initializing it to a value.


![](https://www.learnsimpli.com/wp-content/uploads/2020/02/2-4.png)



```javascript
// Scope chain example


// Global scope / global variables
let firstLevel = 1
test(firstLevel); // call hoisted function


function test(firstLevel) {
    // this is both a block scope and a function/local scope
    let secondLevel = 2; // Functional/local scope variable
    console.log(firstLevel) // 1
    console.log(secondLevel) // 2
    console.log(thirdLevel) // ReferenceError: thirdLevel is not defined

    if (firstLevel) {
        // this is a smaller block scope that is not the same as the above function scope
        let thirdLevel = 3; // Block scope variable
        console.log(firstLevel) // 1
        console.log(secondLevel) // 2
        console.log(thirdLevel) // 3
    }
 }
 

console.log(firstLevel) // 1
console.log(secondLevel) // ReferenceError: secondLevel is not defined
console.log(thirdLevel) // ReferenceError: thirdLevel is not defined
```

**[⬆ Back to Top](#scope)**


## 4.6 Hoisting

**Hoisting** is JavaScript's default behavior of moving declarations to the top of the current scope (to the top of the current script or the current function). In other words “hoisted” (or lifted) to the top of their scope.

Basically, it gives us an advantage that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local.

It allows us to call functions before even writing them in our code. 

- JavaScript only hoists declarations, not the initialisations.

- All declarations (`function`, `var`, `let`, `const` and `class`) are hoisted in JavaScript, 

- `var` declarations are hoisted  to the top of the block and initialized with `undefined`

- `let` and `const` declarations are hoisted to the top of the block, but not initialized.

> If the JavaScript engine still can’t find the value of `let` or `const` variables at the line where they were declared, it will assign them the value of `undefined` or return an error (in case of `const`).


```javascript
// Function declaration
greet('Tom'); // Hello, Tom! // Hoisted, can call before declaration
// only function declaration type functions are hoisted to the top

function greet(who) {
    console.log(`Hello, ${who}!`); 
  }
```

**[⬆ Back to Top](#scope)**

## 4.7 Lexical scope


Lexical Scoping (also called static scope) defines how variable names are resolved in nested functions: inner functions contain the scope of parent functions even if the parent function has returned.

Javascript has lexical scoping with functions scope. In simple words, this means the child's scope has access to the variables defined in the parent's scope.

Note that inner functions contain the scope of parent functions even if the parent function has returned, also known as **closures**. (See closures below)

>Lexical: of or relating to words or the vocabulary of a language as distinguished from its grammar and construction Our language has many lexical borrowings from other languages


>Lexical: the vocabulary of a person, language, or branch of knowledge.

```javascript
// lexical scope
var scope = "I am global";
function whatismyscope(){
   var scope = "I am just a local";
   function func() {
       return scope;
    }
   return func;
}

console.log(whatismyscope()()) // "I am just a local"
console.log(whatismyscope()) // [Function: func]
```

```javascript
// lexical scope example 2
function outerFunc() {
    // the outer scope
    let outerVar = 'I am from outside!';
  
    function innerFunc() {
      // the inner scope
      console.log(outerVar); // 'I am from outside!'
    }
  
    return innerFunc;
  }
  
  
  outerFunc()(); // "I am from the outside"

  const inner = outerFunc();
  inner(); // "I am from the outside"
  ```

**[⬆ Back to Top](#scope)**

## 4.8 Module scope


In modules, a variable declared outside any function is hidden and not available to other modules unless it is explicitly exported. 

Exporting makes a function or object available to other modules.

```javascript
const express = require('express'); // example how to import express from seperate module
```

![](https://cdn.javascripttutorial.net/wp-content/uploads/2020/06/nodejs-modules.png)

```javascript
// Module scope

// "circle" module scope in it's own file
const pi = 3.14159;
console.log(pi); // 3.14159
// pi variable is declared within the scope of circle module. 
// Also, the variable pi is not exported from the module ()


// Then the circle module is imported from another file:
import './circle';
console.log(pi); // ReferenceError
// The variable pi is not accessible outside of circle module (unless explicitly exported using export).
```


**[⬆ Back to Top](#scope)**


## 4.9 Closures

A **closure is a function having access to the parent scope**, even after the parent function has closed.

- A function within a function, where the outer function’s local variables remain available in memory after creation.

- A closure gives you access to an outer function’s scope from an inner function. 


```js
function outer() {

    let count = 0; // persits in memory after outer is popped off the call stack

    function inner() {
        count++;
        return count;
    }

    return inner;
}

// Creates the Closure
const addOne = outer();

// Operates within its context or lexical environment
addOne(); // 1
addOne(); // 2
addOne(); // 3
```
> Notice how outer contains a local number variable, while inner increments it. Even though outer is only called once, we can still access the count because JS “closes over” the inner function to preserve the execution context.

---

```javascript
// Closure

// Variable 'outer' comes from the "outside", and is called a free variable.
let outer = 1; 

// Function foo adds the values of variables outer, num and inner. 
function foo(num) {
  let inner = 2;
  return outer + num + inner;
}


foo(42); // returns 45; value of 'outer' is preserved inside the function

// A closure is any function that "closes over" one or more free variables. 
```

**[⬆ Back to Top](#functions)**



# 5 Arrays

> Array
![](https://www.educative.io/api/page/6094484883374080/image/download/5163503745761280)

An **array is an ordered list of values**. Each value is called an element specified by an index.

Neither the length of a JavaScript array nor the types of its elements are fixed. 

```js
// Declaring an array
let myArray = [1, 2, 3, 4, 5];

// view array element at index 0
console.log(myArray[0]) // 1

// view array element at index 3
console.log(myArray[3]) // 4

// change the element at index 0 of myArray to 9
myArray[0] = 9;
console.log(myArray); // [ 9, 2, 3, 4, 5 ]
```



**[⬆ Back to Top](#arrays)**

## 5.1 Console.table 

The console.table() method writes a table in the console view.

```js
// console.table()
let fruits = ['apple', 'watermelon', 'mango', 'orange'];

console.table(fruits); // returns below table in console
┌─────────┬──────────────┐
│ (index) │    Values    │
├─────────┼──────────────┤
│    0    │   'apple'    │
│    1    │ 'watermelon' │
│    2    │   'mango'    │
│    3    │   'orange'   │
└─────────┴──────────────┘
```

```js
// An array of arrays
let people = [["John", "Smith"], ["Jane", "Doe"], ["Emily", "Jones"]];

console.table(people); // returns below table in console
┌─────────┬─────────┬─────────┐
│ (index) │    0    │    1    │
├─────────┼─────────┼─────────┤
│    0    │ 'John'  │ 'Smith' │
│    1    │ 'Jane'  │  'Doe'  │
│    2    │ 'Emily' │ 'Jones' │
└─────────┴─────────┴─────────┘
```


**[⬆ Back to Top](#arrays)**

## 5.2 push / pop / shift / unshift 

![](https://www.edureka.co/blog/wp-content/uploads/2019/07/push-pop-1-528x126.png)

`push()` adds one or more elements to the end of an array and returns the new length of the array.

`pop()` removes the last element from an array and returns that element. This method changes the length of the array.

`shift()` removes the first element from an array and returns that removed element. This method changes the length of the array.

`unshift()` adds one or more elements to the beginning of an array and returns the new length of the array.

---

```js
// .push()
let fruits = ['Apple', 'Banana']

// push() adds a new element to the end of an array
let newLength = fruits.push('Orange') // push() returns the new array length

console.log(newLength); // 3
console.log(fruits); // [ 'Apple', 'Banana', 'Orange' ]
```

```js
// .pop()
let fruits = ['Apple', 'Banana', 'Orange'];

// Remove or "pop" Orange (from the end)
// pop() removes the last element from an array
let last = fruits.pop() // pop() method returns the value that was "popped out"

console.log(last); // 'Orange'
console.log(fruits); // [ 'Apple', 'Banana' ]
```

```js
// .shift()
let fruits = ['Apple', 'Banana'];

// Remove Apple from the front
// shift() removes the first array element and "shifts" all other elements to a lower index.
let first = fruits.shift(); // shift() returns the string that was "shifted out"

console.log(first); // 'Apple'
console.log(fruits); // [ 'Banana' ]
```

```js
// .unshift()
let fruits = ['Orange'];

// Add strawberry to the front
// unshift() adds a new element to an array (at the beginning), and "unshifts" older elements:
let newLength = fruits.unshift('Strawberry') // unshift() returns the new array length.

console.log(newLength); // 2 
console.log(fruits); // [ 'Strawberry', 'Orange' ]
```

**[⬆ Back to Top](#arrays)**

## 5.3 length / fill / toString / sort / reverse

`.length` sets or returns the number of elements in that array.

`fill()` method fills the specified elements in an array with a static value.

`.toString()` converts an array to a string, and returns the result.

`.sort()` sorts the elements of an array.

`.reverse()` reverses the order of the elements in an array.

---

```js
// .length
let fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.length; // 4
```

```js
// .fill(value, start, end)
let fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.fill("Kiwi"); // [ 'Kiwi', 'Kiwi', 'Kiwi', 'Kiwi' ]
fruits.fill("Kiwi", 2, 4); // [ 'Banana', 'Orange', 'Kiwi', 'Kiwi' ]
```

```js
// .toString()
let fruits = ["Banana", "Orange", "Apple", "Mango"];
let x = fruits.toString();  // 'Banana,Orange,Apple,Mango'
```

```js
// .sort()
let fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.sort(); // [ 'Apple', 'Banana', 'Mango', 'Orange' ]

// NOTE: numbers are also sorted as strings
let numbers = [1, 2, 100, 1000, 3];
numbers.sort(); // [ 1, 100, 1000, 2, 3 ]
```

```js
// .reverse()
var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.reverse(); // [ 'Mango', 'Apple', 'Orange', 'Banana' ]
```

**[⬆ Back to Top](#arrays)**

## 5.4 concat / join / slice / splice

`.concat()` joins two or more arrays, and returns a copy of the joined arrays.

`.join()` joins all elements of an array into a string.

`.slice()` selects a part of an array, and returns the new array.

`.splice()` adds/removes elements from an array.

```js
// .concat()
let hege = ["Cecilie", "Lone"];
let stale = ["Emil", "Tobias", "Linus"];
let children = hege.concat(stale); // [ 'Cecilie', 'Lone', 'Emil', 'Tobias', 'Linus' ]
```

```js
// .join(separator)
let fruits = ["Banana", "Orange", "Apple", "Mango"];
let energy = fruits.join(); // 'Banana,Orange,Apple,Mango'
energy = fruits.join('++'); // 'Banana++Orange++Apple++Mango'
```

```js
// .slice(start, end)
let fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
let citrus = fruits.slice(1, 3); // [ 'Orange', 'Lemon' ]
```

```js
// .splice(index, howmany, item1, ..., itemX)
let fruits = ["Banana", "Orange"];
fruits.splice(1, 0, "Lemon", "Kiwi"); // [ 'Banana', 'Orange', 'Lemon', 'Kiwi' ]
fruits.splice(0, 4, "Mango", "Watermelon"); // [ 'Mango', 'Watermelon' ]
```

**[⬆ Back to Top](#arrays)**

## 5.5 find / findIndex / indexOf / lastIndexOf

`.find()` returns the value of the first element in an array that pass a test

`.findIndex()` returns the index of the first element in an array that pass a test

`.indexOf()` search the array for an element and returns its position

`.lastIndexOf()` search the array for an element, starting at the end, and returns its position

```js
// .find(function(currentValue, index, arr),thisValue)
// .findIndex(function(currentValue, index, arr), thisValue)
var ages = [3, 10, 17, 20, 25];

function checkAdult(age) {
  return age >= 18;
}

ages.find(checkAdult); // 20
ages.findIndex(checkAdult); // 3
```

```js
// .indexOf(item, start)
// .lastIndexOf(item, start)
let fruits = ["Banana", "Orange", "Apple", "Mango"];

let forwards = fruits.indexOf("Apple"); // 2
let backwards = fruits.lastIndexOf("Apple"); // 2
```

**[⬆ Back to Top](#arrays)**

## 5.6 includes / some / every / forEach

`.includes()` checks if an array contains the specified element

`.some()` checks if any of the elements in an array pass a test

`.every()` checks if every element in an array pass a test

`.forEach()` calls a function for each array element

```js
// .includes(element, start)
let fruits = ["Banana", "Orange", "Apple", "Mango"];
let n = fruits.includes("Mango"); // true
n = fruits.includes("Watermelon"); // false
```

```js
// .some(function(currentValue, index, arr), thisValue)
// .every(function(currentValue, index, arr), thisValue)
let ages = [3, 10, 17, 20, 25];

function checkAdult(age) {
  return age > 20;
}

ages.some(checkAdult) // true
ages.every(checkAdult) // false
```

```js
// .forEach(function(currentValue, index, arr), thisValue)
let ages = [3, 10, 17, 20, 25];
let newArray = []

ages.forEach(function(age) {
    console.log(age); // 3, 10, 17, 20, 25
    newArray.push(age)
});

console.log(newArray); // [ 3, 10, 17, 20, 25 ]
```

**[⬆ Back to Top](#arrays)**

## 5.7 filter / map / reduce

![](https://i.imgur.com/WIOSuvV.jpg)

**Filter, map, and reduce** are **higher order functions** which will iterate over an array and perform a transformation or computation, always returning a new array.


`.filter()` creates a new array with every element in an array that pass a test

`.map()` creates a new array with the result of calling a function for each array element

`.reduce()` reduce the values of an array to a single value (going left-to-right)

- `.reduceRight()` reduce the values of an array to a single value (going right-to-left)

---

```js
// .filter()
const numbers = [1, 5, 11, 15, 20];

function isBigEnoughBoolean(value) {
    console.log(value >= 10) // false, false, true, true, true
    return value >= 10 // if value is >= 10, return true, else false
  }

// "filter" an array by true or false return values from isBigEnoughBoolean function
const result = numbers.filter(isBigEnoughBoolean) // if true, keep element - if false, discard element

console.log(numbers); // [ 1, 5, 11, 15, 20 ]
console.log(result); // [ 11, 15, 20 ]
```


```javascript
// .filter() with concise arrow function expression
const words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

// passing a concise arrow function expression to filter
const result = words.filter(word => word.length > 6); // if true, keep the element - if false, discard

console.log(result); // ["exuberant", "destruction", "present"]
```

```javascript
// .map()
const numbers = [1, 4, 9, 16];

// passing a concise arrow function expression to map
const result = numbers.map(x => x * 2); // function is called for every element of numbers array

console.log(result); // [2, 8, 18, 32]
```



```javascript
// .reduce()
const numbers = [1, 4, 9, 16];

const reduceLog = numbers.reduce((accumulator, current, index) => { 

    // current = the current element being processed in the array
    console.log(current) // 1, 4, 9, 16

    // index = current element index in the array
    console.log(index) // 0, 1, 2, 3 

    // The accumulator accumulates returned values from the previous iterations
    console.log(accumulator) // 0, 1, 5, 14 

    // every iteration adds the value of 'current' to the sum total (accumulator)
    return accumulator + current // 1, 5, 14, 30

  }, 0)

  console.log(reduceLog) // 30
```

> .reduce() visual
![](https://miro.medium.com/max/1510/0*32G_bCgAi8L8ZsQ6.gif)

---

**[⬆ Back to Top](#arrays)**

## 5.8 Two-dimensional (2D) arrays

A **two-dimensional (2D) array** is an array of arrays. Similar to an excel spreadsheet.

![](https://cdn.programiz.com/sites/tutorial2program/files/java-2d-array.jpg)

---

```js
// console.table()
let activities = [
    ['Work', 9],
    ['Eat', 1],
    ['Commute', 2],
    ['Play Game', 1],
    ['Sleep', 7]
];

console.table(activities); // returns below table in console
┌─────────┬─────────────┬───┐
│ (index) │      0      │ 1 │
├─────────┼─────────────┼───┤
│    0    │   'Work'    │ 9 │
│    1    │    'Eat'    │ 1 │
│    2    │  'Commute'  │ 2 │
│    3    │ 'Play Game' │ 1 │
│    4    │   'Sleep'   │ 7 │
└─────────┴─────────────┴───┘
```


**[⬆ Back to Top](#arrays)**

## 5.9 Three dimensional (3D) arrays

A **Three-dimensional (3D) array** is a collection of 2D arrays.

![](https://i1.wp.com/indianaiproduction.com/wp-content/uploads/2019/06/NumPy-array.png?resize=640%2C307&ssl=1)

![](https://i.imgur.com/lYlkrup.gif)

```js
// console.table()
let three = [
    [
        [1, 2, 3],
        [4, 5, 6],
        [7, 8, 9],
    ],

    [
        [11, 12, 13],
        [14, 15, 16],
        [17, 18, 19],
    ],
    [
        [111, 112, 113],
        [114, 115, 116],
        [117, 118, 119],
    ],
];

console.table(three); // returns below table in console
┌─────────┬───────────────────┬───────────────────┬───────────────────┐
│ (index) │         0         │         1         │         2         │
├─────────┼───────────────────┼───────────────────┼───────────────────┤
│    0    │    [ 1, 2, 3 ]    │    [ 4, 5, 6 ]    │    [ 7, 8, 9 ]    │
│    1    │  [ 11, 12, 13 ]   │  [ 14, 15, 16 ]   │  [ 17, 18, 19 ]   │
│    2    │ [ 111, 112, 113 ] │ [ 114, 115, 116 ] │ [ 117, 118, 119 ] │
└─────────┴───────────────────┴───────────────────┴───────────────────┘
```

**[⬆ Back to Top](#arrays)**

# 6 Objects

> Anatomy of an object
>\
>\
![](https://www.iitk.ac.in/esc101/05Aug/tutorial/figures/java/concepts-object.gif)


In computer science, an **object** can be a variable, a data structure, a function, or a method, and as such, is a value in memory referenced by an identifier (pass by reference type).

If a variable can be thought of as a container for a data value, then an object can be thought of as a container for many values or references.

---

An object is a an entity that has:
- **State** (attributes) - What do the objects have? Defined by the attributes and the values they have. Represents data.
- **Behavior** (methods) - What do the objects do? Defined by the operations an object can perform. Represents actions.
- **Identity** - Each object is uniquely identifiable.

> **Functions vs methods:** 
> A method, like a function, is a set of instructions that perform a task. The difference is that **a method is associated with an object, while a function is not**.



Analogy of state vs behavior:

- An object 'Dog' would have **states** (variables): (name, color, breed, hungry)
- An object 'Dog' also have **behaviors** (methods): (bark, fetch, wag tail)


**[⬆ Back to Top](#objects)**

## 6.1 Object declaration & definition

An empty `object` (“empty filing cabinet”) can be created (initialized) using one of three syntaxes:

```js
// Object declaration syntaxes
const dog = { }; // "object literal" syntax

const cat = new Object(); // "object constructor" syntax

const horse = Object.create({ }); // "static method" syntax
```

![](https://javascript.info/article/object/object-user-empty.svg)

---

```js
// Object literal declaration and definition 
const user = { // we are also defining the object with properties
    name: 'Tom',
    age: 25,
    likesBirds: true
}; 
```

![](https://javascript.info/article/object/object-user-props.svg)

**[⬆ Back to Top](#objects)**

## 6.2 Object properties

### The JavaScript object is a collection of properties:


- An `Object` is a collection of properties.

- A `Property` is a **key-value pair** that contains a name and a value.

- A `Property name` is a unique string that points to a value.

- A `Property value` can be any value, including other objects or even functions (methods), that are associated with the name/key. (**states and behaviors**)

- `Functions` (**methods**) are property values.

![](https://i.imgur.com/IiCnMrm.png)

> Objects at the most basic level can be thought of as a **list of key/value pairs** with the key always being a string and the value being… well anything else. Similar to a **filing cabinet**.

**[⬆ Back to Top](#objects)**

## 6.3 Object manipulation

- Use the dot notation `.` or array-like bracket notation `[]` to access a property of an object. (Getter)

- The `delete` operator removes a property from an object.

- The `in` operator checks if a property exists in an object.

- The `for...in` loop iterates over properties of an object.

- When functions are the properties of an object, they are called methods.

> Also called Getters and setters:
>
> Getter - Get a property from an object - dot or bracket notation (get = object.property;)
> 
> Setter - Set a property in an object (object.property = set;)


```js
// Accessing an object property values using dot and bracket notation:

// declare object 'user' and define it
let user = {    
    name: 'John',
    fruit: 'apple',
    loggedIn: true 
  };

user.name = 'Tim'; // change value of name with dot notation (Setter)
user['loggedIn'] = false; // change value of loggedIn with bracket notation (Setter)

// access property with dot notation (Getter)
console.log(user.name); // 'Tim'

// access property with bracket notation
console.log(user['loggedIn']); // false

console.log(user); // { name: 'Tim', fruit: 'apple', loggedIn: false }
```

```js
// Object push, delete and in
let user = { name: 'John', fruit: 'apple', loggedIn: true };

user.age = 30; // pushes a new key/value pair into the end of the object

delete user.fruit; // deletes a key/value pair

console.log(user); // { name: 'John', loggedIn: true, age: 30 }

// To check if a property exists in an object, you use the in operator:
console.log('loggedIn' in user) // true
```

```js
// Object for...in loop
let user = { name: 'John', fruit: 'apple', loggedIn: true };

// iterate over all properties of an object
for(let key in user) { 
    console.log(key); // 'name', 'fruit', 'loggedIn'
}
```

**[⬆ Back to Top](#objects)**


## 6.4 Object methods

`Objects` can also contain methods.

> **Functions vs methods:** 
> A method, like a function, is a set of instructions that perform a task. The difference is that **a method is associated with an object, while a function is not**.

```js
let calculator = {

    add : function(x, y) { return x + y; },
    subtract : function(x, y) { return x - y; },
    multiply : function(x, y) { return x * y; },
    divide : function(x, y) { return x / y; },

  };

console.log(calculator.add(3, 6)); // 9
console.log(calculator.subtract(36, 6)); // 30
console.log(calculator.multiply(3, 6)); // 18
console.log(calculator.divide(36, 6)); // 6
```



**[⬆ Back to Top](#objects)**


## 6.5 Object destructuring

**Destructuring** is a convenient way of extracting multiple values from data stored in (possibly nested) objects and Arrays. 

It is a special syntax that allows us to “unpack” `Objects` or `Arrays` (arrays are also just objects) into a bunch of variables.

```js
// Array destructuring
let arr = ["John", "Smith"]

// sets firstName = arr[0] and surname = arr[1]
let [firstName, surname] = arr;

console.log(firstName); // John
console.log(surname); // Smith
```

```js
// Object single property to value
let person = { name: "Bob", age: 25 };
  
let {name} = person; // name is now a variable for person.name

console.log(name); // 'Bob'
```

```js
// Object destructuring
let options = { title: "Menu", width: 100, height: 200 };
  
let {title, width, height} = options;

console.log(title); // Menu
console.log(width); // 100
console.log(height); // 200
```

  ```js
  // Rest operator
let options = { title: "Menu", height: 200, width: 100 };
  
  let {title, ...rest} = options;
  
  console.log(title); // Menu
  console.log(rest); // { height: 200, width: 100 }
  console.log(rest.height); // 200
  console.log(rest.width); // 200
  ```

**[⬆ Back to Top](#objects)**

## 6.6 Core (built-in) objects

![](https://i.imgur.com/J3ETg5D.png)

JavaScript has several built-in or core language objects:

`Date()`, `Array()`, `Boolean()`, `Error()`, `Function()`, `Math()`, `Object()`, `Number`, and many more...

Object, Function, Boolean and Symbol are the fundamental, basic objects upon which all other objects are based. 

---

`.length`, `.toString()`, `.push()` & `.pop()` and all the other methods we have used so far are actually methods from built-in objects.

Some examples of built-in functionality:

```js
// Core objects
console.log(Number('42')) // 42
console.log(Number.isInteger(42)); // true
console.log(String(42)); // '42'
console.log(Date()); // Wed Mar 31 2021 02:55:29 GMT+0300 (Eastern European Summer Time)
console.log(Boolean('0')); // true
console.log(Math.pow(2, 4)); // 16
console.log(Math.sqrt(36)); // 6
```

**[⬆ Back to Top](#objects)**

## 6.7 Primitive vs non-primitive

### A variable can hold one of two value types: **primitive values** or **reference values** (non-primitive)


- The 7 primitive data types: `string`, `number`, `bigint`, `boolean`, `undefined`, `symbol`, and `null`

```javascript
// Pass primitive by value
let x = 10; // primitive value - non-object
let y = x; // y copies x by value. Now there are 2 instances of the value 10 in memory
let z = y // z copies y by value. Now there are 3 instances in total

x = 99 // this only changes x, but not y or z

console.log(x); // 99
console.log(y); // 10
console.log(z); // 10
// there are 3 seperate instances of the number 10
```

---

### Everything that is not a primitive, is an `Object`.


- Numbers can be objects (if defined with the new keyword)

- Strings can be objects (if defined with the new keyword)

- Booleans can be objects (if defined with the new keyword)

- Regular expressions are always objects

- Dates are always objects

- Maths are always objects

- Arrays are always objects

- **Functions are always objects**

- **Objects are always objects**




**[⬆ Back to Top](#objects)**

## 6.8 Primitive wrappers

In JavaScript, a `primitive` (primitive value, primitive data type) is data that is not an object and has no methods. 

Primitive values, like "John Doe", cannot have properties or methods (because they are not objects).

> **If primitives have no properties, why does "abc".length return a value?**
>\
>\
> Because JavaScript will readily coerce between primitives and objects. In this case the string value is coerced to a string object in order to access the property length. The string object is only used for a fraction of second after which it is destroyed and sent of to garbage collection


JavaScript automatically converts primitives to String objects, so that it's possible to use String object methods for primitive strings.


In contexts where a method is to be invoked on a primitive string or a property lookup occurs, **JavaScript will automatically wrap the String object around the string primitive** and call the method or perform the property lookup.

With the exception of `Null` and `Undefined`, all primitive values have object equivalents which wrap around the primitive values.

---

### String primitives vs string objects

So what actually happens is that a primitive is converted to its wrapper type when a method of the wrapper type is invoked. Put simple:
```js
var primitiveString = 'test';
```
`primitiveString` is a primitive data type which has no methods. 

It is nothing more than a pointer to a raw data memory reference, which explains the much faster random access speed.

Since `primitiveString` is not an instance of a String Object, JavaScript will auto-box `primitiveString`.

The auto-boxing behaviour casts `primitiveString` back and forth to its wrapper type as needed.

The standard operations for this auto-boxing are incredibly fast since you are dealing with a simpler data type.

---

In case of string literal we cannot assign properties:
```js
var x = "hello" ;
x.y = "world";
console.log(x.y); // undefined
```
Whereas in case of String Object we can assign properties:
```js
var x = new String("hello");
x.y = "world";
console.log(x.y); // 'world'
```



**[⬆ Back to Top](#objects)**

## 6.9 Value vs reference

![](https://res.cloudinary.com/practicaldev/image/fetch/s--CwQwOULx--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/l4aptnsmawrur69mpixf.gif)



- **Pass by value** (primitive) creates a new location in memory (duplicate):
    - `Primitive values` are **immutable** and passed by value (a copy of the value is made in memory)

    - The 7 primitive data types: `string`, `number`, `bigint`, `boolean`, `undefined`, `symbol`, and `null`

- **Pass by reference** (non-primitive) refers to an existing location in memory:

    - Everything that is not a primitive, is an `object` (Arrays and Functions are also objects) 

    - `Objects` are passed by reference. No copy is made in memory.

    - An object is like a man-in-the-middle, referencing things to other things

    - **Variables maintain a reference to an object, as opposed to a full copy of it**. 

    - Any variable that points to that reference can set its properties and they will be shared between all variables.

```js
// Pass by reference - create new object and """copy""" it
let user = { name: "John" };

let admin = user; // copy the reference - pass by reference
```


![](https://i.imgur.com/TSuEXRq.jpg)
> Now we have two variables, admin and user, each storing a reference to the same object:

---


In general, we should be using const as much as possible and only using let when we know a variable will change.

Let’s be really clear about what we mean by “change”.
A mistake is to interpret “change” as a change in value. A JS programmer who interprets “change” this way will do something like this:

```js
// Change in value vs change in reference
let sum = 0 // 
sum = 1 + 2 + 3 + 4 + 5
let numbers = []
numbers.push(1)
numbers.push(2)
numbers.push(3)
numbers.push(4)
numbers.push(5)
```

This programmer correctly declared “sum” using let, because they knew that the value would change. 

However, this programmer incorrectly declared “numbers” using let, because they interpret pushing things onto the array as changing its value.

### The correct way to interpret “change” is a change in memory address. 

- Let allows you to change memory addresses. 

- Const does not allow you to change memory addresses.

---

**[⬆ Back to Top](#objects)**

# 7 Object-oriented

> An Object
>\
![](https://www.iitk.ac.in/esc101/05Aug/tutorial/figures/java/concepts-object.gif)


> Multiple objects
>\
![](https://www3.ntu.edu.sg/home/ehchua/programming/java/images/OOP_Objects.png)

The basic idea of OOP is that we use objects to model real world things that we want to represent inside our programs, and/or provide a simple way to access functionality that would otherwise be hard or impossible to make use of.

Objects can contain related data and code, which represent information about the thing you are trying to model, and functionality or behavior that you want it to have. 

Object data (and often, functions too) can be stored neatly (the official word is encapsulated) inside an object package (which can be given a specific name to refer to, which is sometimes called a namespace), making it easy to structure and access; objects are also commonly used as data stores that can be easily sent across the network.

**[⬆ Back to Top](#object-oriented)**
    
## 7.1 This

If we want:

- A function inside an object (method of that object) to have access to a variable inside that same object:

Then we need to use the `this` keyword:

```js
// Object literal and this
const user = {
    name: 'Jeff', // A property of user
    test() {
        console.log(name); // ReferenceError: name is not defined 
        // test() does not have access to 'user' object property 'name' (user.name)

        // this refers to the object 'user' itself
        console.log(this) // { name: 'Jeff', test: [Function: test], hello: [Function: hello] }
    },
    hello() {

        // 'this' refers to 'user' object 
        // 'this.name' refers to object property: 'user.name' 
        console.log(this.name) // 'Jeff'
    }
  }
  
user.hello(); // 'Jeff'
```

In JavaScript, the thing called `this` is the object that "owns" the code.

- The value of `this`, when used in an object, is the object itself.

- In an object method (function), `this` refers to the "owner" of that method (the object itself).

- The value of `this` will become the new object when a new object is created.

---

Functions using the arrow syntax are not bound to `this`, so it refers to the outer or global `this` context:

```js
// Arrow functions and this
const obj = {
  username: 'Jeff',
  hello: () => console.log(this.username)
}

obj.hello(); // My name is undefined
```



**[⬆ Back to Top](#object-oriented)**

## 7.2 Constructors & new

Constructors are technically just like regular functions that describe **how to create an Object**. 

Sometimes we want to create many similar objects, like multiple users and so on.

- In a constructor function, `this` does not have a value. It is a substitute for the new future object. 

- Constructor functions are named with capital letter first.

Constructors are like a **"skeleton" or a "blueprint"** for creating these objects of the same "type".


```js
// Constructor function which creates an "object type"
function User(first, last) {
    this.firstName = first
    this.lastName = last
  };
```

To create an actual object from the "blueprint" or constructor function, we use the `new` keyword:

```js
let user1 = new User("Jon", "Snow")
let user2 = new User("Ned", "Stark")

console.log(user1.firstName) // 'Jon'  
console.log(user1.lastName) // 'Snow'  
console.log(user2) // User { firstName: 'Ned', lastName: 'Stark' }
```
> Objects of the same type are created (**instantiated**) by calling the constructor function with the `new` keyword.


The `new` operator lets us create an instance of a user-defined object type or of one of the built-in object types that has a constructor function such as `Date` etc.

```js
// New Date object - we now have access to Date object methods
let time = new Date();

console.log(time); // 2021-04-01T13:18:55.796Z
console.log(time.getMonth()); // 3
console.log(time.getFullYear()); // 2021
```


```js
// Constructor function
function Boat(name) {
  this.name = name;
  this.created = Date.now()

  this.horn = function () {
    console.log(this.name)
  }
}

// The new objects of the "boat type" are then instantiated with the new keyword.
const sally = new Boat('Sally');
const molly = new Boat('Molly');

sally.horn() // Sally
molly.horn() // Molly
```

> You can not add a new property to an existing object constructor.

> To add a new property to a constructor, you must add it to the constructor function itself (body of function).

**[⬆ Back to Top](#object-oriented)**

## 7.3 Constructors vs literals

In JavaScript there are two ways to create an object: 

- The literal notation
```js
let arr2 = ['a', 'b', 'c', 'd'];
```

- The constructor function 
```js
let arr = new Array('a', 'b', 'c', 'd');
```

**These two produce the same result: an array object.**

---

### So what's the difference (constructors vs literals)?

- The literal notation delivers a single object, like a singleton.

- The constructor function creates object that can be instantiated into multiple instances (with the `new` keyword)



```js
// Repetitive way of creating objects with similar properties
const dog1 = { name: 'Max', age: 5 }
const dog2 = { name: 'Daisy', age: 7 }
const dog3 = { name: 'Cooper', age: 3 }
const dog4 = { name: 'Jack', age: 4 }
```

```js
// Constructor function - When we need to instantiate multiple instances with ease.
function Dog(name, age) {
    this.name = name
    this.age = age
  };

const dog1 = new Dog('Max', 5);
const dog2 = new Dog('Daisy', 7);    
const dog3 = new Dog('Cooper', 3);   

// Note: they are all part of the same object: "Dog"
// With the constructor, you create an object that can be instantiated into multiple instances
console.log(dog1); // Dog { name: 'Max', age: 5 }
console.log(dog2); // Dog { name: 'Daisy', age: 7 } 
console.log(dog3); // Dog { name: 'Cooper', age: 3 }
```


**[⬆ Back to Top](#object-oriented)**

## 7.4 Factories

If a function returns a new object without the `new` keyword, they are said to be a **Factory Function**. 

The factory function pattern is similar to constructors, but instead of using `new` to create an object, factory functions simply set up and return the new object when you call the function. 

```js
// Factory function
const personFactory = (name, age) => {
    const sayHello = () => console.log('hello!');
    return { name, age, sayHello };
};
  
const jeff = personFactory('jeff', 27);

console.log(jeff.name); // 'jeff'

jeff.sayHello(); // calls the function and logs 'hello!'
```

For reference, here is the same thing created using the constructor pattern:

```js
const Person = function(name, age) {
  this.sayHello = () => console.log('hello!');
  this.name = name;
  this.age = age;
};

const jeff = new Person('jeff', 27);
```
>The convention of defining a constructor function is to use capitalize function name to denote that this is a constructor function. 


### What’s the Difference Between a Factory and a Constructor?

A **constructor function** is used with the `new` keyword which causes JavaScript to:

- automatically create a new object

- set `this` within the function to that object

- return the object (not a value)

```js
// Constructor function
let objFromConstructor = new ConstructorFunction();
```
---

```js
// Factory function
let objFromFactory = factoryFunction();
```

A **factory function** is called (invoked) like a "regular" function, but for it to be considered a "factory" it would need to return a new instance of some object. 

**You wouldn't call it a "factory" function if it just returned a boolean or something**. 

This does not happen automatically like with `new`, but it does allow more flexibility for some cases.

As opposed to the constructor functions they differ only from its use case and a convention. (Some advanced level differences and side-effects are present)

Other than that factory functions and constructor functions are similar. 

**[⬆ Back to Top](#object-oriented)**

## 7.5 Classes (Constructor 2.0)

Classes are a template or blueprint for creating objects just like constructors.

Javascript classes are modernized syntactic sugar for constructors.

- A JavaScript class itself is not an object. It is just a template for JavaScript objects.

Use the keyword `class` to create a class.

```js
// Class syntax
class ClassName {
  constructor() { ... }
}
```

Always add a method named constructor():

```js
// We create a class named "Car".
// The class has two initial properties: "name" and "year".
class Car {
  constructor(name, year) {
    this.name = name;
    this.year = year;
  }
}
```

```js
// When you have a class, you can use the class to create objects:
// We use the Car class to create two Car objects.
let myCar1 = new Car("Ford", 2014);
let myCar2 = new Car("Audi", 2019);
```

### The Constructor Method

The constructor method is a special method:

- It has to have the exact name "constructor"
- It is executed automatically when a new object is created
- It is used to initialize object properties
- If you do not define a constructor method, JavaScript will add an empty constructor method.

---

### Class Methods

Class methods are created with the same syntax as object methods.

Use the keyword `class` to create a class.

Always add a constructor() method.

```js
class Car {
  constructor(name, year) {
    this.name = name;
    this.year = year;
  }
  age() {
    let date = new Date();
    return date.getFullYear() - this.year;
  }
}

let myCar = new Car("Ford", 2014);

console.log(myCar.age()); // 7
```

**[⬆ Back to Top](#object-oriented)**

## 7.6 Class inheritance & extends

Inheritance is useful for code reusability: reuse properties and methods of an existing class (blueprint) when you create a new class (blueprint).

To create a class inheritance, use the `extends` keyword.

A class created with a class inheritance inherits all the methods from another class:

```js
// Class inheritance
class Car {
    constructor(brand) {
      this.carname = brand;
    }
    present() {
      return 'I have a ' + this.carname;
    }
}
  

// Using extend to `extend` the Car class
class Model extends Car {
    constructor(brand, mod) {
      super(brand);
      this.model = mod;
    }
    show() {
      return this.present() + ', it is a ' + this.model;
    }
}

  
let myCar = new Model("Ford", "Mustang");

console.log(myCar.show()); // I have a Ford, it is a Mustang
```

The `super()` method refers to the parent class.

By calling the `super()` method in the constructor method, we call the parent's constructor method and gets access to the parent's properties and methods.

**[⬆ Back to Top](#object-oriented)**

## 7.7 Prototype model

**Javascript is a prototype-based (prototypal), object-based language** , rather than being class-based (like Java).

> **NOTE**: JavaScript classes however, are primarily syntactical sugar over JavaScript's existing prototype-based inheritance. Classes in JS are built on prototypes. They are not like classes in other class-based languages, such as Java.

> Classes in JavaScript, which were created for ES6, are just syntax sugar on top of function-objects. Instead of having to type prototype over-and-over again to define methods on functions, with the class keyword we can just define a group of methods inside of a class. With the extends keyword, classes can inherit from other classes without having to do Object.create.

Prototype-based programming is a style of object-oriented programming in which behaviour reuse (known as inheritance) is performed via a process of reusing existing objects that serve as prototypes. 



- Prototype-based programming uses generalized objects, which can then be cloned and extended. 

- Prototypes are the mechanism by which JavaScript objects inherit features from one another.

---

```js
let myObj = {}; // Empty object literal
// Is the equivalent of:
let myObj = new Object();
```

```js
// Constructor function
function Cat() {
    // constructor for kitty
};

let kitty = new Cat();

console.log(kitty); // Cat {}
console.log(Cat); // [Function: Cat]
```

![](https://i.imgur.com/CrR1PH8.jpg)


```js
console.log(myObj.__proto__); // [Object: null prototype] {}
console.log(myObj.constructor); // [Function: Object]
console.log(myObj.constructor.prototype); // [Object: null prototype] {}
console.log(myObj.__proto__ == myObj.constructor.prototype); // true
```

```js
console.log(kitty.__proto__); // {}
console.log(kitty.constructor); // [Function: Cat]
console.log(kitty.constructor.prototype); // {}
console.log(kitty.__proto__ == myObj.constructor.prototype); // false
console.log(kitty.__proto__ == kitty.constructor.prototype); // true
```

**[⬆ Back to Top](#object-oriented)**

## 7.8 Prototype chain & inheritance

Prototypes are the mechanism by which JavaScript objects inherit features from one another.

JavaScript works with objects. Everything except primitives are objects. 

All JavaScript objects inherit properties and methods from a prototype:

- `Date` objects inherit from `Date.prototype`

- `Array` objects inherit from `Array.prototype`

- `Math` objects inherit from `Math.prototype`



> The `Object.prototype` is on top of the prototype inheritance chain; ​ `Date` objects, `Array` objects, and so on all inherit from `Object.prototype`.
![](https://i.imgur.com/osotLZb.jpg)


---

### Understanding the Prototype Object

Without classes in JavaScript (*classical classes, such as in Java), inheritance is only possible due to Prototype objects.

- A prototype is an object which is used as template from which all new objects will get their properties.

- Any object can be used as a prototype for another object and share the properties with that object.

- The object can override the inherited methods/properties, but it will not impact the prototype.

- The prototype can change it's methods/properties or add new ones, which will impact the objects which was created from the same prototype.


So basically we create copies from one object and then all copies will move with their own life. The new object will have access to all the methods/properties of the prototype as long as they are not overridden. 

Even if there is any method/property being added to the prototype class after the object creation, object will still have access to those newly added method/property. Any changes in the object will not impact prototype, but any change in prototype will impact all objects. This is the core of prototype based programming.

![](https://frontend.turing.io/assets/images/lessons/oop/chain.png)


**[⬆ Back to Top](#object-oriented)**

## 7.9 Overview of OOP - prototype-based vs class-based


### A Quick Overview of Object-Oriented Programming


Both prototypal inheritance and classical inheritance are object-oriented programming paradigms (i.e. they deal with objects). Objects are simply abstractions which encapsulate the properties of a real world entity (i.e. they represent real word things in the program). This is known as abstraction.

**Abstraction**: The representation of real world things in computer programs.

Theoretically an abstraction is defined as "a general concept formed by extracting common features from specific examples". However for the sake of this explanation we're going to use the aforementioned definition instead.

Now some objects have a lot of things in common. For example a dirt bike and a Harley Davidson have a lot in common.

A dirt bike and a Harley Davidson are both bikes. Hence a bike is a generalization of both a dirt bike and a Harley Davidson.

```
                   Bike
                     |
    +---------------------------------+
    |                                 |
    v                                 v
Dirt Bike                       Harley Davidson
```

In the above example the bike, the dirt bike and the Harley Davidson are all abstractions. However the bike is a more general abstraction of the dirt bike and the Harley Davidson (i.e. both the dirt bike and the Harley Davidson are specific types of bikes).

Generalization: An abstraction of a more specific abstraction.

In object-oriented programming we create objects (which are abstractions of real world entities) and we use either classes or prototypes to create generalizations of these objects. Generalizations are created via inheritance. A bike is a generalization of a dirt bike. Hence dirt bikes inherit from bikes.

### Classical Object-Oriented Programming

In classical class-based object-oriented programming we have two types of abstractions: classes and objects. An object, as mentioned before, is an abstraction of a real world entity. A class on the other hand is an abstraction of an object or another class (i.e. it's a generalization). For example, consider:

```js
+----------------------+----------------+---------------------------------------+
| Level of Abstraction | Name of Entity |                Comments               |
+----------------------+----------------+---------------------------------------+
| 0                    | John Doe       | Real World Entity.                    |
| 1                    | johnDoe        | Variable holding object.              |
| 2                    | Man            | Class of object johnDoe.              |
| 3                    | Human          | Superclass of class Man.              |
+----------------------+----------------+---------------------------------------+
```

As you can see in classical object-oriented programming languages, objects are only abstractions (i.e. all objects have an abstraction level of 1) and classes are only generalizations (i.e. all classes have an abstraction level greater than 1).

Objects in classical object-oriented programming languages can only be created by instantiating classes:

```js
class Human {
    // ...
}

class Man extends Human {
    // ...
}

Man johnDoe = new Man();
```
In summation in classical object-oriented programming languages objects are abstractions of real world entities and classes are generalizations (i.e. abstractions of either objects or other classes).

Hence as the level of abstraction increases entities become more general and as the level of abstraction decreases entities become more specific. In this sense the level of abstraction is analogous to a scale ranging from more specific entities to more general entities.

### Prototypal Object-Oriented Programming

Prototypal object-oriented programming languages are much simpler than classical object-oriented programming languages because in prototypal object-oriented programming we only have one type of abstraction (i.e. objects). For example, consider:

```js
+----------------------+----------------+---------------------------------------+
| Level of Abstraction | Name of Entity |                Comments               |
+----------------------+----------------+---------------------------------------+
| 0                    | John Doe       | Real World Entity.                    |
| 1                    | johnDoe        | Variable holding object.              |
| 2                    | man            | Prototype of object johnDoe.          |
| 3                    | human          | Prototype of object man.              |
+----------------------+----------------+---------------------------------------+
```

As you can see in prototypal object-oriented programming languages objects are abstractions of either real world entities (in which case they are simply called objects) or other objects (in which case they are called prototypes of those objects that they abstract). Hence a prototype is a generalization.

Objects in prototypal object-oriented programming languages may be created either ex-nihilo (i.e. out of nothing) or from another object (which becomes the prototype of the newly created object):

```js
var human = {};
var man = Object.create(human);
var johnDoe = Object.create(man);
```

In my humble opinion prototypal object-oriented programming languages are more powerful than classical object-oriented programming languages because:

- There is only one type of abstraction.

- Generalizations are simply objects.

By now you must have realized the difference between classical inheritance and prototypal inheritance. Classical inheritance is limited to classes inheriting from other classes. However prototypal inheritance includes not only prototypes inheriting from other prototypes but also objects inheriting from prototypes.

### Conclusion

In summation we learned that an abstraction is a "a general concept formed by extracting common features from specific examples" and that generalization is "an abstraction of a more specific abstraction". We also learned about the differences between prototypal and classical inheritance and how both of them are two faces of the same coin.

On a parting note I would like to remark that there are two patterns of prototypal inheritance: the prototypal pattern and the constructor pattern. The prototypal pattern is the canonical pattern of prototypal inheritance whereas the constructor pattern is used to make prototypal inheritance look more like classical inheritance. 

**[⬆ Back to Top](#object-oriented)**

# 8 Data structures & memory

![](https://i.imgur.com/gu8JtSb.jpg)

In computer science, a **data structure** is a data organization, management, and storage format that enables efficient access and modification. 

More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.

![](https://media.geeksforgeeks.org/wp-content/uploads/20191010170332/Untitled-Diagram-183.png)

---

Data structures, at a high level, are techniques for storing and organizing data that make it easier to modify, navigate, and access. Data structures determine how data is collected, the functions we can use to access it, and the relationships between data.

Data structures are used in almost all areas of computer science and programming, from operating systems to basic vanilla code to artificial intelligence.

Data structures enable us to:

- Manage and utilize large datasets

- Search for particular data from a database

- Design algorithms that are tailored towards particular programs

- Handle multiple requests from users at once

- Simplify and speed up data processing

Data structures are vital for efficient, real-world problem solving. After all, the way we organize data has a lot of impact on performance and useability. In fact, most top companies require a strong understanding of data structures.

### In this chapter, we will be looking into a high-level overview of various data structures.


**[⬆ Back to Top](#data-structures--memory)**



## 8.1 Stack & queue

![](https://i.imgur.com/PW74S7D.jpg)

> In terms of complexity, stacks and queues are the simplest and can be constructed from linked lists. See linked lists below.
---

A `stack` is a data structure that holds a list of elements and operates based on the **LIFO** principle - **Last In, First out**.

> Meaning that the most recently added element is the first one to remove.

A stack has three main operations:
- **Push** adds an element to the top of stack
- **Pop** removes an element from the top of the stack
- **Peek** get the topmost element of the stack

```js
// Stack using javascript array
let stack = [];  
//push
stack.push(5);  
stack.push(10);

//pop
stack.pop(); //10  
stack.pop(); //5
```

---

A `queue` is a linear structure of sequential and ordered elements which is similar to a stack, with a difference that it works based on the **FIFO** principle - **First In, First Out**.

> Meaning the first or oldest element that was added to queue will be the first to be removed.

A queue data structure has two fundamental operations:

- **Enqueue** (push) inserts or pushes a new element to the queue
- **Dequeue** (pop) removes or pops the oldest element from the queue

```js
// Queue using javascript array
let queue = [];

// enqueue
queue.push(3);  
queue.push(5);  
queue.push(10);

console.log(queue); // [ 3, 5, 10 ]

// dequeue
queue.shift(); // 3  
queue.shift(); // 5
queue.shift(); // 10
```

**[⬆ Back to Top](#data-structures--memory)**


## 8.2 Arrays - indexed & associative

![](https://www.educative.io/api/page/6094484883374080/image/download/5163503745761280)

The most basic of all data structures, an array stores data in memory for later use. 

An array data structure or an array is an ordered list of values, or a collection of elements (values or variables) identified by an index or key. The most simple type of array data structure is a linear array.

The array is the most basic data structure, merely a list of data elements that you can access by an index, which is the data’s position inside the array. 

Arrays are quite efficient at searching if the elements in the array are ordered. However, insertion and deletion are not as efficient since you have to shift all elements when you delete or insert an item.

At it's core (in computer science), there are two types of arrays - indexed arrays and associative arrays (javascript objects). For

> ### What we in javascript refer to as a collection of key-value pairs (javascript object), computer science refers to this as an associative array!

---

### Indexed arrays vs associative arrays (javascript object)

- **Indexed arrays** are used when you identify things by their position called "indices," and we don't get to pick them — they are always sequential integers (0, 1, 2, 3, etc). (like a regular javascript array - [] )


- **Associative array** (also known as maps or hash) is a set of key/value pairs (like a javascript object). Objects (associative arrays) are not ordered/sorted like indexed arrays. Objects have key/value pairs.

> JavaScript does not have built-in support for arrays with named indexes like other languages do! In javascript, these associative arrays are actually objects! - {}

> ### Associative array is the computer science term for a key-value pair collection. 

> ### Key-value pair array (collection) = associative array = javascript object

---

**There are no associative-arrays in JavaScript per-se. They are objects.** 


Arrays with named indexes are called associative arrays (sometimes called hashes, map structures or a dictionary objects).

Other languages support associative arrays (named indexes) as arrays, Javascript does not. In javascript these entities are not arrays, but rather objects.

Associative arrays and objects are the same thing. Every object is internally much like an associative array.

> ### The key idea is that **every Javascript object underneath the hood is an associative array** ,as an associative array is simply a set of key value pairs, just like a javascript object itself.

---

In a JavaScript, an object and a regular indexed array are also pretty much the same thing, with an array having a bit of magical functionality (autoupdating the length property and such) and prototype methods suitable for arrays. 

It is also much easier to construct an object than using an ""associative array"":

```js
var obj = {"my.key": "myValue"};
```
vs

```js
var obj = [];
obj["my.key"] = "myValue";
```


**[⬆ Back to Top](#data-structures--memory)**



## 8.3 Linked lists - array vs linked list

Like arrays, `Linked Lists` are a linear data structure, which stores data elements in sequential order. However, unlike arrays, elements are not stored in a particular memory location or index. 

Instead of keeping indexes, linked lists hold pointers to other elements meaning that each element is a separate object that contains a pointer or a link to the next object in that list.

Each element (commonly called nodes) contains two items: the data stored and a link to the next node. The data can be any valid data type. 

The first node is called the `head` while the last node is called the `tail`. 

The tail node is a special node, where the next pointer is always pointing or linking to a null reference, indicating the end of the list. Null signals the end of the list.

- In a singly-linked list, each node has only one pointer to the next node. Here, the head is where we begin our walk down the rest of the list. 

- In a doubly-linked list, a pointer to the previous node is also kept. Therefore, we can also start from the tail and walk “backwards” toward the head.

The benefit of Linked List over an array is that you can delete and insert elements from the beginning in one step.

![](https://i.imgur.com/NyO5G2W.jpg)


---


### Linked list vs array

```
Array:  0: A    1: B    2: C    3: D    4: E    5: F
Singly Linked List: (head) A → B → C → D → E → (tail) F → null
```

![](https://open4tech.com/wp-content/uploads/2019/03/array-linked-list.png)

![](https://miro.medium.com/max/3572/1*Lnb0IARMGORn_c-gYf-24g.png)




**[⬆ Back to Top](#data-structures--memory)**


## 8.4 Trees

A `Tree` is like a linked list, except it keeps references to many child nodes in a hierarchical structure. In other words, each node can have no more than one parent. 

The Document Object Model (DOM) is such a structure, with a root html node that branches into the head and body nodes, which further subdivide into all the familiar html tags. 

![](https://adrianmejia.com/images/tree-parts.jpg)


Trees are another relation-based data structure, which specialize in representing hierarchical structures. Like a linked list, nodes contain both elements of data and pointers marking its relation to immediate nodes.

Each tree has a “root” node, off of which all other nodes branch. The root contains references to all elements directly below it, which are known as its “child nodes”. This continues, with each child node, branching off into more child nodes.

Nodes with linked child nodes are called internal nodes while those without child nodes are external nodes. A common type of tree is the “binary search tree” which is used to easily search stored data.

**Binary search trees**, which means every node has up to two nodes, and its left descendants are less than or equal to the current node. And the right descendants are greater than the current node. This rule applies to all nodes. The benefit that a tree has over a hash table is besides doing quick search, insertion, and deletion, it can also maintain order.

These search operations are highly efficient, as its search duration is dependent not on the number of nodes but on the number of levels down the tree.

![](https://www.educative.io/api/page/6094484883374080/image/download/4860454879887360)

### Tries

A `trie` is a tree-like data structure, with nodes that store the letters of an alphabet. Words and strings can be reTRIEved from the structure by traveling down a branch path of the tree.


**[⬆ Back to Top](#data-structures--memory)**

## 8.5 Graphs

`Graphs` are a relation-based data structure helpful for storing web-like relationships. Each node, or vertex, as they’re called in graphs, has a title (A, B, C, etc.), a value contained within, and a list of links (called edges) it has with other vertices.

![](https://adrianmejia.com/images/graph-parts.jpg)

If a tree has more than one parent, it becomes a Graph. 

Graphs onsist of a limited set of nodes or points, along with a set of unordered pairs of these nodes for an undirected graph or a set of ordered pairs for a directed graph. 


**[⬆ Back to Top](#data-structures--memory)**

## 8.6 Hash tables (hash maps)

A **hash table** (often called a hash map) is a data structure that maps keys to values.

In computing, a **hash table** (hash map being a slight variant) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. 

The term “hash table” is talking about the implementation: a specific way to organize your data in memory.

The term “associative array” is talking about the interface: the concept that you use objects as array indices. (This is sometimes called an abstract data structure.)

**Hash tables are the mechanism in which the key can be paired to the value in a key-value pair.**

> A JavaScript Object is an example of a Hash Table because data is represented a key/value pairs. A hashing function can be used to map the key to an index by taking an input of any size and returning a hash code identifier of a fixed size. If you've used a JavaScript object, then you have used a hash table.

There are multiple ways to implement an associative array. A hash table is one of them – in fact, it is by far the most common one.

A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.

In the world of data structures and algorithms Hash Tables are extremely prevalent. Javascript abstracts them away (they are Objects).

![](https://www.educative.io/api/page/6094484883374080/image/download/6745911163092992)
> A **hash function** is a method or function that takes an item’s key as an input, assigns a specific index to that key and returns the index whenever the key is looked up.

In Computing Science terminology, a map is an associative container mapping from a key to a value. In other words, you can do operations like "for key K remember value V" and later "for key K get the value". A map can be implemented in many ways - for example, with a (optionally balanced) binary tree, or a hash table, or even a contiguous array of structs storing the key/value.

A hash table is a structure for storing arbitrary data, and that data does not necessarily consist of a separate key and value. For example, I could have a hash table containing the values { 1, 10, 33, 97 }, which would be their own keys. When there is no value distinct from the key, this is sometimes known as a "set", and with a hash table implementation a "hash set".

So, a hash table stores elements, each of which need not consist of distinct key and value components, but if it does then it's also a hash map.

### Hash table vs associative array (javascript object)
> Javascript does not have associative arrays per se - it uses objects as an implementation for this.

The difference between an associative array and a hash table is that an associative array is a data type, while a hash table is an implementation method of an associative array.

In other words, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values.


**[⬆ Back to Top](#data-structures--memory)**


## 8.7 Javascript memory model - value vs reference under the hood

### Declare variable to memory

```js
let myNumber = 23
```

When the above variable is declared, javascript will:

- Create a unique identifier for your variable: `myNumber`

- Allocate an address in memory/RAM (will be assigned at runtime)
- Store a value of 23 at the address allocated

`myNumber` now equals the memory address that holds the value 23 - 0012CCGWH80.

![](https://miro.medium.com/max/700/1*IiejRUFbks-TaOzJJvdoVw.jpeg)

---

### Reassign declared variable in memory

If we were to create a new variable called “newVar” and assign it “myNumber”…

```js
let newVar = myNumber
```

Since `myNumber` equals the memory address “0012CCGWH80”, assigning it to newVar assigns “0012CCGWH80” to newVar.

![](https://miro.medium.com/max/700/1*AaUqtuwa2BZiI73bV9RHmA.jpeg)



---

### Mutate existing variable in memory

What if we try to change or **mutate** the value:

```js
myNumber = myNumber + 1
```

Since primitive data types in javascript are immutable, when “myNumber + 1” resolves to “24”, javascript will allocate a new address in memory, store 24 as its value, and “myNumber” will point to the new address.

![](https://miro.medium.com/max/700/1*awL1xpr8cDNV7AaxiaA7YQ.jpeg)

---

### Mutate existing string in memory

```js
let myString = 'abc'
myString = myString + 'd'
```
When ‘abc’ is concatenated with ‘d’, since strings are also primitive data types in JS, a new memory address is allocated, ‘abcd’ is stored there, and “myString” points to this new memory address.

![](https://miro.medium.com/max/700/1*WQHSspJDrPGOQ9L8R01jmw.jpeg)


**[⬆ Back to Top](#data-structures--memory)**

## 8.8 Javascript memory model - call stack & heap

### The call stack and memory heap

The Javascript Engine does a lot of work for us. 

But the biggest thing is reading our code and executing it. The two main important things in this step are:

- We need a place to store and write information — data for our app(variables, objects, etc..)

- We need to keep track of what's happening to our code line by line.

#### This is where a call stack and a memory heap comes in:

- We need the `memory heap` as a place to store and write information because at the end of the day all programs just read and write operations — that is to allocate, use and release memory.

- The `call stack` helps us keep track of where we are in the code so that we can run the code in order.

---

The **call stack** is where primitives are stored (in addition to function calls). A rough representation of the call stack after declaring the variables in the previous section is below.

The **heap** is where non-primitives are stored. The key difference is that the heap can store unordered data that can grow dynamically—perfect for arrays and objects.

> I’ve abstracted away the memory addresses to show the values of each variable. 
>
> However, don’t forget that in actuality the variable points to a memory address, which then holds a value. 

![](https://miro.medium.com/max/700/1*E5Y5QBkntO31o4Al2-_YOA.jpeg)

---

```js
let myArray = []
```

When you declare a variable “myArray” and assign it a non-primitive data type like “[]”, this is what happens in memory:

- Create a unique identifier for your variable `myArray`
- Allocate an address in memory (will be assigned at runtime).
- Store a value of a memory address allocated on the heap (will be assigned at runtime).
- The memory address on the heap stores the value assigned (the empty array []).

> When myArray is declared, a memory address is allocated on the call stack, and the value is a memory address that is allocated on the heap. The value stored on the heap is the actual empty array. Visualized, it looks like this:

![](https://miro.medium.com/max/700/1*CPnnVIgE0tQVbxIja_C-_A.jpeg)

![](https://miro.medium.com/max/700/1*0x_h4Q0eu-rpA0YxHJBJdg.jpeg)

From here, we could push, pop, or do whatever we wanted to to our array.

```js
myArray.push("first")
myArray.push("second")
myArray.push("third")
myArray.push("fourth")
myArray.pop()
```

![](https://miro.medium.com/max/700/1*XfqW2Xh5oJrChzhRAauf9Q.jpeg)


**[⬆ Back to Top](#data-structures--memory)**


## 8.9 Defining & interpreting change (in memory)


```js
const myArray = []
```

When myArray is declared, a memory address is allocated on the call stack, and the value is a memory address that is allocated on the heap. The value stored on the heap is the actual empty array. Visualized, it looks like this:

![](https://miro.medium.com/max/700/1*60iWMS6aDYFoTU1pcIgXeQ.jpeg)

If we were to do this:

```js
myArray.push(1)
myArray.push(2)
myArray.push(3)
myArray.push(4)
myArray.push(5)
```

![](https://miro.medium.com/max/700/1*rphzalOnHm5FseLVov498g.jpeg)



… this pushes numbers onto the array that exists in the heap. 

However, the **memory address of “myArray” has not changed**. 

This is why although “myArray” was declared with const, no error is thrown. 

“myArray” still equals “0458AFCZX91”, which has a value of another memory address “22VVCX011”, which has a value of the array on the heap.

---

### The correct way to interpret “change” is a change in memory address. 

### Let allows you to change memory addresses. 

### Const does not allow you to change memory addresses.

---

**[⬆ Back to Top](#data-structures--memory)**



# 9 Algorithms & time complexity


**Time complexity** is the number of operations an algorithm performs to complete its task (considering that each operation takes the same amount of time). 

> In other words, the time complexity is how many operations a program takes to process a given input.

**Space complexity** is a measure of the amount of working storage an algorithm needs. That means how much memory, in the worst case, is needed at any point in the algorithm. As with time complexity, we're mostly concerned with how the space needs grow, in big-O terms, as the size N of the input problem grows.

### You do not measure time complexity in seconds, but rather by how many operations are executed.

- The algorithm that performs the task in the smallest number of operations is considered the most efficient one in terms of the time complexity.

- The number of instructions executed by a program is affected by the input’s size and how their elements are arranged.




![](https://kajabi-storefronts-production.global.ssl.fastly.net/kajabi-storefronts-production/blogs/27029/images/CCI6Y7gVQNIePZRDT5rb_c1262ed75ecd53ae26372a6544c6e155.jpg)



---

### But why is it that time complexity is measured by the number of operations executed? 

Well, let’s say you want to sort an array of numbers: 

- If the elements are already sorted, the program will perform fewer operations. 

- On the contrary, if the items are in reverse order, it will require more time to get them sorted. 

- The time a program takes to execute is directly related to the input size and its arrangement.

---

### We can say for each algorithm have the following running times:

- Best-case time complexity (e.g., already sorted)

- Average-case time complexity (e.g., elements in random order)

- Worst-case time complexity (e.g., input elements in reversed order) 

> We usually care more about the worst-case time complexity (We hope for the best but prepare for the worst).

**[⬆ Back to Top](#algorithms--time-complexity)**



## 9.1 Big-O notation


Big O notation is one of the most fundamental tools for computer scientists to analyze the cost of an algorithm. It is a good practice for software engineers to understand in-depth as well.

In plain words, Big O notation describes the complexity of your code using algebraic terms.


> A logarithm is the power to which a number must be raised in order to get some other number. 
>
> For example, the base ten logarithm of 100 is 2, because ten raised to the power of two is 100: log 100 = 2.

![](https://miro.medium.com/max/749/1*w4qanwIVl9Ec8A4LDgY_3Q.jpeg)


![](https://miro.medium.com/max/1200/1*j8fUQjaUlmrQEN_udU0_TQ.jpeg)

---

### O(1) - constant time

This is the ideal, no matter how many items there are, whether one or one million, the amount of time to complete will remain the same and that amount is a single operation - `O(1)`.

Pushing to an array, getting an item at a particular index, adding a child element, etc, will all take the same amount of time regardless of the array length.

### n = 64
### O(1) = 1 operation

---

### O(n) - linear time
By default, all loops are an example of linear growth because there is a one-to-one relationship between the data size and time to completion. 

So an array with 1,000 times more items will take exactly 1,000 times longer.

### n = 64
### O(n) = 64 operations

---

### O(n^2) - quadratic time

`O(n^2)` is exponential growth.

Need to find a matching pair for each item in an array? 

Putting a loop inside a loop is great way of turning an array of 1,000 items into a million operation search that’ll freeze your browser. 

It’s always better to have to do 2,000 operations over two separate loops than a million with two nested loops.

### n = 64
### O(n^2) = 4069 operations

---

### O(log n) - logarithmic time

Given a person's name, find the phone number by picking a random point about halfway through the part of the book you haven't searched yet, then checking to see whether the person's name is at that point. Then repeat the process about halfway through the part of the book where the person's name lies. (This is a **binary search** for a person's name.)

O(log N) basically means time goes up linearly while the n goes up exponentially. So if it takes 1 second to compute 10 elements, it will take 2 seconds to compute 100 elements, 3 seconds to compute 1000 elements, and so on.

​It is O(log n) when we do divide and conquer type of algorithms e.g binary search.

With this 'divide-and-conquer’ approach, the amount of time to find something will still change depending on the size of the dictionary but at nowhere near the rate of `O(n)`. 

Because it searches in progressively more specific sections without looking at most of the data, a search through a thousand items may take less than 10 operations while a million may take less than 20, getting you the most bang for your buck.

### n = 64
### O(log n) = 6 operations

---

### O(2^n) - exponential time

Exponential Time complexity denotes an algorithm whose growth doubles with each additon to the input data set. If you know of other exponential growth patterns, this works in much the same way. The time complexity starts off very shallow, rising at an ever-increasing rate until the end.

### n = 16
### O(2^n) = 65536 operations

---

### O(n!) - factorial time

Finally, one of the worst possibilities, **factorial growth**. The textbook example of this is the travelling salesman problem. If you have a bunch of cities of varying distance, how do you find the shortest possible route that goes between all of them and returns to the starting point? 

The brute force method would be to check the distance between every possible configuration between each city, which would be a factorial and quickly get out of hand.

### n = 16
### O(n!) = 20922789888000 operations

---

**[⬆ Back to Top](#algorithms--time-complexity)**



## 9.2 CRUD operations on data structures

### CRUD = create, read, update & delete

CRUD are the four basic operations of persistent storage.

They also adhere to time complexity.

![](https://i.stack.imgur.com/l56sp.png)

**[⬆ Back to Top](#algorithms--time-complexity)**






## 9.3 Sorting algorithms

In computer science, a sorting algorithm is an algorithm that puts elements of a list in a certain order.

A sorting algorithm is an algorithm made up of a series of instructions that takes an array as input, performs specified operations on the array, sometimes called a list, and outputs an array of elements in a certain order.

![](https://miro.medium.com/max/2628/1*X1hZCxNdfgZ0sT_2tynPKA.png)

---

### Each sorting algorithm can be fastest for certain scenarios. 

There are many types of sorting algorithm present with time complexities O(N²), O(N*logN) and even O(N). 

Then why isn't the algorithm with O(N) time complexitiy the fastest?

Let's break down the scenarios where each algorithm would be best:

### Bubble Sort

This algorithm is almost never used because of its O(N²) time complexitiy. But in computer graphics, it is popular to detect a very small error (like swap of two elements) in almost sorted array.

### Selection Sort

This algorithm is used when the input array's length is around 10 - 20. Usually, insertion sort is preferred over selection sort. But selection sort takes less write than insertion sort. That's why sometimes, selection sort is preferred over insertion sort.

### Insertion Sort

This algorithm is used when the input array's length is around 10 - 20. This algorithm is mostly preferred because its an adaptive algorithm i.e it improves its time complexitiy from O(N²) to even O(N*logN) by taking advantage of a sorted subarray if its present in the input array.

### Quicksort

This algorithm is used when the input array's length is very very high. This is a recursive algorithm with time complexity O(N*logN). This is usually preferred over mergesort. But we should select the pivot element properly. If we take the wrong pivot element, its time complexitiy can reach O(N²).

### Mergesort

This algorithm is used when the input array's length is very very high and it is usually used to sort linked list. Its time complexitiy is O(N*logN). But quicksort is preferred over mergesort. Because mergesort has O(N) extra space complexity where quicksort's space complexity is O(1).

### Counting Sort

The time complexity is O(N + k) where k is the largest integer present in the input array. This algorithm is only used when the input array's length is very very high and the largest element (k) present in the array is smaller than the length of array (N). For example, sort an array of length around a billion containing age of people. Here k can be maximum around 150 and length of the input array is 10 crore.

### Thus, each algorithm is fastest in certain situations.


**[⬆ Back to Top](#algorithms--time-complexity)**


## 9.4 Quick sort

**Quick Sort** is a sorting algorithm that follows the Divide and Conquer approach. It divides elements into smaller parts based on some condition and performing the sort operations on those divided smaller parts.

Quick Sort algorithm is one of the most used and popular algorithms in any programming language. 

Quicksort is a logarithmic-time algorithm, in other words, it has a Big O notation of **O(log n)** and depending on the way you implement it, it can be up to 2x or even 3x faster than Merge Sort or Heap Sort.

![](https://lh3.googleusercontent.com/pw/ACtC-3ffMGXxda36cmTyM8zDCbAvFPaEFdN9YWtdzeVPdhyPebpavRSESWBd6womQ3dDs4B3xumPOwVph7iOq-LqxgWt5063aVKVbtahOPQfV4dU1_-LmzHy2ZSeSfrnBeNYTMyGeixnrEB1N-gInTThj8WJ=w480-h288-no?authuser=0)

--- 

### Quick sort visual vs merge sort visual

![](https://cdn-images-1.medium.com/max/708/1*9Ydg_JYZ7m50kQW8nBH9Yg.png)
> Resembes a regular tree and an inverted tree



**[⬆ Back to Top](#algorithms--time-complexity)**

## 9.5 Merge sort

**Merge sort** is a sorting algorithm that uses the “divide and conquer” concept.

Given an array, we first divide it in the middle and we get 2 arrays.

We recursively perform this operation, until we get to arrays of 1 element.

The time complexity of MergeSort is **O(n*Log n)** in all the 3 cases (worst, average and best) as the mergesort always divides the array into two halves and takes linear time to merge two halves.

![](https://upload.wikimedia.org/wikipedia/commons/c/cc/Merge-sort-example-300px.gif)

---

### Quick sort visual vs merge sort visual

![](https://cdn-images-1.medium.com/max/708/1*9Ydg_JYZ7m50kQW8nBH9Yg.png)
> Resembes a regular tree and an inverted tree


**[⬆ Back to Top](#algorithms--time-complexity)**

## 9.6 Insertion sort

We look at the array as two parts, the sorted and unsorted, with every time we find a new value we loop back to find its place in the sorted half. 

With each addition our sorted group grows until it is the whole array.

Insertion sort has two nested loops, which means that as the number of elements n in the array arr grows it will take approximately n * n longer to perform the sorting. 

In big-O notation, this will be represented like **O(n^2)**.

---

![](https://upload.wikimedia.org/wikipedia/commons/9/9c/Insertion-sort-example.gif)

![](https://www.alphacodingskills.com/cs/img/insertion-sort.PNG)

**[⬆ Back to Top](#algorithms--time-complexity)**


## 9.7 Search algorithms

In computer science, a search algorithm is any algorithm which solves the search problem, namely, to retrieve information stored within some data structure, or calculated in the search space of a problem domain, either with discrete or continuous values.

It is the step-by-step procedure used to locate specific data among a collection of data. It is considered a fundamental procedure in computing. In computer science, when searching for data, the difference between a fast application and a slower one often lies in the use of the proper search algorithm.

### Search Algorithms:

- Linear Search.
- Binary Search.
- Jump Search.
- Interpolation Search.
- Exponential Search.
- Sublist Search (Search a linked list in another list)
- Fibonacci Search.
- The Ubiquitous Binary Search.
- and more...

![](https://he-s3.s3.amazonaws.com/media/uploads/1e0079d.JPG)

**[⬆ Back to Top](#algorithms--time-complexity)**


## 9.8 Linear search

In computer science, a linear search or sequential search is a method for finding an element within a list. It sequentially checks each element of the list until a match is found or the whole list has been searched.

To calculate the Big O value we always look at the worst-case scenario.

### So the time complexity for linear search is O(n).

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Linear-Search.png)

```js
// Linear search
const linearSearch = (list, item) => {
  for (const [i, element] of list.entries()) {
    if (element === item) {
      return i
    }
  }
}

linearSearch(['a', 'b', 'c', 'd'], 'd') // 3 (index start at 0)
```

**[⬆ Back to Top](#algorithms--time-complexity)**


## 9.9 Binary search

**Binary Search**: Search a sorted array by repeatedly dividing the search interval in half. Begin with an interval covering the whole array. 

If the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half. Otherwise narrow it to the upper half. Repeatedly check until the value is found or the interval is empty.

To calculate the Big O value we always look at the worst-case scenario.

### So the time complexity for binary search is O(log n).


![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Binary-Search.png)

```js
// Binary search
const binarySearch = (list, item) => {
  let low = 0
  let high = list.length - 1

  while (low <= high) {
    const mid = Math.floor((low + high) / 2)
    const guess = list[mid]

    if (guess === item) {
      return mid
    }

    if (guess > item) {
      high = mid - 1
    } else {
      low = mid + 1
    }
  }

  return null //if not found
}

console.log(binarySearch([1, 2, 3, 4, 5], 1)) // 0
console.log(binarySearch([1, 2, 3, 4, 5], 5)) // 4

console.log(binarySearch([1, 2, 3, 4, 5], 6)) // null
```

**[⬆ Back to Top](#algorithms--time-complexity)**

---
---
---

# 💯 - 🎊🎊🎊 🙌 CONGRATULATIONS! 🥳 🎊🎊🎊

![](https://pbs.twimg.com/media/EQ5qdaxXUAEosoF.jpg)

---
