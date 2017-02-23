---
title: Vizor Starter Project
section_title: Introduction to Vizor
type: unit3
layout: docs
parent_section: project3
order: 2
toc: true
---


# Building A World

## Project Goals
Get ready to jump into the world of virtual reality (VR) development! We will not focus on code until later projects, but the project will introduce you to VR design. By the end of the project, you will:
* Get a first taste of how computer graphics can be used to create any world you can imagine.
* Use a platform named Vizor to build a virtual world you can share with anyone.
* See hands-on examples of how to design virtual worlds from engineers at Facebook.

Want an idea of what you'll be able to build? Check out the following project built by someone else in Vizor. You can click and drag to change your view!
<script src="//vizor.io/scripts/embed.js" data-vizorurl="//vizor.io/embed/edelblut/mountain_top_wip_02" ></script>

## Requirements and Suggestions

* The Virtual Reality Starter Project is designed to be completed by individual students, not teams.
* Similar to many computer graphics platforms, Vizor is most easily used with a mouse.
* Vizor projects are most exciting in VR! To use VR with Vizor, you'll need one computer set up with WebVR.

## Computer Graphics and VR 

Computer graphics, also known as CG, is a field of computer science which uses computers to create pictures, models, films, and more. CG emerged in the United States in the 1950's and since then has been used for many applications.

With a knowledge of computer graphics you can...

* use an image editing program like PhotoShop!

<img src="/images/docs/intro_vizor/photoshop.gif">

* build 3-dimensional (3D) models and animations using a program like Blender!

<div style="text-align:center"><img src="/images/docs/intro_vizor/blender.gif"></div>

* create movies, video games, and more using computer programs such as Adobe Final Cut, Unity or Unreal, and more!

<img src="/images/docs/intro_vizor/unity.gif">

Computer graphics is also the basis of building virtual reality experiences!

## Vizor Basics

Enough talk - let's jump into Vizor and get started!

### Creating a Vizor Account
You'll first need to create a Vizor account.

* Navigate to <a href="https://vizor.io" target="_blank">vizor.io</a> in your web browser and click on the “Sign Up” button.
* Fill out your information on the “Sign Up” screen and click “Create an Account.” 
* You should see a new screen with links to Vizor tutorials, the Vizor Facebook group, and more. Click the “X” button, wait for the scene to load, and you'll be in the Vizor editor!

<img src="/images/docs/intro_vizor/create_account2.png">

### Vizor Editor Guide: Cameras
Many computer graphics programs use multiple cameras. Most often, there will be a “world camera” you use to create and build your application. You can move the world camera wherever you want at any time. In Vizor, the world camera is called “Editor camera” and you can switch into Editor camera mode by clicking the Editor camera button in the editor.

<img src="/images/docs/intro_vizor/edit_cam.png">

When you open the Vizor editor, you should be using the Editor camera by default.

A world camera is great to use while building, but what will your user's point of view be? Many computer graphics programs also have a second camera to represent your user's view. The camera is named differently in different programs, but in Vizor the camera is called the “VR camera.” The VR camera represents where your user's view will be when they start. 

The position of the VR camera in Vizor is denoted by the model of a head wearing a VR headset in the editor. 

<img src="/images/docs/intro_vizor/navigation0.png">

You can test the VR camera point of view by selecting the VR camera button in the editor. While in VR camera mode, you can click and drag to test what it would be like for a user to look around your scene.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EiVuDRYkvpA" frameborder="0" allowfullscreen></iframe>

At any time, you can toggle between the Editor camera and VR camera by pressing "V".

### Vizor Editor Guide: Navigation
Let's learn how to navigate in the editor. Be sure to switch into Editor camera mode.

* Zooming: scroll in and out using mouse or mouse pad.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AgmAzrLSdS4" frameborder="0" allowfullscreen></iframe>

* Rotating Your View: click the left mouse button down and drag.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8KJIK2iAR3Y" frameborder="0" allowfullscreen></iframe>

* Panning: click the right mouse button down and drag. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/8tT26p_t5So" frameborder="0" allowfullscreen></iframe>

Play around with navigation in the Vizor editor until you feel comfortable, then move on to the next section!

### Hello Virtual Reality!

You've learned about the basics of cameras in computer graphics and Vizor navigation. There's tons more that you could learn about computer graphics and Vizor, but for now let's focus on designing a virtual world. Let's get building!

#### Fun With Objects

In Vizor, you add 3D objects using the “Patches Menu.” The Patches Menu contains two tabs. 

* The “Objects” tab shows objects you can add to your scene. 
* The “Patches” tab allows you to use programming to make your scene dynamic and will be explored in later projects. 

If you do not see the Patches Menus, click the “Patches” button in the Vizor editor. You can click again to make the Patches Menu disappear. You can also click on the Patches Menu and drag to move the menu around.

<iframe width="560" height="315" src="https://www.youtube.com/embed/B16PH6RZRts" frameborder="0" allowfullscreen></iframe>

Now let's add an object!

* Select the Objects tab in the Patches Menu.
* Select the objects “Objects: Basic” option, then select the “Box” option.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pQFgFhsqX0c" frameborder="0" allowfullscreen></iframe>

You should now see a 3-dimensional box in your scene. You can use the Vizor editor to change the position, size, or rotation of any object. 

* Select your object. You've selected an object when red, green, and blue lines appear by the object. Each line represents an “axis” you can use to adjust the object. The plural form of axis is “axes,” which is pronounced “axe-zeez”.
* Select the “Move” button, then click and drag on any of the object axes to change the object position.

<iframe width="560" height="315" src="https://www.youtube.com/embed/npOygI-vQ-8" frameborder="0" allowfullscreen></iframe>

* Select the “Scale” button, then click and drag on any of the object axes to make the object bigger or smaller. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/0CxPw10-xYs" frameborder="0" allowfullscreen></iframe>

* Select the “Rotate” button, then click and drag on any of the object axes to change the object rotation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/NNYuxEe1rCI" frameborder="0" allowfullscreen></iframe>

### Advanced Controls

You can delete an object at any time by selecting the object and pressing “Backspace” or “Delete” on your keyboard. 

You can undo your changes by pressing the “Ctrl” and “Z” button on your keyboard. 

With an object selected, you can press “Alt” and move the object to create a copy.

### Building a World

You're all set to start building your first virtual world. Add objects to your scene and modify the scene as much as you'd like. We recommend only using objects that appear under the “Objects:” items in the Patches Menu. Make a scene you would like to show a friend and add at least 5 objects to the scene before you continue.

## Share With The World

One of the coolest parts about Vizor is the ability to share what you build with the world. If you want, you can let anyone with a VR headset see what you've built. 

### Publishing
To publish your project, click the “Publish” button in the Vizor editor. A screen should pop up. Give your project a name and hit the “Publish” button to publish your project on the internet. You'll then be taken to a website with the URL of **vizor.io/(your username)/(your project name)**. What's a URL? URL stands for Uniform Resource Locator and is basically an internet address for where different websites live.

If your username is “techstart” and your project name is “my_project,” the URL for your Vizor project is vizor.io/techstart/my_project. You can view, edit and delete all of your projects by visiting **vizor.io/(your username)** in your browser.

### Viewing

Although you can use Vizor on any computer, you'll need a computer or phone with WebVR to view Vizor projects in virtual reality.

Once you have WebVR and your virtual reality headset ready, open Firefox Nightly on your computer and enter the URL of your published project. If you click near the bottom of the screen, you'll see an icon which looks like binoculars. On the internet, that icon is used to start a VR experience. Click the icon and put the headset on to see what you made in virtual reality!

After you've viewed your project in virtual reality, please complete the following 3-minute survey: [https://www.surveymonkey.com/r/6JF7XLL].


