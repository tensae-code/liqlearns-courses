# Video script — Pattern Recognition in Search and Sort

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Every method in the chapter is a **pattern repeated**: linear search repeats **check–next**; binary search repeats **check the middle–halve**; bubble sort repeats **compare neighbours–maybe swap**, pass within pass; bucket sort repeats **place by size**, then gathers. Recognising the pattern means being able to say, at any step, **what happens next and why** — the next check is forced by the pattern, not chosen by the searcher. A trace that surprises you at some step means either the pattern was misrecognised or the algorithm has a fault — the pattern is the standard the trace is checked against.
Patterns also **compare** the methods: the check–next pattern grows one step per item, the halving pattern collapses the field, the neighbour pattern must repeat whole passes. Malaysia's use is practical: given a list and a job, the patterns predict the **work** each method will do, and the prediction chooses the method — order the list once if halving will be used often; accept the passes when the list is nearly sorted. Recognising the pattern is what turns four memorised methods into one understood family.
