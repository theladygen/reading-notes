# Class 5

## Reading

[React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)

1.***What is the `single responsibility principle` and how does it apply to components?***

`Single responsibility principle` is the idea that a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2.***What does it mean to build a ‘static’ version of your application?***

A `static` version is building a version that renders the UI from your data model without adding any interactivity. The components will only return JSX.

3.***Once you have a static application, what do you need to add?***

State.

4.***What are the three questions you can ask to determine if something is state?***

* Does it remain unchanged over time? If so, it isn’t state.
* Is it passed in from a parent via props? If so, it isn’t state.
* Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!

5.***How can you identify where state needs to live?***

For each piece of state in your application:

* Identify every component that renders something based on that state.
* Find their closest common parent component—a component above them all in the hierarchy.
* Decide where the state should live:
Often, you can put the state directly into their common parent.
You can also put the state into some component above their common parent. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1.***What is a “higher-order function”?***

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

2.***Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?***

function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

Line 2 is a function inside line 1. It remembers the 'n' value from the outer function and compared and returns the comparison of another value, 'm', to 'n' and determines if 'm' is greater than 'n'.

3.***Explain how either `map` or `reduce` operates, with regards to higher-order functions.***

`map` applies a function to each element of an array and returns a new array of the same length.

## Things I Want to Know More About

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
