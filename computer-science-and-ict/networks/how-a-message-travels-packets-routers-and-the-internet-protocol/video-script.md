# Video script — How a Message Travels — Packets, Routers and the Internet Protocol

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

At Level 2, the home-network study opens the envelope: a message is **cut into packets (paquets)** — small addressed pieces. Each packet carries its destination's **IP address** and follows the **Internet Protocol (protocole Internet)**: the shared rules for addressing and forwarding. **Routers (routeurs)** read each packet's address and forward it toward its destination, hop by hop — packets of one message may take different roads and arrive out of order.
Arrival is a rebuild: the receiving machine collects the packets, puts them back in order, checks what is missing, and only then holds the message. This is why networks survive broken roads — a lost packet is one piece to resend, not a message to restart — and why the protocol, agreed by everyone, matters more than any single machine: the roads are many, the rules are one.
