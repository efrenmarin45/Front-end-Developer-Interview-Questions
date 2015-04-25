#Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* What is a recent technical challenge you experienced and how did you solve it?
* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
* Talk about your preferred development environment.
* Which version control systems are you familiar with?
* Can you describe your workflow when you create a web page?
* If you have 5 different stylesheets, how would you best integrate them into the site?
* Can you describe the difference between progressive enhancement and graceful degradation?
* How would you optimize a website's assets/resources?
* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
* Name 3 ways to decrease page load (perceived or actual load time).
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* Describe how you would create a simple slideshow page.
* What tools do you use to test your code's performance?
* If you could master one technology this year, what would it be?
* Explain the importance of standards and standards bodies.
* What is Flash of Unstyled Content? How do you avoid FOUC?
* Explain what ARIA and screenreaders are, and how to make a website accessible.
* Explain some of the pros and cons for CSS animations versus JavaScript animations.

#### HTML Questions:

* What does a `doctype` do?
* What's the difference between standards mode and quirks mode?
* What's the difference between HTML and XHTML?
* Are there any problems with serving pages as `application/xhtml+xml`?
* How do you serve a page with content in multiple languages?
* What kind of things must you be wary of when design or developing for multilingual sites?
* What are `data-` attributes good for?
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
* Describe the difference between `<script>`, `<script async>` and `<script defer>`.
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
* What is progressive rendering?

#### CSS Questions:

* What is the difference between classes and ID's in CSS?
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
* Describe Floats and how they work.
* Describe z-index and how stacking context is formed.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* How would you approach fixing browser-specific styling issues?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Any familiarity with styling SVG?
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector.
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* How is responsive design different from adaptive design?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?

#### JS Questions:
SALMAN
* Explain event delegation
immediately invoked function expression
http://davidwalsh.name/event-delegate
https://learn.jquery.com/events/event-delegation/
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* How do you go about testing your JavaScript?
* What do you think of AMD vs CommonJS?
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?

YUSUF
* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
* How do you organize your code? (module pattern, classical inheritance?)
* What's the difference between host objects and native objects?
* Explain `Function.prototype.bind`.
* Why is extending built in JavaScript objects not a good idea?
* Difference between document load event and document ready event?

DIEN
* Explain AJAX in as much detail as possible.
* Explain how JSONP works (and how it's not really AJAX). 
* What's the difference between feature detection, feature inference, and using the UA string?
* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
* Explain the same-origin policy with regards to JavaScript.
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```

JENNIFER
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
The conditional (ternary) operator is the only JavaScript operator that takes three operands. This operator is frequently used as a shortcut for the if statement.
Syntax: 
condition ? expr1 : expr2 
If condition is true, the operator returns the value of expr1; otherwise, it returns the value of expr2. 
Example: "The fee is " + (isMember ? "$2.00" : "$10.00")
The numbers (in an arithmetic operation) are called operands. The operation (to be performed between the two operands) is defined by an operator.

* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, `"buzz"` at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`

* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
http://lucybain.com/blog/2014/js-dont-touch-global-scope/
Why global variables are generally bad? 
    It's harder to read the code and reason about it when variables seem to appear out of thin air (but really from the global scope).
    Anyone can update a global variable from any point in the program at any time (and from any thread if there's more than one going).
    General code smell - if you're too lazy to put the variable only where it needs to be then what other corners are you cutting?
    It's probable that you'll encounter global variable name clashes. Since there's only one namespace you're more likely to double up on a variable name.
For JS specifically global variables can be particularly problematic. This is because JS defaults all variables to the global scope unless they are explicitly defined elsewhere. 

* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
The onload event occurs when an object has been loaded.
onload is most often used within the <body> element to execute a script once a web page has completely loaded all content (including images, script files, CSS files, etc.).  The onload event can be used to check the visitor's browser type and browser version, and load the proper version of the web page based on the information. The onload event can also be used to deal with cookies.

* Explain what a single page app is and how to make one SEO-friendly.
Single page app is a website in which all of the pages and content are on the same page but just on different sections of that page.  To make one SEO-friendly:
http://searchengineland.com/single-page-websites-seo-182506
1. Define Content Sections like separate webpage - h1 tag, relevant text to keywords, img alt tags
2. Place each section of content inside its own DIV. - <div id="services">...content...</div>
3. Use anchor links  - Ex: <a href="#art-design">Art + Design</a>

* What is the extent of your experience with Promises and/or their polyfills?
Promises work on newer browsers, but not  on older browsers. Polyfill (or polyfiller) is downloadable code which provides facilities that are not built into a web browser. It implements technology that a developer expects the browser to provide natively, providing a more uniform API landscape. To bring browsers that lack a complete promises implementation up to spec compliance, or add promises to other browsers and Node.js, use the polyfill.
As of Chrome 32, Opera 19 & Firefox 29, promises are enabled by default. They're in the next release of Safari, and they're in development in IE.
http://www.html5rocks.com/en/tutorials/es6/promises/#toc-browser-support
http://www.html5rocks.com/en/tutorials/es6/promises/#toc-api

* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?  - 
http://lucybain.com/blog/2014/null-undefined-undeclared/
Undeclared example: function myFcn(){}  - doesn't say "var"
Undefined:  var myVar; - empty, didn't set it to anything
Null: assigns a null value to the variable

    undeclared variables don't even exist
    undefined variables exist, but don't have anything assigned to them
    null variables exist and have null assigned to them

Undefined is empty.  Null exists but it has no value...it's a placeholder for a value.  Undefined - doesnt know what the value is or cant find it. variable is undeclared if you don't use "var"
  * How would you go about checking for any of these states?

* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
1. creating a function that is undeclared
2. declare variable to set to function with no parameters
3. create new instance of Person constructor

* What's the difference between `.call` and `.apply`?
http://stackoverflow.com/questions/1986896/what-is-the-difference-between-call-and-apply
The difference is that apply lets you invoke the function with arguments as an Array; call requires the parameters be listed explicitly (Comma). A useful mnemonic is "A for array and C for comma."
Apply uses array. Call requires parameters to be listed.

* When would you use `document.write()`?
To edit the HTML document from your javascript file.
Ex: document.write("<h1>Out with the old - in with the new!</h1>");
insert into HTML dom

* Explain "hoisting".
Ex: http://www.w3schools.com/js/js_hoisting.asp
Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope (to the top of the current script or the current function).

* Debugger - a marker for where to check your code. Put above your functions. If something goes wrong with your code, it will flag it.

* Describe event bubbling. - impacts most specific to least specific. When an event is fired on a particular element and then it impacts its parent/ancestor elements. http://javascript.info/tutorial/bubbling-and-capturing

* What's the difference between an "attribute" and a "property"?
Attribute is on HTML and property is on the DOM.
Use jQuery: $('#linkID').prop('href'); // returns "http://example.com/page2.html"
http://lucybain.com/blog/2014/attribute-vs-property/

* What is the difference between `==` and `===`?  === must match same type too while == may convert a number inside a string to a number to compare with another number. it knows to change the type.

* What is `"use strict";`? what are the advantages and disadvantages to using it?
http://stackoverflow.com/questions/1335851/what-does-use-strict-do-in-javascript-and-what-is-the-reasoning-behind-it

    Strict mode helps out in a couple ways:

        It catches some common coding bloopers, throwing exceptions.
        It prevents, or throws errors, when relatively "unsafe" actions are taken (such as gaining access to the global object).
        It disables features that are confusing or poorly thought out.

* What are the pros and cons of using Promises instead of callbacks? 
http://www.quora.com/Whats-the-difference-between-a-promise-and-a-callback-in-Javascript
- callbacks you look at entire block whereas promise depends on a smaller piece of modularized code.  Callback error can be anywhere inside the script.  Nested callbacks happening around the same thing...will just run.  Promise only waits for an event to happen before executing. Callback better if you are running small piece of code. Callback hell - when too many callbacks are nested within each other.

#### Network Questions:

* Traditionally, why has it been better to serve site assets from multiple domains?
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
* What are the differences between Long-Polling, Websockets and Server-Sent Events?
* Explain the following request and response headers:
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
* What are HTTP actions? List all HTTP actions that you know, and explain them. 

#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

#### Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
* How do you like your coffee?


#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
