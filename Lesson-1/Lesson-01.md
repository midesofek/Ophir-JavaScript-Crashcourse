# Crash-Course-01: JavaScript Basics and Fundamentals

Without a doubt, JavaScript is currently the biggest, most popular and most widely used programming language as far as web3 development is concerned.
As a result, a solid understanding of the JavaScript syntax and fundamentals is very important.

In this crash course, we will go over the following:

- Data types in javascript
- Using the _typeof_ operator
- Commenting in Javascript
- How to declare variables in javascript
- The naming convention in Javascript.

## Introduction to Data Types in Javascript

Just like we have alphabets symbols and emoticons in our normal traditional languages EG English Spanish Chinese etc we also have something similar of similar nature in programming languages. They are called Data Types.
Data types are the various ways to represent values in programming.
In JS, there are two major ways in which values are represented:
Primitive values (our focus in this course)
Object values.

When looking at primitive values or primitive data types there are seven(7) major data types. They include:

1. Number
2. Strings
3. Boolean
4. Undefined
5. Null
6. Big Int
7. Symbol

Let's now look into each of these data types.

### Number

The number data type includes integers and float point numbers (ie decimals)
Integers: e.g: 10,9,8,7….3,2,1,0,-1,-2,-100, etc
Decimals: -10.2, -8.7, -3.66, -0.55, -1.1, etc

### Strings

A string in Javascript is an array of characters represented between double quotes (" ")single quotes (' ') or backticks (``).
E.g:

```




```

### Boolean

A boolean value is either true or false.

```
e.g:


```

### Undefined

As the name implies, a variable is `undefined` in Javascript if we don't assign a value to it.
Another occurrences where is a function does not return a value.

```
e.g:
```

### Null

A null data type in JS refers to an empty value.

```
let birthDate = null;
console.log(birthDate);
```

### BigInt

A big int data type is a numeric primitive that can hold and store large integers (i.e. large numeric values) beyond what you can ordinarily store with the `number` data type (i.e `Number.Max_SAFE_INTEGER`)

### Symbol

The symbol data type represents primitive values that are unique and immutable.
A symbol data type is created using `Symbol()`

```
e.g:
```

## The Caveat in JS Data Types

It is important to note that unlike what you have in solidity and other statically typed languages, JavaScript has dynamic typing (i.e. it is dynamically typed).
This means that you don't need to declare the type. JavaScript does the type interpretation behind the scenes.

## The `typeof` operator

There are times during your coding process where you might want to <u>**check the data type**</u> of a variable in your code.

To do this, you can use the `typeof` operator to check the data type of a certain variable.

Illustration:

```
console.log(typeof 007) //returns number
console.log(typeof 'Ophir')//returns String
console.log(typeof ) //returns number

```

## Introduction to Comments in JavaScript

Comments are lines of code that are included in a code for readability. These lines of code are ignored by the compiler/computer engine.

Comments are used in almost every existing programming language out there. However, they are written in different ways across these languages.

In Javascript, there are two ways of writing comments:

- Single-line Comments
- Multi-line Comments

- **Single line comments**: this is declared using two forward slashes (//)

```
E.g: This is a comment
```

- **Multi-line Comments**: This is declared with (/\* \*/)

```
/*
This is a multi-line comment
In JS
*/
```

## How to Declare Variables in Javascript

A variable can be likened to a container that holds a certain value.

Variables are used to store data in a computer's memory, so it can be reassessed, reused and modified.

> Take note of these 3 things!

If you need to store a certain value, you declare a variable and store your value in it.

In Javascript, you can declare a variable in three (3) ways using let, const and var.

### Using Let

This is the flexible way of declaring variables. Variables declared with let can be modified, and reassigned and you can also change the data type.

```
E.g:




```

### Using Const

`const` refers to constant. Values stored in a `const` are immutable (i.e. they cannot be changed).

```
E.g:


```

### Using var

This is the old way of defining variables prior to ES6. There are a lot of vulnerabilities surrounding using var to declare variables in JavaScript.

🤔 You may wonder if it has issues why not remove it?

Well, var is preserved for legacy reasons.

A lot of old applications and websites still run with the `var` syntax, hence blocking it out will crash a large portion of websites and apps on the internet.

#### 💡 So which should you use?

As a rule of thumb, always use `const`. However, where you need to reassign a variable, then use `let`. But NEVER use `var`.

> Pretend it doesn't exist!

## Naming Conventions

When it comes to naming variables in Javascript, the universally approved method is to follow the `camelCasing` syntax.

That is, sth like this:

```
E.g:




```

There are some other rules to bear in mind, they include the following:

- Your variable name should never begin with a number
- Do not include special symbols except the dollar sign (\$) and underscore (\_)
- Never use the hyphen (-) to space variable names, and
- Do not include a space between words when naming variables.

```
E.g:


```
