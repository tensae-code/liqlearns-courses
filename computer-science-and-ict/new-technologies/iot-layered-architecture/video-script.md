# Video script — IoT Layered Architecture

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **layered architecture** divides a system into stacked layers, each with its own job, each serving the layer above and using the layer below. The IoT stack begins at the physical world and rises to the user: **perception** (sensing), **network** (carrying), **processing** (storing and making sense), and **application** (serving people). A fault can be hunted layer by layer; a better sensor can be swapped in without rewriting the application.
Each layer has named **functions**: perception collects data from things; the network layer transmits it reliably and addresses its journey; processing stores, analyses and decides; the application layer presents services — the dashboard, the alert, the automatic action. Between the layers sit **interfaces** — agreed ways of handing work across — and beneath the whole stack run the cross-cutting concerns, above all **security and management**, which no single layer owns alone.
