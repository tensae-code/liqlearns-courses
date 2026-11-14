# Video script — Storage Architectures

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The simplest architecture keeps storage **attached to the machine that uses it** — fast and private, but stranded when others need the same data. **Network-attached storage** puts the shelves **on the network as a named place** any authorised machine may reach, so the organisation's files live **once, together**, instead of in copies scattered per desk. The architecture question is already a sharing question: who must reach this data, and what breaks when two copies disagree?
At the largest scale, storage becomes **its own dedicated network** behind the servers — a **storage area network** — so many servers share pools of storage at machine-room speed, and the pools can grow without the servers stopping. The chapter's judgement is by need: attached for the lone machine's speed, network-attached for the office's sharing, a storage network for the institution whose data is its life. Architecture is the database lessons' ground floor: the DBMS of the next sections stands on one of these arrangements, whether the learner names it or not.
