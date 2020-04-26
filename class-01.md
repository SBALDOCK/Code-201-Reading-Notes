![Lake Dog](https://images.unsplash.com/photo-1504208434309-cb69f4fe52b0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### Introductory HTML and JavaScript

#### Introduction

This book teaches the fundamentals of website design. It covers two of the three languages used in most websites, which are HTML and CSS. Depending upon the device used to access a website, the experience may differ due to outdated web browsers. This is important to keep in mind when writing code. 

The web is a network of servers that send and receive information back and forth from all over the world. This is called a **Domain Name System**. You may be browsing the web from Seattle, but the information you want to retrieve is very likely coming from somewhere else. 

#### HTML Chatper 1: Structure

##### Structure is an important element of website design. Just like printed media such as a newspaper, impactful websites present information in a way that flows naturally for the consumer and calls appropriate attention to important information. 

##### HTML describes the structure of websites.
* **Elements** tell the browser something about the information in between      **opening** and **closing** tags. 
    * The **HTML** element indicates that HTML code lies between the tags. 
    * The **BODY** element contains all information viewed in the main browser. 
    * The **HEAD** element provides information about the website that does not appear in the browser. 
    * The **TITLE** element lies within the HEAD and provides the website name that appears in the top of the browser above the URL window. 
    * Other common structural elements include **h1** and **p**. 
    * Opening tags look like this: `<p>`. 
    * Closing tags look like this: `</p>`. 

* **Attributes** provide more information about elements. 
    * They lie inside the opening tag of any given element. 
    * Attributes have a **name** and a **value**. 


#### HTML Chapter 8: Extra Markup

* HTML5 is the third and current version of HTML. 
    * The previous two are HTML 4 and XHTML. Web developers still encounter both in use, so it is helpful to understand the differences as compared to HTML5. 
* Each page should begin with an indication of what version of HTML will be used.
    * `<!DOCTYPE html>` is used for HTML 5.
* Comments are an important way for a web developer to communicate information about a web page for future reference both by them and any collaborators.
    * Comments look like this: `<!--leave comment here-->`. 
* The **ID** attribute assigns a unique identification to one element in order to apply style with **CSS** or interactivity with **JavaScript**. 
    * ID attributes should only be used for a single element on a page. 
* The **CLASS** attribute applies the same style or characteristics for any element that is assigned. 
* **BLOCK** elements always appear to start on a new line. Some examples are `<p>`, `<h1>`, and `<ul>`. 
* **INLINE** elements appear to continue on the same line as other elements. `<em>` is a good example of this. 
* `<div>` is used to group a set of elements inside a block-level box. This is less commonly used as other HTML5 elements offer more clear and well-organized alternatives. 
* `<iframe>`, or **inline frame** is a window cut into one page that provides a view of another page. An example would be a map in the middle of a web page. 
* The `<meta>` element lives inside the `<head>` and provides detailed information about the web page such as the author, expiration date, keywords, and description. 

#### HTML Chapter 17: HTML5 Layout

##### HTML5 introduced a new set of elements that help define the structure of a page. They help organize information more clearly and ensure that older browsers recognize the elements. 

* Instead of using `<div>` elements with unique `<id>` or `<class>` attributes, web developers can use a new set of elements that divide the parts of a page in a similar structure but make code easier to follow. 
* `<header>` and `<footer>` elements are used for main header and footer information on a page or header and footer information for a specific part of a page. 
* `<nav>` is used for the main navigational elements of a page. 
* The `<article>` element is used as a container for any stand alone section of information on a page. 
* The `<aside>` element is used for two purposes. When inside an article, it contains information related to the article but not essential. When outside an article, it contains information related to the entire page. 
* The `<section>` element groups related content together and would typically have its own heading. A section may contain several distinct articles that have a common purpose or theme. 
    * The section element should not be used as a wrapper for the entire page. 
* `<hgroup>` is used to list multiple `<h1>` through `<h6>` elements. This is not widely used. 
* `<figure>` is used to contain any content that is referenced from the main flow of an article, but the article should still be abel to stand alone without the figure. 
    * Examples are images, videos, graphs, and diagrams. 
* `<div>`, although often replaced by other elements, is still used when none of the other HTML5 elements (which should strictly be used for their given purpose) apply. An example would be a wrapper for an entire page. 
* Using an `<a>` element around block-level elements allows a developer to turn an entire block into a link. 
* In order to help older browsers identify new HTML5 elements, there is specific CSS and Javascript language that should be included. This can simply be copied and pasted into a page. 

#### HTML Chapter 18: Process & Design

##### It is important to consider an audience before building a website. Understanding an audience and their motivations will help inform how a website should be built. Additionally, incorporating elements of design theory helps visitors achieve their goals. 

* There are some important questions to ask that will help provide an outline of how a website should be built. 
    * Who is the site for? 
        * Create fictional characters that might visit the site. 
    * Why do people visit the site?
        * What are their key motivations and specific goals?
    * What are visitors tryingt to achieve?
    * What information do visitors need?
        * Are they familiar with the brand, services offered, features, competitive differences, etc.?
    * How often do they visit the site?
        * Do the same visitors return over and over?
        * Does the content of the site change frequently?
* Create a site map that begins to organize the information into sections or pages. 
    * Each Page might have a list of sections within. 
    * This is called **card sorting**. 
* Create a **wireframe** of the site. 
    * This is a simple sketch of the key information and how it is organized on each page. 
    This ensures that all of the information that needs to be on a page is in fact included. 
* **Design** elements help communicate information. 
    * Group togher related content into blocks or chunks. 
    * Create a **visual heirarchy**, which involves making parts of a page look distinct in order to communicate key elements.
        * Visual heirarchy uses size, color and style to differentiate parts of a page. 
        * **Visual contrast** helps direct the eye to perceive certain elements. 
    * Build clear, simple, self-explanatory navigation. 


#### JS Chapter 1: "The ABC of programming"

##### JavaScript is the third layered language of most websites. It provides interactivity by accessing and modifying content used in a web page while being viewed by a user. 

* Four primary uses for JavaScript
    * **Access Content** - Select any element, attribute or text from an HTML page
    * **Modify Content** - Add or remove elements, attributes or text
    * **Program Rules**  - Specify a set of steps for the browser to follow
    * **React To Events** - Run a script when a specific event occurs 

* What is a script and how to create one?
    * A **script** is a series of instructions for a computer to follow. 
    * This is similar to a recipe, handbook or manual but written in terms that a computer can understand.
    * First, state a **goal** and then compose a list of **tasks** that need to be completed in order to achieve it. 
    * Design the script by splitting the goal into a series of tasks. 
    * Code each step in JavaScript. 
    * Computers need to follow instructions every time they perform a task, unlike humans that remember instructions. 
    * There is specific **vocabulary** and **syntax** that a computer needs in order to perform the steps toward a goal. 
    * Computers perform steps **programmatically**, one after another. The steps toward a goal need to be written in this way. 
* How do computers fit in with the world around them?
    * Computers create models of the world using **data**. 
    * Physical things are represented as **objects** in computer programming. 
        * Each object can have properties, events, and methods. 
    * **Properties** are characteristics of an object. Think about the color of a car. The color is a property of the object (car). 
    * **Events** are interactions that can change the value of properties. 
        * A script uses different events to trigger types of functionality. 
    * **Methods** are the way in which an event takes place. 
        * They can change the value of a property or tell something about the objec.t 
    * Objects, Properties, Events and Methods are all inter-related. 
    * Web browsers are programs built using objects. 
        * **Document** is an object that represents a loaded web page.
        * **Window** is an object that represents each window of a browser. 
* How to write a script for a web page
    * HTML is the content layer of a page.
    * CSS is the presentation layer of a page. 
    * JavaScript is the behavior layer of a page. 
    * This layered approach is known as **progressive enhancement**. 
    * JavaScript is written in plain text like HTML and CSs. 
    * It is best to link an HTML document to a JS document rather than including script directly in the HTML. 
    * The **document** object represents an entire web page. 
    * Object methods and properties are known as **members**.
    * An object may access members with a "dot" between the object name and the member. This is known as a **member operator**. 
    * **Parameters** lies within parantheses and provides information for the action taken. 
    





[Next Topic](class-02.md)  
[Main Page](README.md)