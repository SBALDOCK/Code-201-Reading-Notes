![Stubborn Dog](https://images.unsplash.com/photo-1518887371124-412923b6ccff?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### HTML Links, CSS Layout, JS Functions

#### HTML Chapter 4: Links

##### Links are very important. They are what connect the web. This is what browsing means. 

* Write a link 
  * `<a>` followed by `<href=""` with the website or page enclose in quotations. 
  * Following the `>` on the `<a>`, include the text desired to activate the link
  * Example: `<a href="www.nice">Nice</a>`
  * You can embed links in lists by nesting an `<a>` within a `<li>`
  * In order to link to a different page on the same site, use shorthand like this:
    * `<a href="nextpage.html">Next Page</a>`
  * It is helpful to have a well-organized directory of pages for larger sites, so that there is a folder and file system that is easy to navigate. 
    * An example of this is: `<a href="folder/page.html">page</a>`
  * To move to the parent folder, do this:
    * `<a href="../index.html">home</a>`
  * Create an email link like this:
    * `<a href="mailto:hinklemckrinkleberry@gmail.com">Email Hinkle</a>`
  * To open a link in a new window, include `target="_blank"` within the `<a>` tage
  * To link to a specific part of the page, create an `id` and reference the ID name within `href` instead of a URL
  
#### HTML Chapter 15: Layout

##### Layout is one of the most important aspects of any web page. It is crucial to create attractive design and layout so that visitors want to return and also tell others about the experience. 

* **Block-level element** start on a new line
    * `<h1>, <p>, <ul> and <li>` are some expamples
  **Inline elements** flow in between surrounding text
    * `<img>, <b>, and <i>` are examples
  * **Containing elements** are those that hold other elements within
  * There are several ways to manipulate the position of elements
    * **Normal Flow** refers to the default flow where each block element appears below the previous
    * **Relative** positioning moves an element to the top, bottom, left or right of where it would be in normal flow
    * **Absolute** positioning takes an element out of normal flow and does not affect other elements.
    * **Fixed** position is basically an absolute in relation to the browswer window, meaning it does not move when a user scrolls through a page. 
    * **Floating** elements shift to the left or right of a containing box. 
      * **Z-index** allows control over which box appears on top in the case of an overlap
    
#### JS Chapter 3: Functions, Methods and Objects

##### Browers can follow instructions, but they are not like those that you would give to a human. They must be told specifically, in a step by step process, what to do. Also, they will not remember the last time they did it, so you have to tell them over and over. Very annoying!

* **Functions** are a series of statements group together to completed a specific task.
  * This helps organize code
  * They offer a way to store the steps needed to achieve a task since it will not run every time a page loads.
  * A function name should describe the function itself
  * Pieces of information passed to a function are **parameters**
  * The response to a function is a **return value**
  * **Declaring** a function consists of giving it a name and statements necessary to achieve its goal. These go inside curly braces.
  * **Calling** a function refers to the execution of the steps. 
  * Some functions perform simple calculations such as multiplication (such as calculating the area of a rectangle)
  * An **array** allows a function to return multiple values
    * Example: `(width, height, depth)`
* **Methods** are the same, but take place inside of an object.
* **Objects** are made up of properties and methods. This is review.
* **


#### Article - 6 Reasons for Pair Programming

##### Pair programming is when two developers share a workstation to solve coding challenges together. Code Fellows embraces this type of collaboration.

* Typically, there is a **driver** and a **navigator**
  * The **driver** is behind the wheel in the editor and terminal
  * The **navigator** handles the big picture, scans for mistakes, and may even use their computer as a second screen for documentation
* Pair programming is a way to touch on the vital skills needed to learn new languages.
  * Listening, reading, speaking, and writing
* 6 Benefits
  * Greater Efficiency
    * Two coders are better than one
  * Collaboration
    * The experience is more engaging for both developers
  * Learn from others
    * This is a great way to learn best practices and new hacks
  * Social Skills
    * Learn how to work with and communicate with others
  * Job Interview Readiness
    * It is very helpful to have a partner when preparing for a new job
  * Work environment readiness
    * Collaboration is the name of the game in real life, so let's do it now. 

[Next Topic](class-05.md)   
[Main Page](README.md)