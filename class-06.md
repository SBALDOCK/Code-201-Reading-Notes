![Buddies](https://images.unsplash.com/photo-1508814437933-f0c7d18a9217?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60)

### JS Object Literals; The DOM

#### Understanding the problem domain is the hardest part of programming

##### Creating a simple, easily understood problem domain can make learning much easier. Since it is difficult to learn more than one thing at a time, it is important in this instance that the focus remain on the technology rather than the problem domain. A "protein tracker" is something that is very easy to conceptualize, thus freeing the student mind to focus on the actual technology. 

* Problem domains can be like a puzzle with a blurry picture. You aren't sure what the end application or goal looks like
* It is important to have a clear picture with components you can identify.
* When you are given clear and specific parameters for your code, it is usually very easy to complete a task. 
* Steps to approaching the problem domain
  * Make it easier
    * This can be achieved by narrowing your focus, fully understanding one part of the problem before moving on to the next
  * Get better at understanding it
    * Don't assume you know enough about the problem domain. Talk to customers or business people who know about it so you don't have to repeat work

#### JS Chapter 3: Object Literals

* An **object** represents something in the real world
  * It groups together a set of variables and functions to create a model
  * Within an object, variables are known as **properties**
  * Functions are known as **methods**
* **Literal Notation** is the easiest and most popular way to create objects
  * Create variable
  * Everything within curly braces is the object
    * Example -  `var hotel = {
      name: 'Quay',
      rooms: 40;
      booked: 25;
      checkavailability: function(){
        return this.rooms - this.booed;
      }
    }`
* Use **dot notation** to access the property or method of an object
  * Example - var hotelName = hotel.name;
  * The period is called a **member operator**
  * You can also access a property or method using square brackets
    * var hotelName = hotel['name'];
* Access a property of an object by naming the object followed by a dot and the name of the property desired

#### JS Chapter 5: Document Object Model

##### Also known as the DOM, this specifies how browsers should create a model of an HTML page and how JavaScript can access and change information on the page while it is presented in the browser. 

* Separate set of rules implemented by all major browsers
  * Model of the HTML page
    * The browser creates a model of a page in memory when it loads
    * The **DOM Tree** specifies how the browser structures the model
    * It's called an object model because it is a model made of objects
    * Each object represents part of the page
  * Accessing and changing the HTML page
    * The DOM defines methods and properties to access each object in the model
    * It is an **application programming interface (API)**, meaning it lets humans interact with programs
* The DOM Tree consistes of four main types of **nodes**
  * Document Node - Represents the entire page and corresponds with the document object
  * Element Node - Elements represent structure and allow access to the following two nodes
  * Attribute Node - Class and ID attributes are part of an element, not children of an element
  * Text Node - Text nodes cannot of children
* Working with the DOM Tree
  * Step 1 - Locate the node that represents the element you want to work with
    * Accessing nodes can be done several ways including "getelementbyId() or querySelector()"
  * Step 2 - Use its text content, child elements and attributes
    * Access and update text nodes
    * Work with HTML content
    * Access and updated attribute valus
  * Use a variable to store the results of a DOM query if it will be used more than once
* Selecting Elements
  * Select individual elements example - document.getElementById('one')
  * Select from Nodelists
    * The Item() Method
      * Specify the index number of the element you want
    * Array Syntax
      * Preferred method as it is faster
      * Use square brackets to access individual nodes
  * You can select elements using class attributes, tag names, ID, and CSS selectors
  * Loops can be incorporated to apply the same code to numerous elements
  * Traverse the DOM
    * parentNode, previousSibling, nextSibling, firstChild, and lastChild
  


[Next Topic](class-07.md)   
[Main Page](README.md)