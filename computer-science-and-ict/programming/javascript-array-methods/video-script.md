# Video script — JavaScript Array Methods

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

JavaScript arrays carry built-in **methods**. The end-and-start family changes the array itself: **push** adds at the end, **pop** removes from the end, **unshift** adds at the start, **shift** removes from the start, and **splice** removes or inserts at any position. Each returns something useful — push returns the new length, pop and shift return the removed element. Armenia's Grade 12 student book closes with a reference section on array methods (p. 75) — the course's own quick-lookup, kept at the back like a dictionary.
The second family works *over* the array without necessarily changing it: **join** builds a string from the elements, **slice** copies a chosen stretch, **forEach** runs a function on every element, **map** builds a new array of transformed elements, and **filter** builds a new array of only the elements that pass a test. The modern style prefers map/filter over hand-written loops: the code says *what* (double them; keep the passing ones) and the method does the walking. Searching joins the family too — **indexOf** finds a value's place, and **includes** answers yes or no.
