---
title: Vizor Project 1
section_title: Introduction to Vizor
type: primitives
layout: docs
parent_section: project3
order: 2
toc: true
---


Virtual Reality Starter Project

## Lesson Plan + Skill Mappings
* Should we tie to ESSA, CC, or other mappings educators are comfortable with?

## Project Prompt & Goals (10 min, 1 min)

Get ready to jump into the world of virtual reality development! By the end of the project, you will:

* Get a first taste of how computer graphics can be applied to creative projects.
* Use a creative platform named Vizor to build a virtual world you can share with anyone using a VR headset.
* Learn the basics of designing a virtual world.

## Requirements

* The Virtual Reality Starter Project is designed to be completed by individual students, not teams.
* WebVR Set Up
* What is VR?

## Computer Graphics and VR (10 min, 2 min)

Computer graphics, also known as CG, is an area of computer science which uses computers to create pictures, models, films, and more. Computer graphics emerged in the United States in the 1950's and since then has been used for many applications.

With a knowledge of computer graphics...

You can use a computer graphics program like PhotoShop to design user interfaces!
<img src="/images/docs/intro_vizor/photoshop.gif">

You can build 3-dimensional (3D) models and animations using a program like Blender!
<img src="/images/docs/intro_vizor/blender.gif">

You can create movies, video games, and more using computer programs such as Adobe Final Cut, Unity or Unreal, and more!
<img src="/images/docs/intro_vizor/unity.gif">


Computer graphics is also the basis of building virtual reality experiences! Here are some virtual worlds built using the vizor.io platform. You'll know how to build a similar world by the end of the lesson.
<img src="/images/docs/intro_vizor/vizor_sample.png">

<img src="/images/docs/intro_vizor/vizor_sample1.jpg">

Credit - Vizor

## Vizor Basics

Enough talk - let's jump into Vizor and get started!

### Creating a Vizor Account
You'll first need to create a Vizor account.

* Navigate to vizor.io and click on the “Sign Up” button.
* Fill out your information on the “Sign Up” screen and click “Create an Account.” 
* You should see a new screen with links to Vizor tutorials, the Vizor Facebook group, and more. Click the “X” button, wait for the scene to load, and you'll be in the Vizor editor!

<img src="/images/docs/intro_vizor/create_account2.png">

### Vizor Editor Guide: Cameras
Many computer graphics programs use multiple cameras. Most often, there will be a “world camera” you can use while you are creating and building your application. You can move the world camera wherever you want to make your work easier. In Vizor, the world camera is called “Editor camera” and you can switch into Editor camera mode by clicking the Editor camera button in the editor. 

<img src="/images/docs/intro_vizor/edit_cam.png">

When you open the Vizor editor, you should be using the Editor camera by default.

A world camera is great to use while working, but what will a user's point of view be? If the user's point of view was the same as your world camera, you'd have to move the world camera into position every time before someone tried your application. It would be more convenient to set where a user's view will always begin. As a result, many computer graphics programs have a second camera to represent a user's starting view. The camera is named differently in different programs, but in Vizor the camera is called the “VR camera.” The VR camera represents where a user's view will be when they start your virtual reality experience. 

The position of the VR camera in Vizor is denoted by the model of a head wearing a VR headset in the editor. 
<img src="/images/docs/intro_vizor/navigation0.png">

You can test the VR camera point of view by selecting the VR camera button in the editor. While in VR camera mode, you can click and drag to test what it would be like for a user to look around your scene.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EiVuDRYkvpA" frameborder="0" allowfullscreen></iframe>

### Vizor Editor Guide: Navigation
Let's learn how to navigate in the editor. Be sure to switch into Editor camera mode.

* To zoom, scroll in and out using mouse or mouse pad.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AgmAzrLSdS4" frameborder="0" allowfullscreen></iframe>

* To rotate your view, click the left mouse button down and drag.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8KJIK2iAR3Y" frameborder="0" allowfullscreen></iframe>

* To pan, click the right mouse button down and drag. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/8tT26p_t5So" frameborder="0" allowfullscreen></iframe>

Play around with navigation in the Vizor editor until you feel comfortable, then move on to the next section!

### Hello Virtual World!

You've learned about the basics of cameras in computer graphics and Vizor navigation, so now it's time to get building!

#### Fun With Objects

In Vizor, you can add 3D objects via the “Patches Menu.” The Patches Menu contains two tabs. The “Objects” tab provides a list of objects you can add into your scene. The “Patches” tab allows you to use computer programming to make your scene dynamic and will be explored later. If you do not see the Patches Menus, click the “Patches” button in the Vizor editor. You can click again to make the Patches Menu disappear. You can also click on the Patches Menu and drag to move the menu around.

<iframe width="560" height="315" src="https://www.youtube.com/embed/B16PH6RZRts" frameborder="0" allowfullscreen></iframe>

Now let's add an object!

* Select the Objects tab in the Patches Menu.
* Select the objects “Objects: Basic” option, then select the “Box” option.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pQFgFhsqX0c" frameborder="0" allowfullscreen></iframe>

You should now see a 3-dimensional box in your scene. You can use the Vizor editor to change the position, size, or rotation of any object. 

* Select your object. You know you've selected an object when red, green, and blue lines appear by the object. Each line represents an “axis” you can use to adjust the object. The plural form of axis is “axes,” which is pronounced “axe-zeez”.
* Select the “Move” button, then click and drag on any of the object axes to change the object position.

<iframe width="560" height="315" src="https://www.youtube.com/embed/npOygI-vQ-8" frameborder="0" allowfullscreen></iframe>

* Select the “Scale” button, then click and drag on any of the object axes to make the object bigger or smaller. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/0CxPw10-xYs" frameborder="0" allowfullscreen></iframe>

* Select the “Rotate” button, then click and drag on any of the object axes to change the object rotation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/NNYuxEe1rCI" frameborder="0" allowfullscreen></iframe>

Finally, you can delete an object at any time by selecting the object and pressing “Backspace” or “Delete” on your keyboard.

## Building a World

You're all set to start building your first virtual world. Add objects to your scene using the Patches Menu and modify the scene as much as you'd like. We recommend only using objects that appear under the “Objects:” items in the Patches Menu.

## Share With The World

One of the coolest parts about Vizor is the ability to share what you build with the world. If you want, you can let anyone with a VR headset see what you've built. 

### Publishing
To publish your project, click the “Publish” button in the Vizor editor. A screen should pop up. Give your project a name and hit the “Publish” button to put your project on the internet for anyone to see.

<img src="/images/docs/intro_vizor/create_account2.png">

Once you hit “Publish” you'll be taken to a website with the URL of vizor.io/(your username)/(your project name). What's a URL? URL stands for Uniform Resource Locator and is basically an internet address for where different websites live. You can find the URL of a website by looking in the browser search bar.

[screen capture: click to highlight a Vizor URL]
If your username is “techstart” and your project name is “my_project,” the URL for your Vizor project is vizor.io/techstart/my_project. You can view, edit and delete all of your projects by visiting vizor.io/(your username) in your browser.

### Viewing

Although you can use Vizor on any computer, you'll need a VR-ready computer or phone set up with WebVR to view Vizor projects in virtual reality. WebVR is a guide for a computer to detect and work with an attached virtual reality headset. If you need to set up WebVR on your computer, visit the WebVR Setup Guide.

Once you have WebVR and your virtual reality headset ready, open Firefox Nightly and enter the URL of your published project. If you click near the bottom of the screen, you'll see an icon which looks like binoculars. On the internet, the icon is often used to start a virtual reality experience. Click the icon and put the headset on to see what you made in virtual reality!

[screen capture: enter VR]

### Submission
If you'd like to be eligible for TechStart awards, be sure to complete the following.

* Complete and publish a scene in Vizor. Don't worry about your project being the best. Submit a project you spent time on and would be happy to show someone, with the exception of inappropriate content. Inappropriate content will not be eligible for awards.

<img src="/images/docs/intro_vizor/submit0.gif">

* Make sure your project can be viewed at vizor.io/(your username), share your Vizor user name with your teacher, and complete the following 3 minute survey: link to post survey.
* Remind your teacher to save your Vizor user name and share your Vizor user name with the TechStart team on the end of the year survey. If your teacher does not share your user name, you will not be able to win awards!



