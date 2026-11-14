# Video script — Testing an Algorithm

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

To **test** an algorithm is to run it — on paper, step by step — with chosen input values, and compare the result it produces with the result you already know is right. If the two match on every test, the algorithm earns trust; if they differ, the step where the trace leaves the right path is where the fault lives. Testing is done before any computer sees the algorithm, with pencil, paper and patience.
Good tests are chosen, not random: an **ordinary** value from the middle of the range, the **edges** — the smallest and largest allowed — and a value that should be refused or handled specially, if the problem has one. Write each test as a small table: input, expected result, result the algorithm gives, verdict. An algorithm that passes only ordinary values may still break at the edges, which is exactly where faults like to hide.
