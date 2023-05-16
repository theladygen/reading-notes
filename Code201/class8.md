# Class 8

## Reading

### [Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

1.**Flexbox is designed for one-dimensional content. Explain what this means.**

Flexbox works in a single direction, like columns or rows, and allows flexibility for content display depending on the existing space available, rather than sticking to rigid dimensions for the browser to follow. You can control alignment in one axis, a row or a column, not both together as in a grid.

2.**Explain the difference between the main axis and cross axis.**

The main axis can be set to run along either the row or the column. The cross axis will run in the other direction to the main axis.

3.**How can using certain properties of flexbox negatively impact accessibility?**

Accessibility can be negatively impacted by flexbox when using any properties that reorder the visual display away from how things are ordered in the HTML document. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

### [CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

Read up to “Flex-Flow Shorthand”

1.**What are some advantages of using flexbox over float?**
Using floats it would be difficult or impossible to do some things, like:

* Vertically centering a block of content inside its parent.

* Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

* Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

2.**How does this topic connect with your long term goals?**

Flexbox is an amazing tool for laying out a design in css. Long term I would absolutely like to be more fluent in the visual layout process of a website. Flexbox will help immensely.

## Bookmark and Review

[Learn CSS - Layout](https://web.dev/learn/css/layout/)

## Things I Want to Know More About

Flexbox and responsive website building. Forming a clearer grasp on the starts and ends with main and cross axis.

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
