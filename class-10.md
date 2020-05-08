![Climber](https://images.unsplash.com/photo-1558528021-a4925a5488c7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### JS Debugging

#### JS Chapter 10: Error Handling & Debugging

* Order of execution is very important in JavaScript, and understanding the order can help developers identify issues with script and work to amend them. 
* There are three **execution contexts** that all JavaScript lives in
  * **Global** context lives independently from any functions
  * **Function** context lives within a function and only works for that function
  * **Eval** context is beyond the scope of the book
  * Global and Function contexts correspond with scope. Either they are global and universally applicable or function-based. 
  * JavaScript stacks functions and commands on top of one another since many functions rely on the execution of another. Each time a new function is added, it stacks on top and only removed when it finishes its work
  * **Hoisting** refers to the concept that many functions are created and called before they can actually be executed, as they rely on other functions to work. 
  * **Lexical Scope** means functions in JavaScript are linked to the object they were defined within.
  * An **exception** is when JavaScript statements generate an error. The interpreter stops and looks for **exception-handling code**. This is code that provides a work around to the error. Good developers anticipate errors and provide exception-handling code. 
  * There are several types of errors, each with an array of errors within.
    * Syntax Errors is caused by incorrect use of the rules of the language
    * Reference Errors are caused by a variable that is not declared or out of scope.
    * Type Errors is caused most often by objects being used incorrectly.
    * Range Errors are when a function is called using numbers outside of the accepted range. 
    * NaN - Not a number
    * Error - Generic
    * Eval Error - Out of the scope of the book
    * URI Error - Use of certain characters inappropriately
  * How to deal with errors
    * Debug the script
    * Handle errors gracefully with error-handling code
  * Debugging 101
    * Determine where the problem exists
      * Use console tools
    * Determine what the problem is 
  * Use Browser dev tools and the console to debug
    * Broswers possess tools to determine the source of an issue
    * The console allows devlopers to create break points in the script to determine whether code prior to that point functions. This narrows the scope of search
      * This allows you to step through code one by one
    * Developers can use the **debugger** keyword to automatically create a breakpoint to see if code functions properly
* Use **try, catch, and finally** to test before running, catch error, and to run whether it has an error or not. 
* Debugging Tips
  * Try another browser
  * Add numbers using the console to see which items get logged
  * Strip it back by removing parts of code or commenting them out
  * Explain the code to someone else
  * Search the web for fixes
  * Use code playgrounds to test code
  * Use validation tools to test code and find errors
  
  

[Next Topic](class-11.md)  
[Main Page](README.md)