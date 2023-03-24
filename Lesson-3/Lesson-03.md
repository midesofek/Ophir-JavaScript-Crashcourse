# Crash-Course-03: UNDERSTANDING THE BASICS OF EVENTS AND EVENT HANDLING IN JAVASCRIPT

In this lesson, we’ll address the concept of DOM and DoM manipulation from a theoretical and practical standpoint, so as to lay a solid background for you when we start using JS to interact with web pages.

## Course Overview

In this course, you’ll learn::

- What the DOM is in Javascript.
- What DOM Manipulation means.
- How to Select and manipulate HTML Elements
- How to Select and Manipulate CSS Styles
- How to remove classes from HTML elements
- How to add classes to HTML elements

Without much further ado, let’s dive straight into this

## What does DOM Mean in Javascript?

When we talk about the Document Object Model, we’re referring to a standard representation of HTML documents.

The DOM is a tree-structured representation of an HTML document that gives JS access to all elements, styles and attributes in an HTML document.

(IMAGE FROM W3S)

In essence, the DOM provides developers with a special object ‘document’ which serves as our entry point to select, manipulate, customise and add some interactivity to web pages built with HTML or XML.

Note, however, that the DOM is not a part of JS nor is it a programming language on its own. Instead, the DOM is a programming interface between web pages (or HTML documents) and scripting languages like Javascript/Python, etc.

> You can also work with the DOM in python!

Now, you may ask, _if the DOM is not part o JS, how then does it work with JS?_

Well, the DOM, DOM methods, and its properties is part of web APIs which are inbuilt into most browsers. So, when working with the DOM you may want to run your code directly with your browser’s Javascript engine

**🤔 Why?**

This is because DOM APIs are not an integral part of the NodeJs runtime. So, trying to access the DOM directly in NodeJs will not work. Although, you could get around this with third-party libraries like `jsDoM`, `Cheerio` and `xml2js`, you are not guaranteed optimum performance.

✅ **Solution**: When working with the DOM, it's best to run your code directly on your browser.

> To see a list of all the fundamental data types & interfaces available on the DOM API, check out <u> [this article by mdn](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction#fundamental_data_types)</u>

## What does DOM Manipulation mean in Javascript?

Before we delve into a practical illustration of some cool applications of the DOM, let’s set a detailed background to help you really understand what we’ll be doing in the subsequent sub-headings.

Let’s get started 🚀🚀

You’ve probably learnt that HTML, CSS and Javascript are used to build websites where HTML handles the content, CSS handles the presentation and styling of the content and JS is responsible for the connectivity and interactivity of the content.

In order to efficiently carry out its duty, Javascript needs a way to interact with HTML (and its CSS styling) to manipulate the document structure in one way or the other - to achieve some key objectives of the website/app.

In practice, when you build your web page with HTML and CSS, it is usually very static with less interactivity going on, so there’s a need for a way to add some functionality and interaction there.

This is where DOM manipulation comes into play!

So, you can say here that **DOM manipulation** is the process of using the DOM API to manipulate, change, add, remove, or modify elements, attributes and styles in an HTML document.

To help you better understand this concept, we’ll walk through some DOM manipulation techniques and a mini-application for you to play around with.

## DOM Manipulation in Practice
