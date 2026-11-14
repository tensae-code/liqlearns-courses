# Video script — Memory Addressing — How Data Sits at Addresses

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Memory is not a heap but a street: a long row of storage places, each with a number — its **address** (pengalamatan memori). When a value is stored, it is placed **at an address**; when the processor needs it, the address is what it asks for. Indonesia's Grade 8 book introduces addressing inside the computer-system chapter because it explains the machine's most basic miracle — finding one exact value among billions — with a picture any pupil knows: the letter is found not by searching the city, but by the address written on it.
The addresses of the machine's own street are **physical addresses**: the real places in the memory hardware. Programs are written as if data simply has names — the variable's name in the program is the programmer's address for the same place — and the system joins name to physical address behind the scenes. Addressing also sets memory's measure: the number of addresses a processor can name limits how much memory it can use, which is why 'how much memory can this machine address?' is a real specification and not a slogan.
