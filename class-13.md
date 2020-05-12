![Waiting](https://images.unsplash.com/photo-1543556153-01d3c066a72a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### Local Storage

#### The Past, Present, and Future of Local Storage for Web Applications

* Native applications have traditionally held an advantage over web applications when it comes to persistent local storage
  * Persistent data is not automatically cleared
  * An example would be playing a game, closing the page down, and then re-opening and being at the same place at the game despite closing the page
* Cookies were invented to allow web applications this same type of storage in small amounts, but they do not function efficiently
  * Included with every http request, so they slow down the appication by transmitting the same data over and over
  * They have a very limited storage of about 4 KB of data, which is enough to slow down an application but not enough to be of much use

* Desirable storage
  * Lots of storage space
  * On the client rather than native
  * Persistent beyond page refresh
  * Isn't transmitted to the server

* Early versions of local storage before HTML5
  * Microsoft's **userData** allows users to store up to 64 KB
  * Adobe's **Flash Cookies** or **Local Shared Objects** stores up to 100 KB of data, but was limited beyond that
  * Google's **Gears** is an open source browswer plugin
* The goal was to create local storage without the need for extra plugins on different APIs (Application Programming Interface)
* HTML5 storage, also called **Local Storage** allows web pages to store locally using named key/pair values within the client web browser.
  * The data persists after refresh or navigating away, just like Cookies
  * The data is not transmitted to a web server, unlike Cookies
  * All major browsers support it
  * Data is based on a named key, which is a string.
  * Data can be any tuype of data including strings, Booleans, integers, or **floats**
  * Data is stored in a string
* Users can trap the storage event to keep grack of when the storage area changes
* Limitation if user needs more storage and there was not a fix for this in 2011 when the article was written
* A competing vision for local storage utilized **SQL**
  * Supported in most browsers 


[Next Topic](class-14.md)  
[Main Page](README.md)