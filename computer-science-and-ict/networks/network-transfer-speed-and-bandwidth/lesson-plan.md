# Lesson plan — Network Transfer Speed and Bandwidth

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Network Transfer Speed and Bandwidth
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Networks on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** How much data crosses a link in one second.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Bits per second — what the speed number counts** — **Transfer speed** is how much data crosses a link in one second, counted in **bits per second (bps)** — with the ladder of thousands the book uses: **kbps, Mbps, Gbps**. The trap is the small b: file sizes are counted in **bytes**, and one byte is eight bits, so a 100 Mbps link moves at most 12.5 megabytes in a second, not 100. Time for a transfer is then plain division: **time = data size ÷ speed**, with both sides in the same unit. Every 'how long will this take?' question in networking is that one division, done honestly.
2. **Bandwidth and the speed you actually get** — **Bandwidth** is the link's capacity — the widest flow it can carry — and it caps the speed, but the speed a user gets is usually less: the link is **shared** with other users, the path crosses several links and moves at the **slowest** of them, and distance, interference and the devices at each end all take their share. Egypt's book puts this calculation at the end of the networks chapter, after packets, addresses and protocols, because speed is where those ideas become a number a person can plan with — choosing a connection, judging a download, or explaining why the evening internet crawls.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Networks on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. How much data crosses a link in one second.
2. Bits per second (bps) — scaling to kbps, Mbps and Gbps.
3. The link's capacity — the widest flow it can carry.
4. The link is shared, and the path moves at its slowest link, with distance, interference and devices taking a share.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 10 networks chapter ends with a number every user has met and few can read: transfer speed, measured in bits per second. This lesson teaches what that number means, how it is built from bandwidth, and how to work out how long a transfer will really take. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of bits per second — what the speed number counts as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of bandwidth and the speed you actually get in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of bits per second — what the speed number counts → the student studies the picture and names what each part shows
- GIF — a GIF of bandwidth and the speed you actually get in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
