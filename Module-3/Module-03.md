# Module-03: UNDERSTANDING THE BASICS OF EVENTS AND EVENT HANDLING IN JAVASCRIPT

In this lesson, you’ll learn:

- What events mean in Javscripts;
- Common examples of events in Javascript;
- What event handling entails in Javascript;
- The difference between events listeners and event handlers; and
- How to respond to user events (clicks && keyboard presses) with Javascript

## What are events in Javascript?

Simply put, events are those things that occur within an application’s environment.

This could be a user click, cursor hover, keyboard press, key hold, page refresh, page scroll, form open, form submission, etc. The list is almost endless as there are lots of ‘things’ that could happen when a user interacts with a website/application.

However, as developers, what is important to us is ‘catching’ and reacting to this events where necessary. And to do this, we attach an **event listener** (or an event handler) to such event.

```
Click example (1 line)

```

## Event Listeners vs Event Handlers

The terms event listeners and event handlers are often used interchangeably, but that doesn’t imply they mean the same thing. There's a difference between an event listener and an event handler.

An **event listener** awaits the trigger of the specified event while the **event handler** is the code implementation that responds to the event occurrence.

## Common Events in Javascript

We get a bunch of these events from user engagements with the contents on a website. This is usually referred to as HTML events.

Some of these events include the following:

- onClick
- onKeydown
- onLoad
- onmouseover
- onChange

> You can find a lot more here

## Handling Events in JS

In JS, events handlers are used to respond to user actions and to do sth when such event is 'fired' - _the conventional word to use_.

For instance, we may set an event handler (i.e. a code block) to pop open a page when a button is clicked.

```
E.g:

```

In this case, what kind of event is triggered here?

Yes that's right, a button click! so the appropriate event to be handled here is the "onclick" event.

Let's now dive into how to respond to user clicks and keyboard presses with JavaScript.

## How to respond to User Events - Clicks

## How to respond to User Events - Keyboard Presses
