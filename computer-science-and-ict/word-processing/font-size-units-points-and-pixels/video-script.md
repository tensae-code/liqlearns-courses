# Video script — Font Size Units — Points and Pixels

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Print measures type in **points (pt)**: one point is **1/72 of an inch** (about 0.35 mm), a unit inherited from metal type. A font's size is the height of its **em** — roughly the distance from the top of its tallest letters to the bottom of its lowest descenders, not the height of any single letter, which is why two fonts at 12 pt can look different sizes. Body text in books commonly sits at 10–12 pt; Armenia's Grade 9 book teaches font measurement units (§11) inside its web-and-print block, between colour systems and operating systems.
Screens measure in **pixels (px)** — the screen's own dots. The bridge between the units: at the CSS reference density, **1 pt = 4/3 px**, so 12 pt type is 16 px — the common default body size on the web. Because real screens pack pixels at different densities, a px on a phone is not a fixed physical size; that is why web type is also set in relative units (em, rem) that scale with the reader's settings. Rule of thumb: points for print, pixels (or relatives) for screens, and never assume they match without the 4/3 bridge.
