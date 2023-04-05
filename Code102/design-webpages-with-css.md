# Design Webpages with CSS: Class 5

## Read

[What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

## Read and Experiment

[How to Add CSS](https://www.w3schools.com/css/css_howto.asp)
[CSS Color](https://www.w3schools.com/cssref/pr_text_color.php)

## Skim

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)

1.**What is the purpose of CSS?**

CSS stands for Cascading Style Sheets and is used to stylize and lay out your documents or webpages in the way you would like them to be visually presented to users.

2.**What are the three ways to insert CSS into your project?**

CSS can be inserted:

* ***External CSS*** - a separate CSS file connected to html. Each HTML page must include a reference to the external style sheet file inside the \<link> element, inside the head section. An external style sheet can be written in any text editor, and must be saved with a .css extension.

* ***Internal CSS*** - CSS is built into the html file. An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the \<style> element, inside the head section.

* ***Inline CSS*** - CSS is built into the html element itself. An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
***An inline style loses many of the advantages of a style sheet (by mixing content with presentation). Use this method sparingly.***

3.**Write an example of a CSS rule that would give all \<p> elements red text.**

p \{  
color: red;  
\}

[CF Reading Journal Home](../README.md)
