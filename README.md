skulpt.js
=========

### Introduction

This is a JavaScript / GLSL height field terrain sculpting library for Three.js plane meshes.

### Features

* GPU-based sculpting for fast performances on high resolution meshes
* Load custom greyscale height map as the base terrain
* Different sculpt brushes: add, remove
* Highlight on sculpt brush area to visually indicate sculpting location
* Retrieve a proxy texture for creating a proxy mesh for CPU operations e.g. collision detection with a CPU-based rigid body system

### Examples

**1) Terrain Load & Sculpt** [[Demo](http://skeelogy.github.io/skulpt.js/examples/skulpt_terrain.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skulpt.js/screenshots/video_skulpt_terrain.jpg)](http://www.youtube.com/watch?v=f8oLzMC8Uz4)

* Loading of greyscale height map
* Terrain sculpting using the mouse cursor

**2) Interaction With Dynamic Rigid Bodies** [[Demo](http://skeelogy.github.io/skunami.js/examples/skunami_twoWayCoupling.html)]

&nbsp;&nbsp;&nbsp;[![ScreenShot](http://skeelogy.github.io/skunami.js/screenshots/video_skunami_twoWayCoupling.jpg)](http://www.youtube.com/watch?v=f_6aTwP2lMg)

* Fetching of proxy texture from the GPU to create a low-res terrain for collision detection with dynamic rigid bodies

### Documentation

* [1.0.x](http://skeelogy.github.io/skulpt.js/docs/1.0.x)

### Browser Support

Tested only in Google Chrome (recommended) and Mozilla FireFox

### License

Released under The MIT License (MIT)<br/>
Copyright (c) 2013 Skeel Lee ([http://cg.skeelogy.com](http://cg.skeelogy.com))
