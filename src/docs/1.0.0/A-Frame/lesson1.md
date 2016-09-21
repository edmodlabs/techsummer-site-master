---
title: Introduction to A-Frame
type: primitives
layout: docs
parent_section: A-frame
order: 3
---

<!--toc-->

## Official Documentation

[Mozilla's A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) is the source of this knowledge base and the authority on everything **A-frame**. The material here is adapted from the official documentation to serve as a high level overview of **A-Frame** for those with limited HTML knowledge and using the (Neocities)[www.neocities.org] platform. 

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
	```
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
	```
	<script src="https://aframe.io/releases/0.3.0/aframe.min.js"></script>
	```
	This script tag loads **A-Frame** into our html page. If you don't include this in your **head** tag, you won't see any **A-Frame**. 
	**This is the basic skeleton for every single A-Frame project. Start every single A-Frame project with this code.**
4. Save

## 2. A-Frame scene

An **a-scene tag**, `<a-scene></a-scene>`, is the basic root element of any A-Frame scene. Every A-Frame related tag must be in between an `<a-scene>` tag. 

`<a-scene>` initializes an **A-Frame** scene on your html page, initializing a full graphics program embedded into your html page, and a camera that captures the user's viewpoint and movement. 

In between `<a-scene></a-scene>` we can add [primative](https://aframe.io/docs/0.3.0/primitives/) components. These are html like tags that are shorthand ways of defining complex graphics components. 

For instance, we add a box to our scene by inserting the `<a-box>` [primative](https://aframe.io/docs/0.3.0/primitives/) in between `<a-scene></a-scene>`. This is analagous to inserting a `<p>` element in between `<body></body>`.

Just like with regular HTML elements, we can configure the element by setting HTML attributes. Here, we define the color, width, height, depth of `<a-box>`. See the `<a-box>` documentation to see the available attributes.

## 3. Adding a box
Let's add a box to our HTML page.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Duxt-6ARi-c" frameborder="0" allowfullscreen></iframe>

1. Change your `<body>` content to be the following
	```
	<body>
		<a-scene>
			<a-box color="blue"></a-box>
		</a-scene>
	</body>
	```
2. View your html page. If you did everything right, you shouldn't actually see anything. We are drawing a box at the 0,0,0 position of our world, and the default camera origin is at **0 1.6 0**
	* Thankfully, an `<a-scene>` automatically includes **WASD** controls. Press **W** to move forwards, **A** to move backwards, **S** to move left, and **D**  to move right. If you hold down **S** to move your camera backwards, you should start to see your lovely blue box.
	* You can rotate the camera and look around by **click-dragging** the mouse inside of our A-Frame


In the meantime...

1. [A great introductory tutorial](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_A-Frame#Initializing_the_scene)

2. [Official A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) 
