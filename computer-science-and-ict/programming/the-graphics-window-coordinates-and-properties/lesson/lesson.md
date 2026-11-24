# The Graphics Window — Coordinates and Properties

## Do it first

Text was the first world; pictures are the second. Mongolia's Grade 11 graphics work begins with the canvas itself: the GraphicsWindow, the grid of points it is measured in, and the properties that shape it before anything is drawn.

## Sub lesson 1 — The GraphicsWindow and its coordinates

The **GraphicsWindow** is Small Basic's drawing object: open it and the program gains a canvas. Every point of the canvas has **coordinates**: **x**, the distance rightward from the left edge, and **y**, the distance **downward** from the top edge — the origin (0, 0) sits at the **top-left** corner, and y grows downwards, the screen's way, not the maths graph's way. Every drawing command in the next lessons is an order given in these coordinates: a shape is its points, named by x and y.

In your mind's eye: the GraphicsWindow and its coordinates.

## Sub lesson 2 — Window properties — shaping the canvas

Before drawing, the program sets the window's **properties**: its **Width** and **Height** in pixels, its **Title** shown in the title bar, and its **BackgroundColor**. Properties are read and written like variables of the window — `GraphicsWindow.Width = 600` — so the canvas itself is part of the program's design: the draughtsman chooses the paper before the picture. Mongolia's order is deliberate: canvas and coordinates first, shapes second — no drawing command can be understood until the grid it lands on is.

In your mind's eye: window properties — shaping the canvas.

## Say it to your companion

Tell your companion, in your own words: The **GraphicsWindow** is Small Basic's drawing object: open it and the program gains a canvas. Every point of the canvas has **coordinates**: **x**, the distance rightward from the left edge, and **y**, the distance **downward** from the top edge — the origin (0, 0) sits at the **top-left** corner, and y grows downwards, the screen's way, not the maths graph's way. Every drawing command in the next lessons is an order given in these coordinates: a shape is its points, named by x and y. Before drawing, the program sets the window's **properties**: its **Width** and **Height** in pixels, its **Title** shown in the title bar, and its **BackgroundColor**. Properties are read and written like variables of the window — `GraphicsWindow.Width = 600` — so the canvas itself is part of the program's design: the draughtsman chooses the paper before the picture. Mongolia's order is deliberate: canvas and coordinates first, shapes second — no drawing command can be understood until the grid it lands on is. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Small Basic's drawing object — the program's canvas. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: x (rightward) and y (downward). Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: At the top-left corner. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Downwards — the screen's way. Do this with a real example of your own and write or say how you know it is right.
