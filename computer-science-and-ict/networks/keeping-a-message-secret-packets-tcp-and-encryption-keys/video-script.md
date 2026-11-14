# Video script — Keeping a Message Secret — Packets, TCP and Encryption Keys

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**TCP (Transmission Control Protocol)** is the protocol that makes packet delivery **reliable**: it numbers the packets, the receiver acknowledges what arrived, missing pieces are sent again, and the message is reassembled complete and in order. Where IP is the addressing, TCP is the promise-keeping: a message sent under TCP either arrives whole or the sender knows it did not — nothing silently vanishes.
Reliability is not secrecy: packets can arrive whole **and** be read on the way. **Encryption** locks the contents with a **key (clef)**: intercepted packets show only scrambled data. The séance's sharp question finishes the lesson — **what if the pirate catches the key?** Then the lock opens for them too: secrecy lives and dies with the key's own safety, which is why keys are guarded, changed, and never sent alongside the message they lock.
