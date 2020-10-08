A (mathy) presentation on how raycasting-based picking -- selecting an object -- is done in virtual 3D worlds.

[View it directly in your browser!](https://legends2k.github.io/3d-picking/)

# Motivation

It’s interesting to know that 3D rendering, which involves a perspective _projection_, is essentially a dimension loss.  How then do we select through 2D in a 3D world?

* “Hey, consoles have joysticks, not pointing devices!”
    - Sure, but game design tools use mouse extensively
* Picking happens on every click
    - Better to know the underlying math
* Curiosity: challenge of selecting in 3D with a 2D input
    - Intuitive in 2D but unnatural in 3D
    - How is the loss in dimension compensated?
* Fun to learn!
