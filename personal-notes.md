# HTML, CSS and JavaScript: Building the Web

[HTML, CSS and JavaScript: Building the Web](https://www.linkedin.com/learning/html-css-and-javascript-building-the-web/hello-web-development?autoSkip=true&resume=false)

## 1. Welcome to Your Development Environment

- HTML: Hypertext Markup Language
- CSS: Cascading Style Sheets
- JavaScript: add interactivity and functionality

## 2. HTML Development

- elements: opening tag, content and closing tag
- tags: keywords surrounded by angle brackets
- self-closing tag (e.g. meta, link, ...)
- attributes: used to specify properties, e.g character encoding, viewport setting, ids, classes, alternative texts for accessibility, etc
  - if using multiple attributes, separate each attribute with a space
  - usually: attribute name on the left, followed by equal sign and the value to the right between 2 double quotes
- accessibility: ensure that all users, including those with disabilities, can access and intercat with our webpage
- semantic elements: help understand the structure and hierarchy; e.g. table, header, footer, section, ...

### Tags

- <!DOCTYPE html>: tells the browser we are using HTML5 - important to ensure modern web standards are followed
- <html>: root of the document, everything goes inside of it
- <head>: meta information (title, ...)
- <body>: main content
- <meta>: provides information about the document (author, description, keywords, ...)
- <link>: e.g. css file 
- <script>: javascript file
- <div>: container to group content
- <img>: images 


### Attributes

- lang="en": specify language of the content, useful for accessibility and Search Engine Optimization (SEO)
- charset="utf-8": specify the character encoding for a document ensuring that text is displayed properly
  - utf-8: standard practice because it supports a wide range of characters and symbols
- name="viewport" content="width=device-width, initial-scale=1.0": ensure web pages scale properly on different devices
- rel="stylesheet": specifies the relationship as a stylesheet
- href="src/styles.css": "href" provides the path
- src="src/main.js": provides the path
- defer: ensure the script loads after the HTML is fully loaded and parsed which helps improve page load speed and performance
- id=: uniquely identifies an element
- class=: apply the same styles to multiple elements
- alt=: provide text descriptions

## CSS Styling

- commenting in CSS: /* */
- curly braces
- semi-colons ";" in curly braces
- cascading: multiple styles can apply to the same element; the browser chooses the final one based on priority, specificity, or order
- inheritance: allows color styles to be passed down from "parent" to "child"
- selectors:
  - element
  - id
  - class
  - descendant, e.g. if you wnat to resize all imgs inside a div
  - pseudo-class: picks elements based on a state, e.g. hover
- properties: to specify color, size, positioning, etc
- animations: dynamic elements (motion and visual effects)
  - keyframe: specify intermiediate frames and CSS will generate the in-between frames
- transitions: making sure the transition between the states look smooth

### Style Priority

- inline html styling > css styling
- css specific style for element > inheritance from other elements

## JavaScript Development

- commands to create variables:
  - let: block-scoped, can be reassigned
  - const: block-scoped, cannot be reassigned (constant)
  - var: function-scoped, avoid using (older syntax)
- end of line → ";" (except of end of blocks of function, if and for)
- "{}" used for fonctions, conditions and loops
- console.log(): logs
- closures: allows an inner function to access variables from its outer function

### Document Object Model (DOM)

- structure of a web page as a tree of objects
- the  DOM is the API of the browser
- JavaScript is the offical language of the browser

### Event Handling

- allows to listen and respond to mouse/keyboard click, drag and more
- event listener: function that wait for a specific event to occur and then execute code in response
  - event types: clciks, key presses, changes in the doc
  - targets`every event is associated with a particular element in the DOM
  - event handler function: code to be exectued when the event occurs
  - adding event listener: crucial step to attach an event listener to a particular element
- event.preventDefault: prevents any default actions that might occur