---
title: Introduction
section_title: Introduction
type: introduction
layout: docs
order: 1
parent_section: docs
section_order: 1
---


# What is A-Frame?

A-Frame is an open-source WebVR framework for creating virtual reality (VR)
experiences with HTML. We can build VR scenes that work across smartphones,
desktop, the Oculus Rift, and the room-scale HTC Vive.

```html
<html>
  <head>
    <script src="https://aframe.io/releases/0.3.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box color="#6173F4" opacity="0.8" depth="2"></a-box>
      <a-sphere radius="2" src="texture.png" position="1 1 0"></a-sphere>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```

### Entity-Component-System