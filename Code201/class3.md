# Class 3

Expanding and continuing to build upon the beginning layers we've seen this far in CSS and JS is really helping to make certain aspects click one at a time. I'm trying to gain more memory for the terminology so I can articulate questions better.

## Reading

### [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul).

1.**When should you use an `unordered list` in your HTML document?**

You should use unordered lists for groupings of items that don't have a numerical ordering, and their order in the list is meaningless.

2.**How do you change the `bullet style` of unordered list items?**

Nesting within unordered lists will change the bullet style.

3.**When should you use an `ordered list` vs an `unordered list` in your HTML document?**

You should use an ordered list when the order is meaningful and an unordered list when the order is meaningless.

4.**Describe two ways you can change the numbers on `list items` provided by an `ordered list`?**

You can use the start attribute to begin an ordered list at whatever number you wish, or the Roman numeral type to change the numbering to Roman numberals.

### [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model).

1.**Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?**

Padding is like the protective gear on a football player, surrounding him. Margin is the bodyguard team around him keeping the paparazzi from getting too close.

2.**List and describe the four parts of an HTML elements box as referred to by the `box model`.**

The center is the content, which is surrounded by padding. The edge of this is the border. Outside the border is the margin.

### [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays).

[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators).

[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals).

[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code).

1.**What `data types` can you store inside of an `Array`?**

An array can store various data types such as strings, numbers, objects, or other arrays. Data types can also be mixed in a single array.

2.**Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

It is and you would access the values with console log, I believe.

 ```text
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

3.**List five shorthand operators for assignment in javascript and describe what they do.**

= used to assign a value to a variable.
+= addition operator performs addition (which is either numeric addition or string concatenation) on the two operands and assigns the result to the left operand.
-= subtraction operator performs subtraction on the two operands and assigns the result to the left operand.
*= multiplication operator performs multiplication on the two operands and assigns the result to the left operand.
/= division operator performs division on the two operands and assigns the result to the left operand.

4.**Read the code below and evaluate the last `expression` and explain what the result would be and why.**

It would equal the string of '10dog' because 10 + false = 10 + dog = '10dog'

 ```text
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ```

5.**Describe a real world example of when a conditional statement should be used in a JavaScript program.**

A conditional statement would be used in a calorie counting application, allowing the user to stay within their calorie target.

6.**Give an example of when a `Loop` is useful in JavaScript.**

A loop is useful when information is needed in filling out a form by not allowing a user to move forward until they input the needed information.

## Things I Want to Know More About

I need to keep playing with sandbox JavaScript tools with arrays, loops, etc. Read my JS for Kids book! lol

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
