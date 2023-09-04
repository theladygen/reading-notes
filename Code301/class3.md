# Class 3

## Reading

### [React Docs - lists and keys}(https://legacy.reactjs.org/docs/lists-and-keys.html)

1.***What does .map() return?***

This iterates over an array and returns a new array that changes the original array according to whatever transformation function it's given.

2.***If I want to loop through an array and display each value in JSX, how do I do that in React?***

.map() within the render method of a component

3.***Each list item needs a unique ____.***

Key

4.***What is the purpose of a key?***

Keys help React identify which items have changed, are added, or are removed.

### [The Spread Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

1.***What is the spread operator?***

The spread (...) syntax allows an iterable, such as an array or string, to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected.

2.***List 4 things that the spread operator can do.***

copying arrays, copying objects, combining arrays, combining objects

3.***Give an example of using the spread operator to combine two arrays.***

const parts = ["shoulders", "knees"];

const lyrics = ["head", ...parts, "and", "toes"];

//  ["head", "shoulders", "knees", "and", "toes"]

4.***Give an example of using the spread operator to add a new item to an array.***

let arr1 = [0, 1, 2];

const arr2 = [3, 4, 5];

arr1 = [...arr1, ...arr2];

// arr1 is now [0, 1, 2, 3, 4, 5]

5.***Give an example of using the spread operator to combine two objects into one.***

const obj1 = { foo: "bar", x: 42 };

const obj2 = { foo: "baz", y: 13 };

const clonedObj = { ...obj1 };

// { foo: "bar", x: 42 }

const mergedObj = { ...obj1, ...obj2 };

// { foo: "baz", x: 42, y: 13 }

## Videos

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1.***In the video, what is the first step that the developer does to pass functions between components?***

Creates a function where state needs to be changed

2.***In your own words, what does the increment function do?***

Iterates through an array and increments the count to each item then triggers state to update

3.***How can you pass a method from a parent component into a child component?***

It passes as a prop

4.***How does the child component invoke a method that was passed to it from a parent component?***

The child component accesses it as a prop

## Bookmark and Review

[React Tutorial through ‘Declaring a Winner’](https://react.dev/learn/tutorial-tic-tac-toe)
[React Docs - Lifting State Up](https://legacy.reactjs.org/docs/lifting-state-up.html)
