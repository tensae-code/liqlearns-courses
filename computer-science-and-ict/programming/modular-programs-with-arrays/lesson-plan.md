# Lesson plan — Modular Programs with Arrays

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Modular Programs with Arrays
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How a modular program is written around an array — subprograms that each do one job on the array (fill it, process it, print it), called from a main program (Malaysia, Tingkatan 4, Java)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **One job per subprogram** — A **modular program** divides its work among **subprograms**, each doing **one job** well. Around an array, the natural modules are the array's career: a **fill** module that reads values into the array, a **process** module that works on them (a total, an average, a highest), and a **print** module that presents them. Each module is written and tested **on its own**, with the array handed to it — a module that fills must not also average, because a fault then has two homes and a test cannot tell them apart.
2. **The main program conducts** — The **main program** shrinks to a conductor: declare the array, then **call** the modules **in order** — fill, process, print — passing the array (and its size) to each. Values a module works out for the conductor are **returned** or left in shared results as the design states. Malaysia's gain is the chapter's closing argument for modules: change how printing looks and only the print module is opened; test the averaging and only the process module is run. The array is the shared stage; the modules are the actors; the main program is the order of the play.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Subprograms — each doing one job well
2. Fill it, process it, print it — the array's career
3. On its own, with the array handed to it
4. A conductor — declare the array, call the modules in order

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A class's marks sit in an array; three jobs must be done on them: read them in, average them, print them. Malaysia's programming chapter finishes by building that program in modules. In this lesson you write one job per subprogram — and let the main program conduct. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one job per subprogram as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the main program conducts in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one job per subprogram → the student studies the picture and names what each part shows
- GIF — a GIF of the main program conducts in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
