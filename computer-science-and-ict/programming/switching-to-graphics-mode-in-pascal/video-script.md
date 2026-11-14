# Video script — Switching to Graphics Mode in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Graphics work begins with the **Graph unit** named in **uses**, and the call **InitGraph**, which loads the graphics driver and switches the screen from text mode to **graphics mode** — a grid of points the program can light one by one. Until InitGraph runs, the drawing operators have no canvas; the book gives the switch its own lesson before any figure is drawn.
In graphics mode every point has **coordinates**: x grows to the right, y grows **downward** from the top-left corner — the opposite of the maths graph, and the cause of most first mistakes. Work ends with **CloseGraph**, which returns the screen to text mode. Open the mode once, draw everything, close it once: that frame holds every graphics program in the course.
