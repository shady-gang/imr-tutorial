# Hardware Accelerated Graphics with Modern Vulkan

This tutorial is meant to be a gentle, top-down introduction to modern GPU programming, from the lens of real-time graphics and the Vulkan API.

Prior experience with other GPU APIs such as CUDA, OpenGL or DirectX is not assumed, but familiarity with graphics concepts such as transformation matrices, primitive intersections and simple ray-tracing will be.
For students taking the eponymous seminar at Saarland University, we require having completed our Introduction to Computer Graphics course, which covers all these concepts.
Proficiency with C++ and CMake will also be a requirement, this tutorial is not there to teach you how to program !

This tutorial is based on the [IMR](https://github.com/shady-gang/imr) framework, co-developed with it.
The structure of this tutorial will roughly follow the example programs in IMR, but will give you opportunities for exercises, so we suggest not looking at the code of samples past the point you're in the tutorial.
Or do, we don't have a way to enforce any rules here.

### Is this a Vulkan tutorial, or an IMR tutorial ?

We'll purposefully "hide" a lot of the complexity of Vulkan at first.

# Table of Contents

 * 0: [Motivation, Background and Setup](01_motivation.md)
 * 1: Getting a Triangle on the screen
   * 1.1: [Getting pixels on the screen](11_pixels_on_screen.md)
   * 1.2: Running code for each pixel
   * 1.3: The first Triangle
   * 1.4: The Cube
   * 1.5: Drawing multiple cubes, correctly
 * 2: Graphics pipelines
   * 2.1: Issues with previous approach, solutions, conclusion
   * 2.2: Partially programmable pipelines
   * 2.3: History lesson
   * 2.4: Overview of geometry processing