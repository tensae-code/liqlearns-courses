# Video script — Encryption — the Caesar and Rail Fence Ciphers

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Encryption** turns readable data (**plaintext**) into unreadable form (**ciphertext**) by a method and, usually, a **key**; **decryption** reverses it for the key's holder. The classical methods divide by their working: **substitution** methods replace each letter by another (the Caesar's family), **transposition** methods keep the letters and rearrange their order (the Rail Fence's family). Every modern cipher is these two ideas industrialised — which is why Jordan teaches the ancestors by hand before the descendants by name.
The **Caesar cipher** shifts every letter by a fixed number (the key): with key 3, A→D, B→E — HELLO becomes KHOOR; decrypting shifts back. Its weakness is its tiny key space: 25 shifts to try. The **Rail Fence** writes the message in a zigzag across rails (rows) and reads it off row by row: the letters are all present, their order scrambled — a transposition. Worked together they teach the field's eternal pair: hide the letters' identities, or hide their order — and why real systems must hide both, against enemies who count letter frequencies and try every key by breakfast.
