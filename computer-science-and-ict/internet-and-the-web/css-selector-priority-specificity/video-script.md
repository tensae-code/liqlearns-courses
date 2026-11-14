# Video script — CSS Selector Priority — Which Rule Wins

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A page often gives one element **several rules at once**: the element selector says paragraphs are black, a class says this paragraph is blue, an id says it is red. CSS settles the fight by **priority (specificity)**: an **inline style** (written in the element's style attribute) beats all; below it the **id** selector beats the **class** selector, and the class beats the **element** selector. Vietnam's Grade 12 book closes its CSS strand with this ladder, because until a learner can predict the winner, styling is guessing.
When two rules have **equal priority**, the **later rule in the stylesheet wins** — the cascade reads top to bottom and the last word stands. The working habits follow: style generally first (elements), then classes for groups, ids sparingly for the one special element, and inline styles almost never — because a style that cannot be overridden becomes a trap when the design changes. Debugging a wrong colour is now a method: find every rule that touches the element, and climb the ladder.
