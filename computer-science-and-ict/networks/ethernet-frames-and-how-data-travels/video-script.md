# Video script — Ethernet Frames and How Data Travels

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Data on a local network travels in an envelope. The envelope is called an Ethernet frame.

First comes a short signal: get ready, a frame is starting.

Then the address of the machine that must receive it. That is a MAC address.

Then the address of the machine that sent it. So the receiver knows who to answer.

Then a small code that says what is inside. Often: an IP packet.

Then the data itself. The parcel.

At the end, a check number. The receiver calculates it again. If it is different, the frame is damaged, and it is thrown away.

With a tool like Wireshark, you can catch a real frame and read every part of it yourself.
