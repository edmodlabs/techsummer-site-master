---
title: A-Frame Setup with Neocities
type: primitives
layout: docs
parent_section: A-frame
order: 2
---

**Special thanks to John Garvey for suggesting the use of [NeoCities](www.neocities.com) as an accessible way to build HTML pages**

[NeoCities](www.neocities.com)  is a free web hosting tool that allow anyone to create a website. 

## Creating an A-Frame page on Neocities
<iframe width="560" height="315" src="https://www.youtube.com/embed/qKI433HfIUc" frameborder="0" allowfullscreen></iframe>

1. Sign up for a [NeoCities](www.neocities.com)'s account: www.neocities.com
2. Select "Edit Site"
3. Select "New File" and call the new file "a-frame-1.html" or anything else you would like (make sure that it ends with '.html')
4. Replace all of the contents of "a-frame-1.html" with the following code
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
	  <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
	  <a-box position="-1 0.5 -3" rotation="0 45 0" width="1" height="1" depth="1" color="#4CC3D9"></a-box>
	  <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
	  <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
	  <a-sky color="#ECECEC"></a-sky>
	</a-scene>
  </body>
</html>

```
5. Select "View" to view your webpage.

## Code Explanation

```
 <script src="https://aframe.io/releases/0.3.0/aframe.min.js"></script>
 ```

 This script tag loads **A-Frame** into our html page. If you don't include this in your **head** tag, you won't see any A-Frame.

```
<a-scene>
  <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
  <a-box position="-1 0.5 -3" rotation="0 45 0" width="1" height="1" depth="1" color="#4CC3D9"></a-box>
  <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
  <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
  <a-sky color="#ECECEC"></a-sky>
</a-scene>
```

These are all special A-Frame elements that get included when you include **A-Frame**. They must go in the **body** tag of your html page or it will not display.

To learn more about A-frame, follow through this [tutorial](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_A-Frame#Initializing_the_scene)

and then

Visit the [official A-frame documentation](https://aframe.io/docs/0.3.0/introduction/) 

