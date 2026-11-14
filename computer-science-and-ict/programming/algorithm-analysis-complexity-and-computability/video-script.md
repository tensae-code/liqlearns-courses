# Video script — Algorithm Analysis — Complexity and Computability

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Algorithm analysis** studies an algorithm's needs — **time and memory** — as the problem's size grows, without running it. Its measure is **complexity**: how the needed steps grow with the input — a growth that stays polite (following the input) against a growth that explodes (doubling with every added value, the **exponential** blow-up that makes exact answers useless even on fast machines). Analysis is the theory behind the practical rule: choose the algorithm by its growth, not by its first small test.
The same chapter opens the door of **computability (υπολογισιμότητα)**: the theory of what can be computed at all. Its hard lesson: some perfectly clear problems have **no algorithm** — no procedure that always ends with the right answer — and others are computable in principle but **intractable**, their exact cost outgrowing any real machine. Knowing the boundary is part of computer science itself: it tells the programmer which problems to solve exactly, which to approximate, and which to stop attacking head-on.
