![Smiley](https://images.unsplash.com/photo-1551717743-49959800b1f6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### More CSS Layout

#### HTML Chapter 15: Layout

* CSS treats HTML elements like individual boxes
  * Block-level elements start on a new line
  * Inline elements flow in between surrounding text
* Containing elements hold other elements within them
* There are several ways to position elements with CSS
  * **Normal Flow** makes every new block-level element appear on a new screen
  * **Relative Positioning** moves an element from normal position to the top, right, bottom or left of hwere it would normally be. 
  * **Absolute Positioning** takes an element out of normal flow and does not affect the surrounding elements
  * **Fixed Positioning** is similar to Absolute, but is positioning in relation to the browser window and thus, does not move when a user scrolls
  * **Floating Elements** float to the right or left of surrounding elements
    * You can place elements side by side using float, but you need to be aware of box height. 
  * **Clear** allows a user to say that no element within a containing element should touch the left or right hand sides of the box.
  * If the parent element consists only of floating elements, it may collapse the box. This can be avoided using **overflow**
  * Create multi-column layouts with floats by assigning the float property to each element within a div or other container. 
  * Screen resolution and size is important when building sites
    * Using percentages rather than fixed measurements such as pixels can help maintain the integrity of your page layout. There are advantages and disadvantages to this, as well as fixed width layouts. 
  * **Layout** grids allow a user to import a CSS template that provides a prescribed grid that can be further customized and styled. 
  * Some developers use multiple stylesheets to distinguish between design elements such as fonts and color. 


[Next Topic](class-09.md)  
[Main Page](README.md)