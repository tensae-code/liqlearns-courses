# Video script — Sensing the Mouse's X and Y Position in Scratch

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The mouse x and mouse y reporters give the pointer's position on the stage's grid: mouse x counts left–right, from −240 at the left edge to 240 at the right; mouse y counts down–up, from −180 at the bottom to 180 at the top, with 0, 0 at the centre — the same grid the sprites' positions use. The values change as the mouse moves, without any click: the reporters are read live, moment by moment, by any script that asks.
With the two reporters a program can answer the pointer: a sprite can go to the pointer's x while keeping its own height, a game can test whether the pointer is in a chosen region — x greater than a number, y between two numbers — and a drawing can follow the pointer's numbers instead of the pointer itself. The sensing is the program's way of asking the user's hand where it is: conditions built on mouse x and mouse y turn the whole stage into a control the user already knows how to use.
