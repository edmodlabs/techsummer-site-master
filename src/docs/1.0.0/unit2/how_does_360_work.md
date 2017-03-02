---
title: How a 360 Camera Works
section_title: How a 360 Camera Works
type: unit2
layout: docs
parent_section: unit2
order: 5
---


## The Magic 360 Sauce 

How does the camera magically covert a two-dimensional (2D) image into one that looks seemingly three-dimensional (3D)?  All digital cameras use a camera *lens *and a digital *sensor *to collect light rays from the world.  Your eyeballs for example are really good wide-angle lenses, which can capture up to 130-degrees of the world at once.*  *

<img src="/images/docs/360_images/FOV.png">

Your Ricoh Theta camera uses two 180-degree lenses and combines them to create one 360-degree image.  This process is called *stitching* the image, much like you might stitch multiple pieces of cloth together to create one single piece of clothing.  The two separate lens images will look like this:

<img src="/images/docs/360_images/theta_example_frame.png">


The two lenses on the camera always stay in the same place relative to each other, so the camera stitches the two images together and deletes the duplicate information so it looks like this: 

<img src="/images/docs/360_images/theta_example_stitched_frame.png">

But wait, the image looks wavelike and all distorted, not all like an image from other digital cameras or your smartphone.  That's because it's still a 2D image trying its hardest to be a 3D one.  You may have seen this in dozens of classrooms before, usually flat and hung on a wall in the form of a world map!  But how can something flat actually represent the earth, which is the shape of a sphere?  This is called a *projection map*, and you can think about your 360-degree images the same way.  

<img src="/images/docs/360_images/Equirectangular_projection_SW.jpg">


Although you can view 360-degree images as flat, they look distorted like a world map.  Remember what your Geography teacher taught you about Canada and Greenland looking way bigger on the flat map than they actually are in real life?  This is because we are doing crazy earth origami, turning a flat piece of paper into a more complicated 3D shape.

<img src="/images/docs/360_images/Dymaxion_2003_animation_small1.gif">


Here's the previously flat 360-degree image, now projected mapped around a full sphere object:

<script src="//vizor.io/scripts/embed.js" data-vizorurl="//vizor.io/embed/codexter/360-lesson" ></script>

Looks totally different, right?  Welcome to the world of 360-degree photography! No more worrying about what correct Instagram angle to capture, just collect a whole scene with one click of the Ricoh Theta and then let the viewer decide where to look!  
