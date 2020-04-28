![Tongue](https://images.unsplash.com/photo-1518717758536-85ae29035b6d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### HTML Text, CSS Introduction, and Basic JavaScript Instructions

#### HTML Chapter 2: Text

##### There are two types of markup that help build the structure of a web page

* Structural markup defines the organization of a web page
    * **Headings** come in six sizes, from `<h1>` to `<h6>`.
    * **Paragraphs** (`<p>`) consist of one or more sentences
    * **Bold** looks like this: `<b>`
    * **Italic** looks like this: `<i>`
    * You can add `<sup>` or `<sub>` elements for characters that are superscript or subscript respectively.
    * When a browser encounters more than one space betweentext, it displays a single space. This is called **white space collapsing**.
    * You can start a new line by using `<br>`.
    * Break up a page to separate themes using `<hr />`.

* Semantic markup provides additional meaning to a web page
    * Semantic markup does not impact the structure of a web page, but rather adds extra information helpful to interpreting the meaning
    * **Strong** indicates importance and looks like this: `<strong>`. It appears **bold**.
    * **Emphasis** indicates a subtle change of meaning and looks like this: `<em>`. It appears *italic*. 
    * In order to enter a quote, use `<blockquote>` and site the reference.
    * For shorter quotes, simply use `<q>`. You may use this for a quote in the middle of a sentence or `<p>`.
    * Use `<abbr>` when using an abbreviation or acronym. It is important to include the full length words using `<title>` as well. 
    * The `<cite>` element allows you to use a reference a piece of work such as a journal. This element presents content in *italics*. 
    * The `<dfn>` element indicates to the browswer a definition of a word or phrase. 
    * `<address>` is specifically used for author details such as name, email, and address.
    * Make changes to content with `<ins>` or `<del>`, which crosses the deleted content out and inserts the new content.
    * The `<s>` element is meant to update content that is no longer accurate or relevant. 

#### HTML Chapter 10: Introducing CSS

##### It is helpful to think of each HTML element having its own box. Each box can be styled with CSS. There are several ways to style HTML elements, and a specific order of importance exists within the CSS heirarchy. 

* Apply CSS to an entire element by listing the element, followed by **curly braces**. This is called a **selector**. 
    * After choosing a selector to style, a **declaration** indicates a style **property** and **value**. 
    * Here's an example: `p {color: red;}`
    * External CSS involves the creation of a separate, `.css` file and linking the file to the HTML page. Here's what it looks like:
        * `<link href="index.css" type="text/css" rel="stylesheet">`
        * This is the preferred method of applying CSS. 
    * The **universal** selector applies to all elements on the page.
    * The **type** selector uses an element name such as `<p>`.
    * The **class** selector uses an element assigned a specific class name. Any styles apply to all elements with the class name assigned. 
    * The **id** can be used to style one single element, even if there are other elements of the name type on a page. Remember to only use each unique id once per page. 
    * The **child** selector applies style to any elements that are direct children of another element.
    * The **descendant** selector applies style to any descendants of an element, including children. 
    * The **adjacent sibling selector** applies style to the next sibling of an element.
    * The **general sibling selector** applies style to any sibling, not just the next in order. 
    * It is important to remember that CSS rules cascade downwards, so that the last rule appies. Also, the more specific rule takes presedence over a less specific rule. An example would be an **id** over ruling a **class** selector. 
    * Some properties are inherited, such as font-family. 

#### JS Chapter 2: Basic JavaScript Instructions

* JavaScript is *case sensitive*. 
* Each individual step that a computer follows is called a **statement**. 
    * Statements end with a semicolon. 
    * Each statement starts on a new line. 
    * Some statements are surrounded by curly braces and are not followed by a semicolon. 
* It is a best practice to write comments to explain what code does.
    * Multi-line comments: `/* Comment here */`
    * Single-line comments: `//`
* **Variables** are used to 'remember' values
    * Variables store bits of information that a script needs to do its job. 
    * Variables are aptly named because they can change or vary each time a script runs. 
    * Variables can represent numbers or other kinds of data similar to Alegbra where letters are used to represent numbers.
    * The equals sign means something very different in JavaScript
* Delare a variable by creating it and giving it a name.
    * Use **var** to announce it and create a name (**identifier**).
    * If possible, a variable's name should describe the kind of data it holds.
    * If an identifier is more than one word, it is usually written in **camelCase**.
    * Once a variable is created, a value may be assigned to it. 
        * The **assignment operator** is an equals sign (=).
    * A variable is considered undefined until given a value.
* There are three primary data types
    * **Numeric Data Type** - Numbers, including negative numbers and decimals
    * **String Data Type** - Consists of letters and other characters
        * Enclosed by a single or double quote, but it must be consistent on either end of the string
    * **Boolean Data Type** - True or false satements
        * Similar to a light switch. Either on or off. 
        * Also used when code can take more than one path. 
    * Variables can be asigned several ways.
        * In a single statement
        * On the same line
        * Two variables on the same line with values and a thir declared and assigned value on the next line
        * To hold a reference to an element in the HTML page
* Rules for naming variables
    * Name must begin with letter, dollar sign or underscore
    * Name can contain numbers, dollar sign, letters, or underscore
    * No **keywords** or **reserved** words.
    * Case sensitive
    * Use a name that describes the kind of stored information
    * Use **camelCase**
* An **array** is a variable that storesj a list of a values
    * Useful when working with a list or a set of values that are related to one another
    * Create an array just like a variable, with values assigned inside a pair of **square brackets**.
    * A number, string or boolean can be stored in the same array. This is called an **array literal**. 
    * The **array constructor** is another way to create an array
    * Values in an array start at 0 rather than 1. 
* An **expression** results in a single value. 
    * Some assing a value to a variable
        * `var color = 'beige';`
    * Some use two or more values to return a single value
        * `var area = 3 * 2;`
* **Operator** types
    * Assignment - Assigns a value to a variable
    * Arithmetic - Performs basic math
        * Addition (+), Subtraction (-), Division (/), Multiplication (*), Increment (++), Decrement (--), Modulus (%).
    * String - Combines two strings
        * One operator: The (+) symbol
        * **Concatenation** combines tow or more strings together to create a single value
    * Comparison - Compares two values and returns true or false
    * Logical - Combines expressions and returns true or false
    * Similar order of execution to algebra


#### JS Chapter 4: Decisions and Loops

##### Most scripts involve more than one path, meaning the browser will run different code depending upon the situation. Learning how to control this flow of data is a very important aspect of JavaScript. 

* Creating a flowchart can help a developer visualize how various **decisions** lead to different code. 
* **Comparison operators** compare values and test if a specific condition is met or not. If if is met, the script moves on. If the condition is not met, the script will keep running until the conditions are met. 
* Decisions consist of the evaluation of an expression and its value, and a statments that gives a command. 
    * **Conditional statements** are based on an if/then/else concept. 
* There are various comparison operators.
    * `==` compares two values to see if they are the same
    * `!=` compares two values to see if they are not the same
    * `===` compares two values for strict equality
    * `!==` compares two values for strict inequality
    * `>` compares to see which value is greater
    * `<` compares to see whic value is lesser
    * `>=` - Greater than or equal to
    * `<=` - less than or equal to 
* **Logical operators** can compare the results of more than one comparison operator
    * `&&` looks for two values or comparisons to be true
    * `||` looks for at least one condition to be true. If either returns true, the expression returns true. If both are false, the expression is false.
    * `!` takes a "true" and makes it "false" or takes a "false" and makes it "true"
* **If** statements evaluate for true and runs code if the condition evaluates to true. 
    * **Else** takes place when the **if** statement resolves to false.
* A **switch** statement allows a user to change code depending upon how the variable matches a value
* **Loops** check a condition and take an action depending upon what returns. If "true" returns, code will run. If "false" returns, the loop will circle back and try again. 
    * **For** loops are useful to loop through items in an array such as an array of baseball game scores
    * **While** loops are helpful when the number of times the code should run is not known.
    * **do while** loops is similar to the while loop but always runs the statements at least once even if the condition evaluates to false. 

#### Git Commit Messages

* It is very important to compose a good git commmit message
    * A git commit message should not tell someone *if* something changed, but rather ***why*** it changed
* Git commit messages show whether a developer is a good collaborator
* Teams must agree on a series of git commit message conventions
    * **Style** - Consistent punctiuation, grammar, markup, etc. 
    * **Content** - What information should be included, and conversely not included
    * **Metadata** - What system is in place for referencing pull requests, etc.
* 7 rules of a solid git commit message
    * Separate the subject from the body with a blank line and include a short introductory nmessage summarizing the change
    * Keep the subject line short
    * Capitalize the subject line
    * Don't end the subject line with a period
    * Use the imperative mood in the subject line
        * Give a comand or instrution
    * Wrap the body around 72 characters
    * Use the body to explain the what and why instead of the how


[Next Topic](class-03.md)  
[Main Page](README.md)