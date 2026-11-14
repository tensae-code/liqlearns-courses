# Video script — Parallel and Serial Transmission

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Parallel transmission** sends a whole group of bits **at the same time**, each on its own wire — eight wires carry a byte in one step. It is fast per step and simple in idea, but expensive in road: many wires, and over distance the bits drift out of step (**skew**) until the group arrives ragged. Parallel therefore lives at **short distances** — inside the computer and to nearby devices — where its wires are short and its speed is real.
**Serial transmission** sends bits **one after another** along a single channel: slower per step, but one road serves any distance, the bits cannot fall out of step because they queue, and the cost stays low. Nearly everything that travels far is serial — network cables, internet links, the connections of this whole title. The comparison closes the lesson: parallel wins the sprint inside the machine; serial wins every journey beyond it — which is why the modern world is built serial, and why the next lesson's question — how the receiver keeps time with the sender — matters at all.
