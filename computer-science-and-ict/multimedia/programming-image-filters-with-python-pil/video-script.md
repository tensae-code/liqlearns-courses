# Video script — Programming Image Filters with Python PIL

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A photo is a grid of numbers. Every pixel: three numbers, red, green, blue.

Python's library Pillow opens the grid. Your program can read the three numbers at any place — and write new numbers back.

A filter is just a rule, applied to every pixel. Two loops walk the whole grid.

Grey: replace the three numbers by their average. Negative: subtract each number from 255. Darker: multiply by a fraction.

Run the loops, and a real photo changes in your hands. Only remember the book's discipline: save under a new name. The original does not come back.
