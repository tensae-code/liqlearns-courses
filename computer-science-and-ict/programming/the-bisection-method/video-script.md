# Video script — The Bisection Method

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Given a **bracket [a, b]** (f of opposite signs at its ends), bisection computes the **midpoint** c = (a + b) / 2 and tests f(c): the half-interval whose ends **still change sign** becomes the new bracket — if f(a)·f(c) < 0, the root is in [a, c]; else in [c, b]. Each step halves the cage. The root itself is never computed — it is **cornered**, until the cage is smaller than the demanded precision and any point of it (the midpoint, say) may be reported as the root, with the cage's width as its error bound.
After **n steps**, the bracket's width is **(b − a) / 2ⁿ** — certainty you can count in advance: to squeeze [0, 1] below 10⁻³ needs 10 steps (2¹⁰ = 1024). Bisection will never run away, never divide by a slope, never be fooled by the function's shape — its price is this **fixed, unhurried rate** (one binary digit of precision per step), which faster methods beat when they behave and disgrace themselves when they don't. The method is the chapter's benchmark of honesty: certainty first, speed as a luxury.
