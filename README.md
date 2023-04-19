# ScrollBaseAnimation

This repository contains code for a simple scroll-based animation made with Three.js. The animation features three 3D objects that rotate and move in response to user scrolling. Additionally, there is a background of particles that respond to mouse movement.

### Demo
You can view a live demo [here] (https://anastasiyanikalayeva.github.io/ScrollBaseAnimation/).

### Usage

To use this code, first clone the repository. Then, open the index.html file in a web browser. The animation should start automatically.

### Dependencies

This code uses the following libraries:

- Three.js
- lil-gui
- GSAP

All dependencies are included in the libs directory and are loaded using ES6 module syntax.

### Customization

The color of the objects in the animation can be changed using the color picker in the top-right corner of the screen. Additionally, the textures used for the particles and the gradient on the objects can be changed by modifying the file paths in the code. Finally, the rotation and movement of the objects in response to user scrolling can be customized by modifying the gsap.to() function in the window.addEventListener('scroll') function.