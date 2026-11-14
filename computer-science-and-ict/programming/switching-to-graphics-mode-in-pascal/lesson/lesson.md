# Switching to Graphics Mode in Pascal

## Do it first

Before Pascal can draw a single point, the screen must change its mode: from text to graphics. Grade 9's lesson is that switch — InitGraph, the Graph unit, and closing the mode properly.

## Sub lesson 1 — InitGraph — entering graphics mode

Graphics work begins with the **Graph unit** named in **uses**, and the call **InitGraph**, which loads the graphics driver and switches the screen from text mode to **graphics mode** — a grid of points the program can light one by one. Until InitGraph runs, the drawing operators have no canvas; the book gives the switch its own lesson before any figure is drawn.

[Picture — InitGraph — entering graphics mode]

## Sub lesson 2 — Coordinates and CloseGraph

In graphics mode every point has **coordinates**: x grows to the right, y grows **downward** from the top-left corner — the opposite of the maths graph, and the cause of most first mistakes. Work ends with **CloseGraph**, which returns the screen to text mode. Open the mode once, draw everything, close it once: that frame holds every graphics program in the course.

[Picture — Coordinates and CloseGraph]

## Say it to your companion

Tell your companion, in your own words: Graphics work begins with the **Graph unit** named in **uses**, and the call **InitGraph**, which loads the graphics driver and switches the screen from text mode to **graphics mode** — a grid of points the program can light one by one. In graphics mode every point has **coordinates**: x grows to the right, y grows **downward** from the top-left corner — the opposite of the maths graph, and the cause of most first mistakes. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The Graph unit. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Loads the graphics driver and switches the screen to graphics mode. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The top-left corner. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Downward. Do this with a real example of your own and write or say how you know it is right.
