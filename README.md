# CSS IS FUN 😜

## CSS (Cascading Style Sheets)
 CSS (Cascading Style Sheets) is a style sheet language used to describe the presentation of a document written in HTML. It controls the visual appearance of web pages by defining how HTML elements are displayed on screens, in print, or other media.

 It provides a set of rules and properties that define how elements on a webpage should be displayed,
including their layout, colors, fonts, sizes, and more ...

### 🎨 Syntax Breakdown
CSS syntax simply  consist of a selector
and block. Each block contains a sequence of
property and value pairings.

<img src='assets\Syntax.png'>
Selector will target the HTML element that
needs to be styled. Our property and value
pairings are separated with a colon and ended
with a semicolon. The entire block is then
wrapped in curly brackets.

### 🎨 CSS Comments
Comments allow us to document our source code
without affecting the output of the website. The
syntax for comments is simple and as follows:

<img src='assets\comments.png'>


### 🎨 CSS Specificity

CSS specificity is a set of rules that determines which styles are applied to an HTML element when multiple conflicting CSS rules target the same element. Specificity helps browsers decide which styles take precedence.

The specificity of a CSS rule is calculated based on the following factors, ranked in order of importance:

<img src='assets\specificity.png' width='500'>



## Table of contents:
 

| No. | Content                                                                                                                                                         |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [🎨 Selectors and Specificity](#)           |
| 2   | [🎨 Typography and Colors](#)                 |
| 3   | [🎨 Box Model](#)                                                        |
| 4   | [🎨 Display and Positioning](#)                                                                                 |
| 5   | [🎨 CSS Grid](#)                                                                     |
| 6   | [🎨 CSS Flexbox](#)                                                                  |
| 7   | [🎨 CSS Transforms](#)                                                                 |
| 8   | [🎨 Animations and Transitions](#)                                                                 |
| 9   | [🎨 CSS Variables](#)                                                                 |
| 10   | [🎨 Media Queries - Responsive Design](#)                                                                |




## 🎨 Selectors
CSS selectors are patterns used to select and style HTML elements. They allow you to target specific elements or groups of elements in an HTML document for styling. Here are some common CSS selectors:

[ Basic Selectors ]
#### Class selectors:
Class selectors allows us to create reusable
style blocks, then apply them in our HTML. An
element can inherit from multiple classes

<img src='assets\class.png'>



#### ID:
An ID selector will target an HTML element that
has a specific ID attribute applied. ID is usually
reserved for styling framework elements

<img src='assets\ID.png'>



#### Tag/Element:
Tag selectors will target any HTML elements of
a given tag or type. Their primary use case is to
reset the default styling applied by browsers

<img src='assets\tag.png'>



#### Universal:
The universal selector will target all HTML
elements. It’s only real use case is to reset
certain properties on all elements.

<img src='assets\universal.png'>








