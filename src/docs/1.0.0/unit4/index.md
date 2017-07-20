---
title: 4.1) Loop Animations - Part One
section_title: 4) Interactive Storytelling
type:  unit4
layout: docs
parent_section: docs
order: 1
section_order: 5
---

## Overview
Welcome to the final unit of Storycasts!  You're already a master architect in our book!  Now, we'll teach techniques related to interactive storytelling.  The topics are the first steps to becoming a pro animator, game designer, technical artist, and more.

Unit 4 is better used as a cookbook than guide.  Pick and choose what you want to use.  When it comes to polishing a creative project sometimes there are no right answers - you just need to experiment and test!

## Adding Loop Animations

When a 3D object moves in space across a specified time period it’s called an <i>animation</i>.  Animations are critical to add life and dimension to characters or scenes.  

<div style="text-align:center">
	<img src="/images/techsummer/Unit4/4.1/bear.gif">
	<br>
	Let's jump into the BEAR necessities of animation! 
</div>

From <strong>Program Mode</strong> in your Storycast, enter a nested scene of a 3D object you want to animate.  Edit the 3D object (pencil icon) <strong>nested patch</strong> to see the object’s features.  The blue <strong>Mesh patch</strong> represents the object’s properties.  A <strong>Mesh</strong> is the 3D shape that constructs the object.  There are many property slots we can modify and connect.  

<div style="text-align:center">
	<img src="/images/techsummer/Unit4/4.1/enter_object.gif">
	<br>
	Navigate into a 3D object through the nested patch. 
</div>

The <strong>Position</strong>, <strong>Rotation</strong>, and <strong>Scale</strong> slots in the <strong>Mesh patch</strong> let us move, rotate, and change the size of objects.  If we connect patches to the slots, we can set specific positions, rotations, and scales and also change those over time to create animations!

In the Patches panel, search for <strong>Toggle Sine Animation</strong> and drag and drop it into the patches area.

<div style="text-align:center">
	<img src="/images/techsummer/Unit4/4.1/add_sine.gif">
	<br>
	Navigate into a 3D object through the nested patch. 
</div>

Yikes - there are lots of parts to the <strong>Toggle Sine Animation patch</strong>.  Also... WHAT IN THE WORLD IS A SINE?!?!

<div style="text-align:center">
	<img src="/images/techsummer/Unit4/4.1/toggle_sine_patch.jpg">
	<br>
	A complete Toggle Sine Animation patch. 
</div>

<div class="alert_green">
  <div style="text-align:center">
  	<strong>Loop Animation Guide</strong>
  </div> 
  We'll explain every step of using the <strong>Toggle Sine Animation patch</strong> in the next section. However, if you want a quick guide or to try on your own, here's a summary:
  <ol>
  	<li>Set the <strong>Animation Speed</strong>, <strong>Min</strong>, and <strong>Max</strong> values.</li>
  	<li>Add an <strong>XYZ to Vector patch</strong>.</li>
  	<li>Connect the output of the <strong>Oscillator (Sine) nested patch</strong> to the X, Y, and/or Z inputs of the <strong>XYZ to Vector patch</strong>.</li>
  	<li>Connect the output of the <strong>XYZ to Vector patch</strong> to the <strong>position</strong>, <strong>rotation</strong>, and/or <strong>scale</strong> properties of the object you want to animate.
  </ol>
</div>
<br>
The above looks like a lot, so let's dive into each step in the next section!

