![Cold Dogs](https://images.unsplash.com/photo-1516466723877-e4ec1d736c8a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### HTML Images; CSS Color & Text

#### HTML Chapter 5: Images

##### Pictures are a very important element of many web sites. Placing the right picture in the right place can make all the difference. 

* Some photo sites include istockphoto, gettyimages, veer, sxc, and fotolia. I've been using **unsplash** and it works wonderfully.  
* It is a best practice to keep images stored in an image folder for your site, or even subfolders with specific categories for larger sites.
* Add an image by using `<img>`, followed by `<src="imagehere"`
  * For accessibility, include an `alt` with a description of the photo
  * A **title** can also be added to `<img>`
* Control the size of the photo with inline `width` and `height`, but it is considered a best practice to use CSS on a separate page for this
* Placing the image is important and makes a big different to layout
* **old** code - Using the `align` tag inside the `img` is no longer used, but keep an eye out for it.
  * Left or right may lie inside
  * Use CSS to control position
* **old** code - Aligning vertically using top, middle, and bottom. 
* Three rules for images
  * Save in the correct format. Use jpeg, gif or png. 
  * Save at the same size you'll need for the web page
  * Measure images in pixels
  * There are plenty of tools to edit photos, and some are photoshop, pixlr, splashup, and ipiccy
* **JPEG** is the format to use if dealing with a photo with many colors
* **GIF** should be used for images with few colors or large areas of the same color
* You can reduce image size by % without an effect on quality, but increasing may have a negative impact. 
* When cropping, make sure the important part of the image is still included.
* **Vector** images are commonly created in adopbe illustrator and are essentially a line drawing
* Animated GIFs can be used to create simple animations as they are several frames of an image in sequence
* Transparency controls the amount of "see through" for an image
* Check image size by right clicking and inspecting the **get info** area
* `<figure>` contains an element and `<caption>`
  * A `<figcaption>` adds the caption. Embed within the `<figure>` element directly below the `<img>`

#### HTML Chapter 11: Color

##### Color brings pages to life. It is important to choose colors with appropriate contrast for accessibility standards and for the experience of every visitor. 

* Text color is controlled with the **color** property in CSS
  * **RGB** stands for red, green, blue 
  * **HEX** codes are six digit codes that represent the amount of red, green, and blue in a color. They start with a #.
  * CSS has many predefined colors to choose from 
* Background color is controlled with the **background-color** property in CSS
  * If you do not specify a color, the background is transparent
  * Most browsers have white as a default
* Color Theory
  * Every color is made up of a mix of red, green and blue
  * RGB values are expressed as numbers from 0 to 255
  * HEX values are six digit combinations of numbers and letters
    * **HUE** is similar to color, but a color can have hue, saturation and brightness
    * **Saturation** is the amount of gray in a color
    * **Brightness** is the amount of black in the color
  * Contrast is important to ensure text is legible
  * **Opacity** is measured from 0.0 to 1.0 and is added to the end of an RGB(A)
  * **HSL** values combine hue, saturation and lightness. 
    * This is new to CSS3


#### HTML Chapter 12: Text

##### Text plays a significant role in the presentation of a web page, include readabililty and style. 

* There are several families of **typeface** and most browsers tend to come with at least one choice for each family. 
  * **Serif** has styled details at the ends of the main strokes
  * **Sans Serif** does not have this styling
  * **Monospace** fonts have evenly sized letters. 
* The **ascender** is the top of a letter above the **cap height**
* The **descender** lies below the **baseline**
* **x-height** is the height of the letter x
* Browsers can only display typefaces that are installed
* Specify a typeface using the `<font-family>` CSS property
  * It is considered good practice to list a backup typeface in the event that the primary typeface is not available on some computers
* **Font-size** controls the size of text. 
  * By default, text is sized at 16px. 
  * Pixels are the most commonly used, but percentages and ems may be used as well
* There is a font-scale that has existed in more or less the same state for 400 years that dictates the size ratio of font
* It is possible to include a fontface that can be downloaded to a user computer as the web page loads using `@font-face `. 
  * The URL is included, pointing a browser to download the typeface
* Control **bold** with **font-weight**
* Control **italic** with **font-style**
  * Other choices are **normal** and **oblique**
* Change to **uppercase, lowercase, or capitalize** with **text-transform**
* Use **text-decoration** to **underline, overline, or strike** text.
* **Leading** specifices line height, or the space between the **descender** on one line to the **ascender** on the next
* **Kerning** referes to the amount of space between letters.
  * Use **letter-spacing** or **word-spacing** to dictate this amount of space, measuring in ems
* Align text left, right, center, or justified in it's containing element using **text-align**.
* **Vertical-align** can space text vertically for images or other inline elements
* **Text-indent** indents the first line of text. Use pixels.
* **Text-shadow** created a shadown version of text
* **:first-letter and :first-line** allow specific font styling for the first letter or line inside an element
* Style links using **:link** before they are visiting and using **:visited** once they are visited
* **:hover**, **:active** and **:focus** can be added to add interactivity for links



[Next Topic](class-06.md)   
[Main Page](README.md)