---
title: Kit Installation
type: introduction
layout: docs
parent_section: introduction
order: 3
toc: true
---

## Introductory Videos for the Oculus Rift CV1

Good videos for getting acquainted with the Oculus Rift hardware.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EiY2xYHzcus?list=PLL2xVXGs1SP5Bdvdz7qYAXlveqGteoSiX" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/-1izYqKyJ80?list=PLL2xVXGs1SP5Bdvdz7qYAXlveqGteoSiX" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/09SiWe0zWvw?list=PLL2xVXGs1SP5Bdvdz7qYAXlveqGteoSiX" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/LQe8W40Q1pg?list=PLL2xVXGs1SP5Bdvdz7qYAXlveqGteoSiX" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/syuAfehcjCo?list=PLL2xVXGs1SP5Bdvdz7qYAXlveqGteoSiX" frameborder="0" allowfullscreen></iframe>

## Instructions for Installation

[leapmotion]: https://developer.leapmotion.com/assets/Leap%20Motion%20VR%20Best%20Practices%20Guidelines.pdf
[oculus]: https://developer.oculus.com/documentation/intro-vr/latest/concepts/bp_intro/

Designing for VR is different than designing for flat experiences. As a new
medium, there are new sets of best practices to follow, especially to maintain
user comfort and presence. This has been thoroughly written about so we defer
to these comprehensive guides:

- [Oculus Best Practices (for VR)][oculus]
- [Leap Motion VR Best Practices Guidelines][leapmotion]

Some things to note:

- The common golden rule is to never unexpectedly take control of the camera
  away from users.
- Units (such as for position) should be considered meters. This is because the
  WebVR API returns pose in meters which is fed into most camera controls. By considering
  units as meters, we achieve expected scale.




