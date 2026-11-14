# Video script — Using a Standard Library

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **standard library** is the collection of **ready-made** functions and objects that **ships with the language itself** — no installing, no importing from strangers. In JavaScript the shelves this chapter uses include **Math** (Math.sqrt, Math.floor, Math.random, PI as Math.PI) and **Date** (the current date and time, and their parts). A library member is known by its **documentation**: what it takes, what it returns, what it promises — the programmer's job is to know the shelves and read the labels, not to rebuild the goods.
Using the library is a **call**: name the member, hand it its values, take its return — let root = Math.sqrt(81); gives 9 without one line of root-finding written. Malaysia's disciplines of use are two: call the library **instead of hand-writing** what it already does correctly (a hand-written random or date routine is a fault waiting), and **check the label** before calling — Math.floor(3.9) gives 3, not 4, because floor promises the whole number **below**; most library 'faults' are labels misread. The standard library is the language's gift of other programmers' tested work; using it well is a form of reading.
