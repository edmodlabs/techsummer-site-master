---
title: FAQ
type: faq
layout: page
toc: true
---

## What is A-Frame?

A-Frame is an open-source framework for easily creating WebVR experiences with HTML. It is designed and maintained by the Mozilla VR team ([MozVR][mozvr]). A-Frame wraps [three.js][three] and WebGL in HTML custom elements. This enables web developers, designers, and artists to create 3D/VR scenes without having to learn WebGL's complex low-level API. Because WebGL is ubiquitous in modern browsers on desktop and mobile, A-Frame experiences work across desktop, iOS, Android, and [Oculus Rift][oculus] headsets.

A-Frame features a smooth learning curve between beginner ease of use and advanced developer flexibility. Beginners start with easily understood primitives like cubes, videos, models, and skies. Advanced users can use JavaScript to imperatively create interactive scenes or dive into its underlying [entity-component-system pattern][ecs], a design pattern popular in the game industry that favors composition over inheritance. Because A-Frame is built around building blocks that can be extended and combined into limitless combinations, it provides a high degree of creative freedom. And being just an abstraction layer, A-Frame is capable of doing anything that [three.js][three] can.

## Why was A-Frame created?

We felt WebVR development was too difficult and sought tools that would make it faster, easier, and more enjoyable. Over the course of 2015, the MozVR team was creating many WebVR experiments with [three.js][three]. To speed up workflows, we began to experiment with custom elements wrapping three.js. In creating these tools, we drew inspiration from both existing declarative 3D/VR tools (e.g., [JanusVR][janus], [GLAM][glam], [SceneVR][scene]), and from game development best practices. As the tools matured, we felt that they might be able to address what we felt were gaps in the market, particularly around ease of use and webbiness. We envisioned A-Frame as having the following:
