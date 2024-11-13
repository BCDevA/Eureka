# Eureka
First repository (_Mandatory_)

###Cupery2.zip  
Creates an _outerspace_ or _planet_ themed image.

* **Sketch Contents**:
 * canvas is 400px by 400px
 * contains 6 shapes
  * 5 ellipses
  * 1 custom shape using vertexes
 * contains 3 beziers

###Cupery6.zip  
Creates a _nature_ or _Halloween_ themed image

* **Sketch Contents**:
 * canvas is 600px by 400px
 * sketch creates ellipses that increase in size as they approach the bottom of the screen
  * ellipses get brighter as they approach the bottom
  * creates the illusion of movement

###Cupery10.zip  
Creates three loops using the [p5.createloop](https://www.npmjs.com/package/p5.createloop) library

* **Sketch Contents**:
 * canvas is 400px by 400px
 * loops must be changed _prior_ to starting the sketch
  * accessed by changing the _**cycle**_ variable
 * **First Loop**
  * 3 second duration
  * no noise
  * ellipse moving in a circle
 * **Second Loop**
  * 3 second duration
  * noise frequency of 10
  * noise seed of 2
  * ellipse moving smoothly left-to-right
  * ellipse rapidly jumping up-and-down
 * **Third Loop**
  * 10 second duration
  * noise frequency of 1
  * noise seed is randomly generated when sketch initiates
  * ellipse moving in a random shape
   * shape is random _each time_
   * shape remains constant _while sketch is running_
