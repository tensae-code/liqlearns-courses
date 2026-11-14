# Video script — IoT Network Architecture

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An IoT **network architecture** arranges: the **things** at the edge (sensors and actuators), the **access network** that links them (short-range wireless, wired, cellular), **gateways** that gather and translate, the **core / cloud** where data is stored and processed, and the **applications** people use. Jordan's Grade 10 architecture is read from the edge inward: every reading travels the same road, and each stop on the road is a place where design choices — and failures — live.
The edge can be arranged as a **star** (every thing talks to one hub — simple, and the hub is a single point of failure), a **mesh** (things relay for each other — far-reaching and stubborn, harder to manage), or a **hybrid** mixing both. The architecture decision weighs range, power, cost and reliability for the actual ground the network must cover — a flat, a farm and a factory floor answer differently, and the book's applications lesson tests exactly that weighing.
