# Lesson plan — Pulse Generators — and the Clock Signal

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Pulse Generators — and the Clock Signal
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Pulse generators: the circuits that produce the machine's heartbeat — a steady train of rectangular pulses whose frequency sets the pace of every sequential circuit, counted in hertz (Moldova Grade 11, Informatică, §5.7).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Pulses — the rectangular heartbeat** — A **pulse** is a signal that jumps between two levels — low and high — staying a measured time at each: drawn, it is a **rectangle**, not a wave. A **pulse generator** (clock generator) produces an endless, even train of them: the **clock signal**. Its measure is **frequency** — pulses per second, in **hertz (Hz)**, and its inverse, the **period** — the seconds one full pulse cycle takes. A 1 MHz clock beats a million times per second; a gigahertz clock, a billion.
2. **Why the machine needs a conductor** — Sequential circuits — flip-flops, registers, counters — change state **at the clock's edge**, all together: the clock is the conductor whose beat makes a million separate circuits one **synchronous** machine. Without it, signals would arrive at their own speeds and memory would smear. The clock's frequency therefore **rates the whole computer**: operations per second track it, which is why processors advertise it. Grade 11's next chapter — architecture — assembles its computer on this beat.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A signal jumping between two levels — drawn as a rectangle
2. An endless, even train of pulses — the clock signal
3. By frequency — pulses per second, in hertz; and by its period, the seconds per cycle
4. A million pulses per second

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every remembering circuit met so far moves on a signal nobody yet introduced: the pulse that says 'now'. Grade 11's circuits chapter ends with the heartbeat's maker. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of pulses — the rectangular heartbeat as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of why the machine needs a conductor in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of pulses — the rectangular heartbeat → the student studies the picture and names what each part shows
- GIF — a GIF of why the machine needs a conductor in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
