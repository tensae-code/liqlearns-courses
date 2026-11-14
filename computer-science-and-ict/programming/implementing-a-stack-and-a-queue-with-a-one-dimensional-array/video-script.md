# Video script — Implementing a Stack and a Queue with a One-Dimensional Array

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An array of fixed size holds the pile; a pointer — **top (κορυφή)** — remembers the place of the last value pushed. **Push**: check the stack is not full (top has not reached the size), move top up one, store the value there. **Pop**: check the stack is not empty (top is not 0), take the value at top, move top down one. Every fault this structure can have lives at its two edges — pushing onto a full stack (**overflow**) and popping an empty one (**underflow**) — so the checks are not decoration; they are half the implementation.
The queue needs **two** pointers: **front (εμπρός)** where values leave and **rear (πίσω)** where values join. Joining moves rear up and stores; leaving takes the value at front and moves front up — so the line **walks along the array** as it works, and the implementation must face the array's end honestly (the book's worked examples keep the line inside its fixed array and test full and empty by the pointers' positions). The unit works both structures through printed implementation examples step by step, pointer by pointer.
