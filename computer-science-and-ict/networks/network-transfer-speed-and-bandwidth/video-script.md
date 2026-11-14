# Video script — Network Transfer Speed and Bandwidth

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Transfer speed** is how much data crosses a link in one second, counted in **bits per second (bps)** — with the ladder of thousands the book uses: **kbps, Mbps, Gbps**. The trap is the small b: file sizes are counted in **bytes**, and one byte is eight bits, so a 100 Mbps link moves at most 12.5 megabytes in a second, not 100. Time for a transfer is then plain division: **time = data size ÷ speed**, with both sides in the same unit. Every 'how long will this take?' question in networking is that one division, done honestly.
**Bandwidth** is the link's capacity — the widest flow it can carry — and it caps the speed, but the speed a user gets is usually less: the link is **shared** with other users, the path crosses several links and moves at the **slowest** of them, and distance, interference and the devices at each end all take their share. Egypt's book puts this calculation at the end of the networks chapter, after packets, addresses and protocols, because speed is where those ideas become a number a person can plan with — choosing a connection, judging a download, or explaining why the evening internet crawls.
