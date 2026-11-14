# Video script — Inserting Elements and Computations in Arrays

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Elements are **entered** one by one — typed in a **fill loop** (cin >> a[i]) or assigned from the program — while a counter **n** records **how many elements are live**. Capacity and count are different numbers: the array may hold 100 and contain 7. Every later walk uses **n**, not the capacity, as its limit.
With the array filled, **basic computations** walk the live elements: the **sum**, the **average** (sum divided by n — the live count, not the capacity), each element transformed (doubled into a second array, say). The classic fault is dividing by capacity or walking into the unfilled tail where garbage values wait; the live-count discipline prevents both.
