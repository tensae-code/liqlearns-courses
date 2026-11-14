# Lesson plan — Video Digitisation and Compression

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Video Digitisation and Compression
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A fast sequence of still images — frames — shown quickly enough that the eye reads movement.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Video as numbers — frames, rate and size** — A **video** is a fast sequence of still images — **frames** — shown quickly enough that the eye reads movement. Digitising video therefore multiplies the image problem by time: each frame is digitised like a photograph (pixels, colour depth), and the **frame rate** — frames per second — decides how many of them a second of video holds. The arithmetic is sobering: resolution × colour depth × frame rate gives a raw data rate so large that a minute of uncompressed video would swallow a school computer's storage. That size is not a detail; it is the reason the second half of this lesson exists.
2. **Compression — keeping the meaning, dropping the weight** — **Compression** shrinks video by removing what the viewer will not miss. Inside one frame it squeezes like image compression; between frames it does the video-only trick — most of a frame is the **same as the frame before**, so the file stores the **changes** instead of the whole picture again. **Lossy** compression goes further, discarding fine detail the eye forgives, which is why a streamed match looks softer than the original recording. Egypt's book places video last in its digitisation run — sound, images, then video with compression — because each step reuses the last: samples, pixels, frames, and then the judgement of what may safely be thrown away.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Multimedia on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A fast sequence of still images — frames — shown quickly enough that the eye reads movement.
2. Like a photograph — pixels with colour depth.
3. What the viewer will not miss.
4. Store the changes — most of a frame is the same as the frame before.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Sound becomes numbers sample by sample, and images pixel by pixel — Egypt's Grade 10 book completes the set with moving pictures: how video is represented digitally, and why compression is not an extra but the thing that makes digital video possible at all. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of video as numbers — frames, rate and size as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of compression — keeping the meaning, dropping the weight in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of video as numbers — frames, rate and size → the student studies the picture and names what each part shows
- GIF — a GIF of compression — keeping the meaning, dropping the weight in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
