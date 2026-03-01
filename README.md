# CS330-Computational-Graphics
OpenGL 3D graphics project demonstrating object modeling, lighting, texturing, and interactive camera navigation.

## Reflection

### 1. How do I approach designing software?

One design skill I strengthened in this project was learning how to break a 2D reference image into simple 3D parts using primitive shapes. I planned my scene by identifying the main objects first, then deciding which meshes best matched each item (plane for the desk, boxes for the laptop and books, and additional shapes for other details).

My design process was iterative. I started with basic placement and scaling to get the layout correct, then improved the scene step by step by adding textures, lighting, and camera controls. As I tested, I adjusted object positions and sizes to better match the original image and to keep the scene visually balanced.

This approach can be applied to future work by continuing to plan in layers. First build a working base version, then refine visuals and interaction features through small improvements. This helps avoid getting stuck and makes debugging more manageable.

### 2. How do I approach developing programs?

A development strategy I used often was building one requirement at a time and testing after each change. For example, I added objects and confirmed they rendered correctly before moving on to texturing and lighting. This helped me catch issues early instead of debugging multiple changes at once.

Iteration was a major part of my workflow. I tested changes using the debugger and adjusted values like scale, position, and light placement until the scene looked more polished. I also learned that small changes to texture settings can make a noticeable difference in visual quality.

My approach evolved over the milestones. Early on, I focused on getting shapes on screen. Later, I focused more on organization and reusability by using functions that handled consistent tasks such as applying transformations, textures, and materials. That structure made the final integration smoother.

Custom functions supported modular code and cleaner rendering. Functions like loading textures, binding textures, setting transformations, and setting shader values helped reduce repeated code and made it easier to apply updates across the scene consistently.

### 3. How can computer science help me in reaching my goals?

This project helped me build a stronger foundation in computational graphics and visualization by applying OpenGL concepts in a complete end to end project. I gained experience working with coordinate systems, transformations, textures, lighting, and interactive camera movement, which are skills that apply to many areas of software development.

In my future educational path, these skills will help me better understand how graphics pipelines work and how performance and visual quality can be balanced. I also feel more confident working in C++ with external libraries and debugging issues in Visual Studio.

In my professional path, I can apply these skills to roles that involve visualization, simulations, or building interactive tools. Even outside of game development, being able to communicate how a visual system is designed and implemented is valuable for technical teams and stakeholders.
