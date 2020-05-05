![Freckles](https://images.unsplash.com/photo-1579213838826-51de388c360c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### HTML Tables; JS Constructor Functions


#### Domain Modeling

##### The process of creating a conceptual model in code for a specific problem

* Describes all details of problem domain
* **Object-oriented** model stores data in properties and captures behaviors in methods
* Use a **constructor function** to define the same properties between many objects
* **Instantiate** by using the keyword **new** to call the constructor function
* **Math.random()** is a built in JavaScript function
* A **prototype** is a stunt double of a constructor function
  * JavaScript best practice


#### HTML Chapter 6: Tables

* Basic table structure
  * `<table>` - new table
    * `<tr>` - row
    * `<td>` - cell
    * `<th>` - table heading
    * `<colspan ="">` - span multiple columns
    * `<rowspan ="">` - span multiple rows
* Long Tables
  * `<thead>` - headings of table
  * `<tbody>` - body of table
  * `<tfood>` - footer of table
* Watch out for old code that should be in CSS now

#### JS Chapter 3: Functions, Methods, and Objects

* Create a new object using the keyword **new**
  * `var hotel = new Object();`
  * Add properties and methods
    * `hotel.name = 'Quah'`
  * Update an object with dot notation
    * `hotel.name = 'new name'`
  * Or update with bracket notation
    * `hotel['name'] = 'new name';`
* Create many objects with an constructor notation
  * `function Hotel (name, rooms, booked){
    this.name = name;
    this.rooms = rooms;
    this.booked = booked;
    this.checkAvailability = function(){
      return this.rooms - this.booked;
    };}`
  * this allows you to use the same notation on many new objects
* Four ways to create objects
  * Create objects, then add properties and methods
    * Literal Notation and Object Constructor 
  * Create and object with properties and methods
    * Literal Notation and Object Constructor
* **This** is a keyword and refers to one object, usually where the function operates
* Arrays are objects written differently, but order matters since everything is in index position
* There are three categories of built-in Objects
  * Browser Object Model
  * Document Object Model (DOM)
  * Global JavaScript Objects



[Next Topic](class-08.md)  
[Main Page](README.md)