# Implementing a Stack and a Queue with a One-Dimensional Array

## Do it first

The theory lesson named the stack and the queue. Greece's supplementary volume makes you build them — on the humblest structure there is, a one-dimensional array, with pointers doing the piling and the lining up.

## Sub lesson 1 — The stack on an array — one pointer on top

An array of fixed size holds the pile; a pointer — **top (κορυφή)** — remembers the place of the last value pushed. **Push**: check the stack is not full (top has not reached the size), move top up one, store the value there. **Pop**: check the stack is not empty (top is not 0), take the value at top, move top down one. Every fault this structure can have lives at its two edges — pushing onto a full stack (**overflow**) and popping an empty one (**underflow**) — so the checks are not decoration; they are half the implementation.

In your mind's eye: the stack on an array — one pointer on top.

## Sub lesson 2 — The queue on an array — two pointers, front and rear

The queue needs **two** pointers: **front (εμπρός)** where values leave and **rear (πίσω)** where values join. Joining moves rear up and stores; leaving takes the value at front and moves front up — so the line **walks along the array** as it works, and the implementation must face the array's end honestly (the book's worked examples keep the line inside its fixed array and test full and empty by the pointers' positions). The unit works both structures through printed implementation examples step by step, pointer by pointer.

In your mind's eye: the queue on an array — two pointers, front and rear.

## Say it to your companion

Tell your companion, in your own words: An array of fixed size holds the pile; a pointer — **top (κορυφή)** — remembers the place of the last value pushed. **Push**: check the stack is not full (top has not reached the size), move top up one, store the value there. **Pop**: check the stack is not empty (top is not 0), take the value at top, move top down one. Every fault this structure can have lives at its two edges — pushing onto a full stack (**overflow**) and popping an empty one (**underflow**) — so the checks are not decoration; they are half the implementation. The queue needs **two** pointers: **front (εμπρός)** where values leave and **rear (πίσω)** where values join. Joining moves rear up and stores; leaving takes the value at front and moves front up — so the line **walks along the array** as it works, and the implementation must face the array's end honestly (the book's worked examples keep the line inside its fixed array and test full and empty by the pointers' positions). The unit works both structures through printed implementation examples step by step, pointer by pointer. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A one-dimensional array of fixed size. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The place of the last value pushed. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Check not full, move top up one, store the value there. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Check not empty, take the value at top, move top down one. Do this with a real example of your own and write or say how you know it is right.
