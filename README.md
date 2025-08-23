# CS-330-Comp-Graphic-and-Visualization
Created for the CS-330 Course

**How do I approach designing software?**

I start by clarigying the user experience and visual goals, then translate them into small, testable features. I sketch the scene layout, list core systems (camera, objects, lighting, interaction), and define clear interfaces between them. I aim for modular clases and data-driven parameters so I can tune visuals without rewriting code.

New design skills I developed
• Turning reference art into a blocked out scene, then refining geometry, materials, and lighting.
• Balancing realism and performance by choosing which effects (shadows, textures, outlines) deliver the biggest impact.

Design process I followed
• Gray-box -> playable prototype -> visual polish: start with primitives, wire up controls/physics, then iterate on materials, colors, and composition.

Tactics I'll reuse
• Separate "simulation" from "rendering", keep constants centralized, and iterate in small loops with frequent visual checks.

**How do I approach developing programs?**

I break features into minimal slices, get them running, then iterate with profiling and visual debugging. I keep commits small and reversible.

New development strategies I used
• Parameterizing visuals (colors, sizes, speeds) with constants for fast iteration. 
• Incremental collision/physics tweaks guided by simple math checks (normals, clamping).

Role of iteration
Frequent test runs shaped the feel of motion, bounce behavior, and readability of the scene, each pass improved clarity and stability.

How my approach evolved
I moved from a single, monolithic loop to well-scoped classes (bricks/objects, balls, input), clearer update/draw ordering, and more consistent coordinate handling.

**How can computer science help me reach my goals?**

Educational pathway
Computational graphics strengthened my linear algebra and real time systems skills.
Modeling transforms, normals, and camera motion deepened my understanding of math-in-code.

Professional pathway
The project demonstrates I can ship interactive visuals, useful for UI/UX prototyping,
simulation, game/AR work, and data visualization, where readable rendering and responsive interaction matter.
