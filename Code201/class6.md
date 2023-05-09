# Class 6

## Reading

### [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1.**How would you describe an object to a non-technical friend you grew up with?**

An object is a collection of data and/or functionality that relates to each other. Usually objects consist of several variables (containers that can hold values) and functions (which perform a task). Functions are called properties and methods when they are inside objects.

2.**What are some advantages to creating object literals?**

It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.

3.**How do objects differ from arrays?**

Objects look very similar to how you access the items in an array, and it is basically the same thing — instead of using an index number to select an item, you are using the name associated with each member's value. It is no wonder that objects are sometimes called associative arrays — they map strings to values in the same way that arrays map numbers to values. However, where arrays values are accessed in sequential order you can access values in an object selectively.

4.**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

If you wanted to access a property using a variable or a special character you would need to use bracket notation.

5.**Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?**

```text
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

The `this` keyword refers to the current object the code is being written inside, which in this case refers to 'Spot' and 2. When you only have to create a single object literal, it's not so useful. But if you create more than one, `this` enables you to use the same method definition for every object you create.

### [Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1.**What is the DOM?**

DOM is the data representation of the objects that comprise the structure and content of a document on the web.

2.**Briefly describe the relationship between the DOM and JavaScript.**

The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

## Bookmark and Review

[Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

[What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Things I Want to Know More About

Objects! It's sandbox time.

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
