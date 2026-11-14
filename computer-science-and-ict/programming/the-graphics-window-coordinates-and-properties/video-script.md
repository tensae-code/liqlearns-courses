# Video script — The Graphics Window — Coordinates and Properties

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **GraphicsWindow** is Small Basic's drawing object: open it and the program gains a canvas. Every point of the canvas has **coordinates**: **x**, the distance rightward from the left edge, and **y**, the distance **downward** from the top edge — the origin (0, 0) sits at the **top-left** corner, and y grows downwards, the screen's way, not the maths graph's way. Every drawing command in the next lessons is an order given in these coordinates: a shape is its points, named by x and y.
Before drawing, the program sets the window's **properties**: its **Width** and **Height** in pixels, its **Title** shown in the title bar, and its **BackgroundColor**. Properties are read and written like variables of the window — `GraphicsWindow.Width = 600` — so the canvas itself is part of the program's design: the draughtsman chooses the paper before the picture. Mongolia's order is deliberate: canvas and coordinates first, shapes second — no drawing command can be understood until the grid it lands on is.
