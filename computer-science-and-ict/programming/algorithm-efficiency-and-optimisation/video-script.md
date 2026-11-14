# Video script — Algorithm Efficiency and Optimisation

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A stopwatch measures one machine on one day; **efficiency** is measured by counting the algorithm's **operations** as the input size **n** grows. An algorithm doing about n operations doubles its work when n doubles; one doing about **n²** operations quadruples it — fine for ten items, hopeless for a million. The growth shape, not the constant, decides whether an algorithm survives big data.
**Optimisation** hunts waste: a value **recalculated** inside a loop that could be computed **once before it**; a second pass over data the first pass could have finished; searching an **unsorted** list item by item when sorted data allows halving the search space each step. The rule is to optimise the **growth** first and the details second — and to keep the program correct and readable while making it faster.
