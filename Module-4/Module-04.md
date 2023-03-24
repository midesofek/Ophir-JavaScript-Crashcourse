# Module-04: Using JavaScript Frameworks and Libraries - EthersJs, React JS, AngularJS

As a developer or an aspiring developer, you would work with lots of programming libraries and frameworks (a lot of them!) and possibly build one yourself one day.

But before we arrive at that destination let's look at programming libraries and frameworks: what they are, their significance and some very popular frameworks you will work with as a web3 developer.

In this lesson, you'll learn:

- The meaning of libraries and frameworks in programming
- The importance of programming libraries and frameworks
- The major distinction between programming libraries and frameworks

Then you'll also learn the following frameworks, what they are, their importance and why you should use them.

- EthersJs
- ReactJs
- AngularJs

## What are programming libraries?

A programming library is a pile of already-built code that can be used and reused by developers to carry out specific tasks or solve complex coding problems.

For instance, if you were to convert a number to strings in Solidity you would have to write a code like this:

```
E.g:

```

However, using the "Strings" programming library by Openzeppelin you can implement the same above functionality by simply calling a single function.

```
E.g:

```

Also, with the help of libraries like Openzeppelin, you can deploy fully-fledged NFTs in barely 20 lines of code.

```
E.g:

```

How smooth could it get?

That's the importance of working with programming libraries (at least the secure and trusted ones), they make the coding process more efficient and less cumbersome.

Before we move with you next I am on our agenda there is also the EthersJs library - a very powerful, complete, and well-packed library for interacting with EVM compatible blockchains.

### EthersJs

EthersJs takes away the abstraction so you can send, read, or write messages to the blockchain without having to directly deal with all of the complexity that comes with Ethereum.

For instance, we can read the balance of any wallet address on the Polygon blockchain through the EthersJs library.

```
Sample code below:

```

> Notes as a web3 developer you would work with it as there's a lot so you might want to get familiar with the EthersJs documentation.

## What are Programming Frameworks?

In programming, a framework is a compact tool that provides a developer with a structural layout and necessary tools for building powerful applications.

Unlike libraries, frameworks give developers access to more than "written codes" and "already solved problems".

Some frameworks usually include integration with SDKs (Software Development Kits), application interfaces and other tools that are integral to building secure and efficient web applications.

Let's now take a look at some very popular JavaScript frameworks.

### ReactJS

React JS (or React in short) is an open-source front-end JavaScript library used for building user interfaces for any kind of web application.

By its history, React was built and is still maintained by Facebook (now Meta) in 2011 (specifically by a man named Jordan Walke).

React is very powerful and versatile and has grown to become the go-to application for almost every web3 developer out there.

Similar to our clarification earlier (on programming libraries), some believe React is merely a library. But, in actual fact, this is "wayyyy" far from the truth.

The return of functionalities inbuilt with React like:

Using a virtual DOM: to efficiently update the UI without even refreshing a page;
The JSX syntax: i.e. JavaScript XML, a mix of HTML and JS;
A Declarative Programming Model - to handle the state of the web page;
Server-Side rendering support: to improve SEO performance.
Web3 integration - react supports a host of web3 functionalities.

Despite all these vast functionalities, React is pretty easy to learn and work with, which is why it is so popular and well-cherished in the web development community.

To help you understand the importance of ReactJs as a powerful JavaScript framework, take a look at big companies that use react to build their web applications:

Facebook
Instagram
WhatsApp
Netflix
Dropbox
Uber
Reddit
Shopify
PayPal
YahooMail (implemented in 2015!)

… and a host of others!

#### React & ReactNative

A salient point to note here is that React is used to build web applications/websites while ReactNative (also a part of react) is used to build mobile applications.

### AngularJS

Another interesting open-source JavaScript framework to consider is definitely Angularjs.

Angularjs is a structural framework that enables developers to build single-page applications (SPAs) and to bring dynamism to static web pages built with HTML.

A notable feature of angular JS is its ability to enable developers to write clear and concise codes through dynamic binding and dependency injection.

Unlike the previous libraries and frameworks discussed in this lesson, development and updates to the Angularjs framework have been halted since support for the framework was pulled back in January 2022.

> You can read more about it here

**🤔 Why?**

The developers of angularjs altered updates on the framework in favour of a more robust version of their well-cherished framework named Angular.

This gives us a clear indication that there is a difference between Angular and Angularjs

#### The Distinction between Angular and Angularjs

When compared to Angularjs, Angular is much more efficient, structured and fast.

Some of the most obvious limitations of angular JS is that it is only built in Javascript and only supports JavaScript. It doesn't support mobile browsers, doesn't have a CLI tool and is less manageable compared to Angular.

Angular resolved all these limitations.

Angular is written in typescript and comes with its own CLI tool (very good for DX - developer experience). Also, Angular is supported by all the most popular mobile browsers.

So considering all of these it is safe to conclude that Angular is a better alternative to Angularjs - although you might need some Typescript knowledge to work with it.

**💡 Which should you choose: React vs Angularjs/Angular **

Given the smooth integration React gives to web3 and the large support given to it by the web3 community, React is a better option for web3 frontend development.

So, without beating around the bush, Reactjs should be your go-to option for web3 frontend development.
