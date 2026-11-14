# Video script — Simulating an Elevator in Scratch — Floors, Doors and Direction

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The lift’s pieces are sprites with jobs: **floor-number sprites with several costumes** (one costume per floor number), **door sprites that glide open and closed**, **open/close buttons**, and **direction arrows** showing the lift’s travel. The stage becomes the lift shaft, drawn and working.
Three variables steer: **current floor, new floor and direction**. The movement logic is careful logic — **repeat-until and wait-until with AND/OR** move the lift **floor by floor** towards the new floor, stop it on arrival, and only then glide the doors. A simulation must obey the real machine’s order: arrive first, doors after.
