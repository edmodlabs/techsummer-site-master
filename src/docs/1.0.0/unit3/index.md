---
title: 3.1) Juggling Scenes and Objects
section_title: 3) Objects Galore
type:  unit3
layout: docs
parent_section: docs
order: 1
section_order: 4
---

## Overview
Congratulations on reaching Unit 3! You’ve built a VR viewer, exercised your storytelling muscle, and started using Vizor.  Now, it’s time to add more technical work to the mix by learning how to add multiple types and amounts of <strong>objects</strong>.

<div class="alert_red">
  <div style="text-align:center">
  	<strong>Stick With It</strong>
  </div> 
  We expect Unit 3 to be challenging - maybe even frustrating at times. If you feel overwhelmed or lost, you’re probably not the only one so don’t give up.  Visit the [Facebook group](fb.com/groups/techsummer) to get help, drop into office hours, and stick with Storycasts. There’s a whole community ready to help!
</div>
<br>

<div style="text-align:center">
	<img src="/images/techsummer/Unit3/3.1/patback.gif">
	<br>
	Pat yourself on the back and let's keep at it! 
</div>

## Juggling Objects

In the last unit, you were introduced to the Storycast Vizor <strong>template</strong>.  You also saw <strong>Build Mode</strong> and <strong>Program Mode</strong> in Vizor. Your first task is to add an object to your project using patches.

<div class="alert_green">
  <div style="text-align:center">
  	<strong>Set Up</strong>
  </div> 
  <strong>Edit</strong> and <strong>Duplicate</strong> the latest version of your Storycast <strong>template</strong> or start [from scratch](https://vizor.io/techsummer/storycast).
</div>
<br>

<div class="alert_green">
  <div style="text-align:center">
  	<strong>Add An Object</strong>
  </div> 
  Follow the steps below to add an object using <strong>Patches</strong>.
  <ol>
  	<li>
  		In <strong>Build Mode</strong>, press the <strong>K</strong> key to switch to the <strong>Beginning Scene</strong>.
  	</li>

  	<li>
  		Press <strong>Tab</strong> to enter <strong>Program Mode</strong>. Navigate into the <strong>Beginning Scene nested patch</strong> by clicking the <strong>pencil icon</strong>. 
  	</li>

  	<li>
  		To add a 3D object to the scene, drag and drop one from from the <strong>Patches Tab</strong> on the left into the patches area.  It should add a purple <strong>nested patch</strong> with the name of the 3D object. 
		<div style="text-align:center">
			<img src="/images/techsummer/Unit3/3.1/addPatch.gif">
		</div>
  	</li>

  	<li>
  		To appear, the 3D object <strong>nested patch</strong> needs to be connected to the <strong>Elements</strong> patch. The <strong>Elements</strong> patch contains a list of 3D objects to display for the scene. Click and drag a line from the <strong>nested patch</strong> slot to the <strong>Elements</strong> slot.
  		<div style="text-align:center">
			<img src="/images/techsummer/Unit3/3.1/connectPatch.gif">
		</div>
  	</li>

  	<li>
  		Adjusting a 3D object cannot be done in <strong>Program Mode</strong>. Switch from <strong>Program Mode</strong> to <strong>Build Mode</strong> by hitting the <strong>Tab</strong> key. You can use the <strong>move</strong>, <strong>scale</strong> or <strong>rotate</strong> tools with the 3D object.
  		<div style="text-align:center">
			<img src="/images/techsummer/Unit3/3.1/adjustObject.gif">
		</div>
  	</li>
  </ol>
</div>

Those are the basics of adding an object to a scene. Check out the next section for pro tips and warnings on using Vizor.
