# Lesson plan — Queues and Waiting Lines

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Queues and Waiting Lines
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Arrivals, the queue itself, and service.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The anatomy of a queue — arrivals, service, the line** — Every queue has the same three parts: **arrivals** (how often customers come, and how irregularly), the **queue** itself (the waiting line, usually **first in, first out**), and **service** (how many servers, and how long each service takes). The numbers that matter are **waiting time**, **queue length**, and how busy the servers stay. The trap is irregularity: even when arrivals average slower than service, a bunching of arrivals builds a line that takes long to clear — which is why the average alone, the lesson of the analysis chapters, never tells a queue's story.
2. **Simulating a queue — what changes, what breaks** — A **queue simulation** runs the model minute by minute — or arrival by arrival — varying what the manager can change: one more server, faster service, arrivals spread by appointments. The findings are famously unfair: as a system nears its capacity, waiting time does not grow gently but **explodes**, so a service running at 95% busy can hold queues many times longer than one at 80%. Egypt places queues inside the simulation chapter because this is simulation's home ground — a real queue cannot be experimented on without experimenting on real people, but its model can be run a hundred ways before a single desk is moved.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Arrivals, the queue itself, and service.
2. First in, first out.
3. It does not grow gently — it explodes.
4. The 95% system can hold queues many times longer.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 10 simulation chapter ends with the system everyone has stood in: the queue. Modelled honestly, a queue shows why a small change in arrivals or service can turn a short wait into a collapsing one — and why simulation, not guesswork, answers it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the anatomy of a queue — arrivals, service, the line as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of simulating a queue — what changes, what breaks in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the anatomy of a queue — arrivals, service, the line → the student studies the picture and names what each part shows
- GIF — a GIF of simulating a queue — what changes, what breaks in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
