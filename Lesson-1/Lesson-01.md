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

When looking at primitive values 4 primitive data types there are seven major data types. They include:

- Number
- Strings
- Boolean
- Undefined
- Null
- Symbol
- Big Int

Let's now look into each of these data types.

### Number

The number data type includes integers and float point numbers (ie decimals)
Integers: e.g: 10,9,8,7….3,2,1,0,-1,-2,-100, etc
Decimals: -10.2, -8.7, -3.66, -0.55, -1.1, etc

### Strings

Strings in Javascript is an array of characters represented between double quotes (" ")single quotes (' ') or backticks (``).
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
