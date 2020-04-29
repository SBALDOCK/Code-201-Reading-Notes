![Siblings](https://images.unsplash.com/photo-1519150268069-c094cfc0b3c8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### HTML Lists, CSS Boxes, JS Control Flow


#### HTML Chapter 3: Lists

##### Three types of lists are **ordered**, **unordered**, and **definition**. 

* Ordered Lists create a list with numbers beginning at 1. 
  * `<ol>` annouces the list and `<li>` contains each list item
* Unordered Lists create a list with bullet points
  * `<ul>` and `<li>`
* Deinition lists consist of terms and definitions
  * `<dl>` element, followed by `<dt>` for the term, and `<dd>` for the definition. 
* Nested Lists are simply lists inside of other lists. 

#### HTML Chapter 13: Boxes

##### To review, CSS treats HTML elements as if they are their own box. There are several ways to style these boxes to achieve a desirable appearance.

* Boxes are sized just big enough to hold content by default.
* Boxes can be sized by pixels, percentages, or ems.
* `width` controls how wide a box is.
  * `min-width` and `max-width` varies according to screen size.
* `height` dictates how tall a box is.
  * `min-height` and `max-height` varies according to screen size. 
* **Overflow** allows control over content if it is greater than the box it lies within
  * **hidden** hides the content
  * **scroll** allows to scroll through the content vertically

##### Border, Margin, and Padding control the appearance of boxes

* **Border** separates the edge of one box from another
  * One can dictate the width, style and color of a border in shorthand like this:
    * `border: 3px dotted #0088dd;}`
* **Margin** sits outside the border and controls the gap between two boxes
* **Padding** is the space between a box border and content inside the box. 
* Center boxes by using the `left-margin: auto` and `right-margin: auto` 
* Center text within a box using `text-align: center`
* **Display** turns an inline element into block-level, and block-level elements into inline
  * Example: `display: inline;`
* **Visibility** provides the ability to hide boxes
  * Example: `visibility: hidden;`
* **Border Images** applies an image to the border of a box
  * URL of image
  * Where to slice image
  * What to do with straight edges
* **Box Shadows** provide styled shadows to a box
  * The order of declaration is horiztonal offset, vertical offset, blue distance, spread of shadow
* **Border-Radius** allows corners to be rounded
* **Elliptical shapes** can be created using border-radius


#### JS Chapter 4: Decisions and Loops

##### Switch Statements
 * Switch statements start with a variable called the **switch value**.
 * Each case outlines a possible value and the code that should run given that value is matched
 * The whole statement is in one case block surrounded by curly braces
 * Each case has the word **break** at the end to signify completion and to indicate that the script should move on to the next or stop if the conditions are met
 
##### Type Coercion and Weak Typing

* **Type Coercion** is when JavaScript converts data to complete an operation
* Javascript uses **weak typing** since values can change

##### Truthy & Falsy Values

* Every value in JavaScript can be treated as true or false
* **Falsy** values are treated as if they are false
  * Another way to think of it is that they represent the number 0
* **Truthy** values are treated as if they are true
  * Another way to think of it is that they represent the number 1
  * Most objects and arrays are considered truthy

##### Equality & Existence

* **Unary Operators** return a result with one operand
  * An example would be an if statement that returns one result, considered truthy and runs a second set if not. 
  * `==` can considers "false", "0", and "empty string" and "false" as equal, but `===` cannot since it is a strict operator

##### Short Circuit Values

* Logical operators "short curcuit" when they find a result, but also return the value that stopped the processing

##### Loops
* Loops check a condition and take an action depending upon what returns. If "true" returns, code will run. If "false" returns, the loop will circle back and try again.
  * For loops are useful to loop through items in an array such as an array of baseball game scores
  * While loops are helpful when the number of times the code should run is not known.
  * Do while loops is similar to the while loop but always runs the statements at least once even if the condition evaluates to false.
  * A **break** causes the termination of the loop and tells the script to move on to the next code
  * **Continue** indicates to remain in the current loop, checking the condition again.
  * An **infinite** loop takes place when a condition  never returns false, effectively trapping the loop indefinitely.
    * This can lead to computer performance issues

[Next Topic](class-04.md)   
[Main Page](README.md)