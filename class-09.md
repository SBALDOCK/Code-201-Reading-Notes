![Folds](https://images.unsplash.com/photo-1541599540903-216a46ca1dc0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### Forms and Events

##### There are many types of forms, with specific input types for whatever information is necessary to collect

#### HTML Chapter 7: Forms

* Start with the **form** element, which wraps the whole input area
  * Each form element requires an **action** URL to receive the information that the user enters
  * **Get** method is good for short forms or just for data retrieval
  * **Post** is for longer forms, sensitive information, or case sensitive data
  * You can use the ID attritube to distinguish one specific form for CSS styling and use with scripts
* **Input** is a self-closing element that requires a **type** and **name**.
  * **Text** is a single-line text input
  * **Name** tells the server what type of data is entered
  * Type **password** is a text input that blocks out the input
  * **Textarea** is a self-closing tag that creates an entry area of multiple line
  * Type **radio** allows for a single selection
    * Add **value** to name each radio button
  * Type **checkbox** allows user to select more than one option.
    * Add value to name each option
    * Use **checked** if you want one option checked when the page loads
  * **Select** creates a drop down of options. The user can select one. 
    * **Value** indicates the value that is sent to the server
  * Use **multiple** with select if you want the user to be able to select multiple option
  * Use **input** with **file** to provide an option to upload a file from a computer. It automatically adds "browse" or "choose files" depending on the computer
  * Use **submit** with input to send a form the server. Does not need to have a name attribute but can be added
    * Value adds a submit button on the right that is named whatever value is specified
  * Use **image** type with input to customize a submit button with an image of your choice
  * Use **button** and **hidden** to have more control over how buttons appear. Hidden form controls hide the form from sight
  * Use **label** to wrap around both text and input or to be kept separate from the form control to indicate what it is a label for
  * **fieldset** groups related form controls together and **legend** names it. 
  * Use **form validation** to require the user to put in specific information/corret information
  * Use type **date** to prompt the user to enter a date
  * Use type **email** for email address input or **url** for URL entry
  * Use type **search** to create a single text box for search queries
  

#### HTML Chapter 14: Lists, Tables & Forms

##### There are specific CSS properties built to work with HTML elements such as lists, tables and forms 

* Bullet point styles can be customized using **list-style-type**
* Use **list-style-image** to add images to bullet points
* Use **list-style-position** and **inside** or **outside** to place bullets to the side or inside the box of text
* Use **list-style** to express the marker's style, image, and position properties in any order
* There are many properties that assist with styling a table
  * Width
  * Padding
  * Text-transorm
  * letter-spacing and font-size
  * border-top, border-bottom
  * text-align
  * background-color
  * :hover
* Use **empty-cells** and **show**, **hide** or **inherit** to choose what to do with empty cells
* Use **border-spacing** or **border-collapse** to space cells
* Use the **div** element to properly align different elements of a form, since they sometime are different lengths
* Custize cursor styles with **cursor** and the following:
  * auto
  * crosshair
  * default
  * pointer
  * move
  * text
  * wait
  * help
  * url(cursor.gif)

#### JS Chapter 6: Events

##### There are many different types of events that occur in the browswer that can be used to trigger a function in JavaScript

* Several example keywords are load, unload, error, resize, scross, keydown, keyup, and click.
* Order of Trigger
  * Select element node for trigger
  * Indicated circumstances for trigger (what event?)
  * Write the code for the event
* There are three primary ways to bind an event to an element
  * HTML event handlers
    * No longer in use as JavaScript handles it better
  * Event Handlers
    * Widely recognized and used
    * Can only handle a single event per script
  * Event Listeners 
    * Allows one event to trigger multiple functions
* When using a function, do not use the parantheses
* Event listeners use an anonymous function that holds the actual named function
* There are work arounds for using older versions of IE that do not support Event Listeners
* Event flow is important because if an event is triggered by a child element, all other elements can be triggered as well
* Objects tell information about the event and the element that it happened upon
  * Placing an event handler on a containing element can save memory and increase performance
* The event object can change the way an element behaves and how an element's ancestors respond
  * This is event delegation
* You can determine which element an event occured on by using **this**
* There are different types of events
  * WC3, HTML5 Events, BOM Events


[Next Topic](class-10.md)  
[Main Page](README.md)