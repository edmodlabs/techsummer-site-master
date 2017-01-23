---
title: Introduction to A-Frame
type: primitives
layout: docs
parent_section: A-frame
order: 4
---

<!--toc-->

## Official Documentation

[Mozilla's A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) is the source of this knowledge base and the authority on everything **A-frame**. The material here is adapted from the official documentation to serve as a high level overview of **A-Frame** for those with limited HTML knowledge, using the (Neocities)[www.neocities.org] platform. 

Some explenations may be taken verbatum from the [Official Mozilla A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) for the sake of clarity and accuracy. 

[Mozilla](https://www.mozilla.org/en-US/grants/?type=open-source-technology) is deeply dedicated to providing open source technologies and knowledge for the betterment of technology as a whole. 

## Prerequisites

1. Basic understanding of HTML
2. [A Neocities account](/docs/1.0.0/A-Frame/lesson1.html)

## 1. The A-Frame Template

<iframe width="560" height="315" src="https://www.youtube.com/embed/YB-O9mIdVQ4" frameborder="0" allowfullscreen></iframe>

1. Select "Edit Site"
2. Select "New File" and call the new file "a-frame-test.html" or anything else you would like (make sure that it ends with '.html')
3. Replace all of the contents of "a-frame-test.html" with the following code.
	```html
	<!DOCTYPE html>
	<html>
	  <head>
	    <meta charset="UTF-8">
	    <title>Your Title Goes Here</title>
	    <script src="https://aframe.io/releases/0.3.0/aframe.min.js"></script>
	  </head>
	  <body>
		<a-scene>
		</a-scene>
	  </body>
	</html>

	```
	```html
	<script src="https://aframe.io/releases/0.3.0/aframe.min.js"></script>
	```
	This script tag loads **A-Frame** into our html page. If you don't include this in your **head** tag, you won't see any **A-Frame**. 
	**This is the basic skeleton for every single A-Frame project. Start every single A-Frame project with this code.**
4. Save

## 2. A-Frame scene

An **a-scene tag**, `<a-scene></a-scene>`, is the basic root element of any A-Frame scene. Every A-Frame related tag must be in between an `<a-scene>` tag. 

`<a-scene>` initializes an **A-Frame** scene on your html page, initializing a full 3d canvas embedded into your html page, and a camera that captures the user's viewpoint and movement. 

In between `<a-scene></a-scene>` we can add [primative](https://aframe.io/docs/0.3.0/primitives/) components. These are html like tags that are shorthand ways of defining complex graphics components. 

For instance, we add a box to our scene by inserting the `<a-box>` [primative](https://aframe.io/docs/0.3.0/primitives/) in between `<a-scene></a-scene>`. This is analagous to inserting a `<p>` element in between `<body></body>`.

This is a sample scene with a box:
```html
<a-scene>
  <a-box color="#6173F4" width="4" height="10" depth="2" position="0 0 -5"></a-box>
</a-scene>
```
Just like with regular HTML elements, we can configure the element by setting HTML attributes. Here, we define the color, width, height, depth of `<a-box>`, and the position of the box in the 3d world as defined by position = "x y z". See the (`<a-box>`)[https://aframe.io/docs/0.3.0/primitives/a-box.html] documentation to see the available attributes.

<p data-height="521" data-theme-id="0" data-slug-hash="PGbJEy" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/PGbJEy/">Example Box</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

## 3. Adding a box
Let's add a box to our HTML page.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Duxt-6ARi-c" frameborder="0" allowfullscreen></iframe>

1. Change your `<body>` content to be the following
```html
<body>
 <a-scene>
   <a-box color="blue"></a-box>
 </a-scene>
</body>
```
2. View your html page. If you did everything right, you shouldn't actually see anything. We are drawing a box at the 0,0,0 position of our world, and the default camera origin is at **0 1.6 0**
	* Thankfully, an `<a-scene>` automatically includes **WASD** controls. Press **W** to move forwards, **A** to move backwards, **S** to move left, and **D**  to move right. If you hold down **S** to move your camera backwards, you should start to see your lovely blue box.
	* You can rotate the camera and look around by **click-dragging** the mouse inside of our A-Frame

## 4. Attributes
Just like with regular HTML elements, we can configure the element by setting HTML attributes.

```html
<body>
 <a-scene>
   <a-box color="blue"></a-box>
 </a-scene>
</body>
```

In our current box example. we have set one attribute so far, **color** to **blue**. Let's explore different attributes and play around with our box in 3d space. 

### Transformation
A-Frame uses a 3 dimensional coordinate system defined by **X Y Z**.
The standard unit of measurment in A-Frame is 1 meter as percieved in virtual reality so creators can easily match 3d space to real space. 

<img src="/images/docs/A-Frame/lesson_1/xyz.png">
**X axis:** “right” with positive numbers and “left” with negative numbers
**Y axis:** “up” with positive numbers and “down” with negative numbers
**Z axis:** “going out to the screen towards us” with positive numbers and “into the screen away from us” with negative numbers
**Note**: **Y** is height and **Z** is depth, which is different from other graphics libraries coordinate systems.

The box can be places in the world with a **position=” X Y Z “** attribute. 

Add a **position=" 0 1.6 -3 "** to place a box 3 meters away from the starting camera in the **Z** direction and 1.6 meters above the 0,0,0 origin to be eye level with the camera default location (0, 1.6, 0).
```html
<body>
 <a-scene>
   <a-box color="blue" position=" 0 1.6 -3 "></a-box>
 </a-scene>
</body>
```

Play around with the positions using the embedded **CodePen** bellow.

<p data-height="369" data-theme-id="0" data-slug-hash="zKogrV" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/zKogrV/">Attributes Color</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Rotation

We can rotate an entity using a **rotation = “ X Y Z ”** attribute. A rotational unit **X**, **Y**, or **Z** is defined in degrees rotated around the axis. 

To determine the positive direction of rotation, we can point our thumbs down the direction of a positive axis, and the direction which our fingers curl is the positive direction of rotation. 

If we wanted to rotate our Box 45 degrees to the right, we have to rotate it around the Y axis.  We need to add **rotation= “ 0 45 0 “** to our box.      

```html
<body>
 <a-scene>
   <a-box color="blue" 
          position=" 0 1.6 -3 "
          rotation="0 45 0">  
   	</a-box>
 </a-scene>
</body>
```
Play around with the rotations using the embedded **CodePen** bellow.

<p data-height="265" data-theme-id="0" data-slug-hash="GjAKOx" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/GjAKOx/">Attributes Rotation</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Scale
We can **scale** an entity to stretch it out or contract it along any axis. We can scale an entity using a s**cale = “ X Y Z ”** attribute. A scaling unit X, Y, or Z is defined as the amount we multiply the height, width, and depth by.

If we wanted to make the box 1/2 the width, 4 times the height, and 3 times as deep, we need to add **scale= “.5 4 3”** to our entity.

```html
<body>
 <a-scene>
   <a-box color="blue" 
          position=" 0 1.6 -3 "
          rotation="0 45 0"
          scale=".5 4 3">  
    </a-box>
 </a-scene>
</body>
```

Play around with the scales using the embedded **CodePen** bellow.

<p data-height="265" data-theme-id="0" data-slug-hash="wzgwjR" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/wzgwjR/">Attributes Scale</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Color
To assign a color to an A-Frame entity, use the **color="color_value"** attribute.
We have already implemented the **color** attribute by setting **color="blue"**.

While we can use the shortcuts for assigning color values such as "green", "blue", "red", "black"
[Here is a full list of color names](http://www.w3schools.com/colors/colors_names.asp) **MUST BE LOWERCASE IN A-FRAME**

Play around with the colors of the box
<p data-height="265" data-theme-id="0" data-slug-hash="jryOqb" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/jryOqb/">Attributes ColorName</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Color values can also be hexadecimal values representing a ratio of Red, Green, and Blue light.

Colors in HTML are displayed combinging red, green and blue light in intensities ranging from 0-255. 
Red,Green,Blue(0,0,255) pure blue
RGB(255,0,0) pure red
RGB(0,0,0) Black (no light)
RGB(128, 128, 128) Grey
RGB(255,255,255) White

[We represent this using hexadecimal colors. Please refer to this explenation of hex colors, if you have not implemented hex colors in CSS before.](http://www.w3schools.com/colors/colors_hexadecimal.asp)

Instead of calculating mathematically which color to use, web developers will often make use of "color pickers" to generate hexadecimal values based on a visual represenation of the color they want. 

[Click here for a great and simple color picker by W3Schools](http://www.w3schools.com/colors/colors_picker.asp)

Use the color picker from [W3Schools](http://www.w3schools.com/colors/colors_picker.asp) to pick various colors for your box

<p data-height="265" data-theme-id="0" data-slug-hash="mARdAv" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/mARdAv/">Attributes ColorHex</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

**note** when assigning color values as hex, we must add a **#** before the value, which we do not do with color names.

# 5. Add more primitive shapes
Our A-Frame scene is looking a bit lonely at the moment. Let's explore some (other primitives included in A-Frame)[https://aframe.io/docs/0.3.0/primitives/. 

### Adding a Plane as a Floor

[From the official documentation](https://aframe.io/docs/0.3.0/primitives/a-plane.html):
"The plane primitive creates flat surfaces using the geometry component with the type set to plane."

Let's add a [plane](https://aframe.io/docs/0.3.0/primitives/a-plane.html) to our scene. Different primitive's have different attributes they require and offer as options. In the case of a plane, there is only height and depth as it is a 2-D shape (cube also has **depth**).

<p data-height="265" data-theme-id="0" data-slug-hash="vXgENY" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="http://codepen.io/nbenavi/pen/vXgENY/">Attributes ColorPlane</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Adding a Sphere

[From the official documentation](https://aframe.io/docs/0.3.0/primitives/a-sphere.html):
"The sphere primitive creates a spherical or polyhedron shapes. It wraps an entity that prescribes the geometry component with its geometric primitive set to sphere."

Let's add a [sphere](https://aframe.io/docs/0.3.0/primitives/a-sphere.html) to our scene. Different primitive's have different attributes they require and offer as options. In the case of a sphere, there is a new "radius" attribute we must define to draw our sphere.  

<p data-height="265" data-theme-id="0" data-slug-hash="ampzJr" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" data-editable="true" class="codepen">See the Pen <a href="https://codepen.io/nbenavi/pen/ampzJr/">Adding a sphere</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Adding a Skybox

[From the official documentation](https://aframe.io/docs/0.3.0/primitives/a-sky.html):
"The sky primitive adds a background to a scene or display a 360-degree photo. It is an entity that prescribes a large sphere with the material mapped to the inside."

Let's add a [skybox](https://aframe.io/docs/0.3.0/primitives/a-sky.html) to our scene. 

<p data-height="265" data-theme-id="0" data-slug-hash="bwqgVk" data-default-tab="html,result" data-user="nbenavi" data-embed-version="2" class="codepen">See the Pen <a href="https://codepen.io/nbenavi/pen/bwqgVk/">Adding a skybox</a> by Noam Ben-Avi (<a href="http://codepen.io/nbenavi">@nbenavi</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

### Further Learning

1. [A great introductory tutorial](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_A-Frame#Initializing_the_scene)

2. [Official A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) 
