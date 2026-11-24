# Keeping a Message Secret — Packets, TCP and Encryption Keys

## Do it first

Your message now travels as packets through machines owned by strangers. Two fears arrive together: pieces getting lost, and pieces getting read. Before reading on, say which fear a checklist solves — and which one only a lock solves.

## Sub lesson 1 — TCP — the reliable carrier

**TCP (Transmission Control Protocol)** is the protocol that makes packet delivery **reliable**: it numbers the packets, the receiver acknowledges what arrived, missing pieces are sent again, and the message is reassembled complete and in order. Where IP is the addressing, TCP is the promise-keeping: a message sent under TCP either arrives whole or the sender knows it did not — nothing silently vanishes.

In your mind's eye: tCP — the reliable carrier.

## Sub lesson 2 — Encryption — the lock on the contents

Reliability is not secrecy: packets can arrive whole **and** be read on the way. **Encryption** locks the contents with a **key (clef)**: intercepted packets show only scrambled data. The séance's sharp question finishes the lesson — **what if the pirate catches the key?** Then the lock opens for them too: secrecy lives and dies with the key's own safety, which is why keys are guarded, changed, and never sent alongside the message they lock.

In your mind's eye: encryption — the lock on the contents.

## Say it to your companion

Tell your companion, in your own words: **TCP (Transmission Control Protocol)** is the protocol that makes packet delivery **reliable**: it numbers the packets, the receiver acknowledges what arrived, missing pieces are sent again, and the message is reassembled complete and in order. Where IP is the addressing, TCP is the promise-keeping: a message sent under TCP either arrives whole or the sender knows it did not — nothing silently vanishes. Reliability is not secrecy: packets can arrive whole **and** be read on the way. **Encryption** locks the contents with a **key (clef)**: intercepted packets show only scrambled data. The séance's sharp question finishes the lesson — **what if the pirate catches the key?** Then the lock opens for them too: secrecy lives and dies with the key's own safety, which is why keys are guarded, changed, and never sent alongside the message they lock. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Transmission Control Protocol. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The packets. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Acknowledgements of what arrived. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: They are sent again. Do this with a real example of your own and write or say how you know it is right.
