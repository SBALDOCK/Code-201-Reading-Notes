![What?](https://images.unsplash.com/photo-1516383074327-ac4841225abf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### CSS Transforms, Transitions, and Animations

#### CSS Transforms

* Transform property gives new options for size, position and alteration (transition)
* **Two-dimensional** transform - X and Y axis
  * `Rotate` - rotate elements from 0 to 360 either clockwise or counterclockwise
  * `2D Scale` - Change the appeared size of an element
    * Default scale is 1
  * `2D Translate` - Push and pull an element in different directions without interrupting the normal flow of the document
    * Similar to relative positioning
  * `2D Skew` - Distort elements on the horizontal axis, vertical axis, or both
    * Use the `SkewX` or `SkewY` value
  * It is common to combine multiple transforms and there is shorthand to do so.
  * `Transform Origin` - Change the default origin or starting point of the element using horizton and vertical percentages
  * `Perspective` - Similar to a vanishing point in design
    * Can be set in two ways
      * Use the perspective value within the transform property on individual elements
      * Use the perspective property on the parent element
    * `Perspective depth value` - Can be set as none or a length measurement
      * The higher the value, the further away the element appears
    * `Perspective origin` - Uses the same values as the transform origin property
      * Identifies the coordinates of the vanishing point of a transform
     
* **Three-dimensional** transform - X, Y and Z axis

  * `3D Rotate` utilizes the Z-axis as well
    * Use rotateX, rotateY, and rotateZ
  * `3D Scale` similar to 2D version but uses the Z-axis
    * Use the rotateX value in order to see how the scaleZ value behaves
  * `3D translate` - The transform takes place on the Z-axis, making it quite different from the 2D version
  * `Backface visibility` allows the label to be seen on the backside of a rotating or otherwise moving element

#### CSs Transitions & Animations

* Transitions provide a change from one state to another
* Animations set multiple points of transition
* The easiest way to change a state is through hover, focus, active and target pseudo classes
* Transition Properties
  * `Transition-property` - Determines what properties will be altered in conjunction with the other properties below
    * By default, all properties are altered upon state change, but `transition-property` allows specification
  * `Transition-duration` - Duration of the transition from one state to another
    * Usually measured in seconds or milliseconds
    * Set multiple durations when transitioning multiple properties
  * `Transition-timing-function` - Sets the speed of the transition
    * Popular options are `linear, ease-in, ease-out, and ease-in-out`
    * Each function has a `cubic bezier curve` which is set on x and x axies
  * `Transition-delay` - Sets a delay with a time value such as seconds or milliseconds
* Vendor prefixes ensure that the animation works across all browswer types
* If multiple properties must be transitioned, they can be separted by a comma in the transition-property
* Only properties that have an identifiable halfway point can be transitioned

* Shorthand can be used to call transition properties
  * Order of operation is transition-property, transition-duration, transition-timing-function, and transition-delay

#### 8 Simple CSS Transitions

* Transition property has 3 values
  * property of the transition
  * speed of transition
  * acceleration or deceleration
* **Fade In** - Fade text in when cursor hovers over it using only opacity
* **Change Color** - Set a default color and then use `:hover` to change color when the cursor hovers over
* **Grow & Shrink** use the transform property, naming a scale above or below the default size
* **Rotate** elements using the transform property and `rotate`, naming an axis and the degree
* **Square to cirlce** is done simply by changing the border-radius on hover
* **3D Shadow** utilizes the box-shadow property with the transform property 
* **Swing** uses `keyframes` and `transform` to create a CSS animation, and then `hover` to make it work
* **Inset border** uses `box shadow` with `inset` as the first parameter

#### 6 Buttons Animated

* It is relatively simple to achieve a "floating" effect on elements such as these buttons
* These utilize the `hover` option to change slightly when the cursor hovers over them

#### CSS3 Animations: KeyFrames

* This utilizes a `webkit-animation` for the bouncing ball, which is referenced in the `style` of the div with class "ball" and then styled in CSS
* It also uses JavaScript to create the Facebook messenger effect in the bottom right hand corner of the page 

#### 404

* This animation uses `transform: translate`, which pushes and pulls elements in certain directions, similar to relative positioning. 
* It also incorporates `key frames` to achieve its effect
* It starts by creating multiple `key frames` ranges, and then references them  behind the `animation` property

#### Pure CSS Bounce Animation

* This animation uses CSS to transform a bouncing ball into a new shape using `keyframes`

* This looks quite complicated but is not that difficult if you just look through all the pieces


[Next Topic](class-15.md)  
[Main Page](README.md)