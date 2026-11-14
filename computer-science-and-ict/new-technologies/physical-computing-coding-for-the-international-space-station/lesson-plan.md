# Lesson plan — Physical Computing — Coding for the International Space Station

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Physical Computing — Coding for the International Space Station
**Place in the curriculum:** ICT expansion — Greece (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Greece's student books (ΙΤΥΕ «Διόφαντος» / ΙΕΠ, Ministry of Education), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Writing code that runs off Earth: handling the Space Station computer's sensors and drawing on its 8×8 LED matrix (Greece Grade 9, Pliroforiki C' Gymnasiou Unit 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Handling sensors — reading the station's senses** — The station's computer (the **Astro Pi**, with its Sense HAT) feels its world through **sensors** the program must **handle**: temperature, humidity, pressure, movement and orientation, light and colour. Handling a sensor means the program's standing pattern — **read the value, decide by it, act on it** — run against readings that arrive from a real, moving, orbiting room, with experiments the book designs around them (what is the station's air like, right now, above our heads?).
2. **Creating images on the 8×8 LED matrix** — The station computer's face is an **8×8 LED matrix** — sixty-four lights in an 8-by-8 grid — and the unit's creative half is **creating images on it**: setting **pixels by their coordinates and colours**, building pictures, letters, icons and small animations light by light. Its discipline is the grid's smallness: with 64 lights, every pixel is a decision — the same economy the Scratch stage taught at the other end of the sky, now practised for an audience of astronauts.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Greece's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The Astro Pi, with its Sense HAT of sensors
2. Temperature, humidity, pressure, movement/orientation, light/colour (any three)
3. Read the value, decide by it, act on it
4. A real, moving, orbiting room

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 9's boldest unit hands its learners a computer that is not in the classroom at all: the Astro Pi on the International Space Station. The code is the same Python — the hardware is in orbit. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of handling sensors — reading the station's senses as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of creating images on the 8×8 led matrix in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of handling sensors — reading the station's senses → the student studies the picture and names what each part shows
- GIF — a GIF of creating images on the 8×8 led matrix in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
