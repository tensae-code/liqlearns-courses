# Video script — Classes — Abstraction, Encapsulation, Inheritance, Polymorphism

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Abstraction (αφαίρεση)** is the class-designer's first cut: keep **only the properties and actions the problem needs** — a pupil-class holds name and marks, not shoe size — because a class is a decision about what matters. **Encapsulation (ενθυλάκωση)** seals the chosen data **inside** the object: other code reaches it only through the object's own methods, so the object's rules (a mark can never exceed 100) cannot be bypassed from outside. Together they are why objects stay trustworthy as programs grow.
**Inheritance (κληρονομικότητα)** builds a **descendant class** from an **ancestor**: the descendant receives the ancestor's properties and methods and adds or sharpens its own — one design, a family of refinements, no rewriting. **Polymorphism (πολυμορφισμός)** lets **one message call each class's own behaviour**: 'draw yourself' draws a circle in the circle class and a square in the square class, while the sender writes the message once. The unit teaches the family with class diagrams, ancestor above descendant, so the learner reads the family tree before writing a line of it.
