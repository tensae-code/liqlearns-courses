# Video script — Modular Programs with Arrays

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **modular program** divides its work among **subprograms**, each doing **one job** well. Around an array, the natural modules are the array's career: a **fill** module that reads values into the array, a **process** module that works on them (a total, an average, a highest), and a **print** module that presents them. Each module is written and tested **on its own**, with the array handed to it — a module that fills must not also average, because a fault then has two homes and a test cannot tell them apart.
The **main program** shrinks to a conductor: declare the array, then **call** the modules **in order** — fill, process, print — passing the array (and its size) to each. Values a module works out for the conductor are **returned** or left in shared results as the design states. Malaysia's gain is the chapter's closing argument for modules: change how printing looks and only the print module is opened; test the averaging and only the process module is run. The array is the shared stage; the modules are the actors; the main program is the order of the play.
