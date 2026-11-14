# Lesson plan — Data Compression — Making Files Smaller

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Data Compression — Making Files Smaller
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Data compression rewrites data in a shorter form by removing repetition: lossless compression restores the original exactly (right for text and programs), while lossy compression throws away detail the eye or ear barely misses (right for photos and music) and shrinks files far more — choosing between them is choosing what may be lost.
**This lesson's own level:** It stands on the digitisation and encoding lessons: compression is what you do to encoded data once you see how much repetition it carries. No new mathematics is needed — only pattern-spotting.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Why files can shrink — repetition and lossless compression** — Real data is full of **repetition**: a photo's sky is the same blue for ten thousand pixels in a row; a text repeats its common words and letters; a sound holds one note. Compression stores the pattern once with a note of how many times it runs, instead of storing every copy. **Lossless** compression uses only tricks like this — it removes repetition but loses nothing: decompressing gives back the original **bit for bit**. That exactness is compulsory where every bit matters — a program, a document, a set of results — which is why archive formats such as ZIP are lossless.
2. **Lossy compression — throwing away what barely matters** — **Lossy** compression goes further: it permanently discards detail the senses hardly notice — very slight colour differences between neighbouring pixels in a photo, sounds at the edge of hearing inside loud music. The decompressed file is *not* the original; it is a close neighbour of it. The reward is size: photos and music shrink to a small fraction of their lossless size, which is why the formats people share every day — JPEG photos, MP3 music — are lossy. The rule for choosing: if every bit must survive (text, programs, data), compress losslessly; if the file is for eyes and ears and small losses pass unnoticed, lossy buys the small size. Never lossy-compress the only copy of something precious — what is thrown away cannot be brought back.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Explain why real files can be compressed: they carry repetition.
2. Say what lossless compression guarantees, and name work it suits (text, programs, data; ZIP).
3. Say what lossy compression discards, what it suits (photos, music; JPEG, MP3), and why it cannot be undone.
4. Choose the right kind of compression for a given file and defend the choice.

## What you need
Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — Write the word 'ha' one hundred times on paper. Now write 'ha × 100'. Both say the same thing — one takes two lines, the other takes a breath. Files are full of the first kind of writing. This lesson is the art of finding it and rewriting it the second way — and of knowing when you may throw a little away on purpose. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a long ribbon printed with the same blue square a hundred times being folded into one square with a tag reading '×100' — the student says what was thrown away in the folding (answer: nothing — the count keeps it all).
   - ADD GIF: a GIF of a photograph being lossy-compressed step by step — the file size falling at each step while the picture stays the same to the eye, until the last step pushes too far and blocks appear — the student watches once and points at the step where the trade stopped being worth it.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a long ribbon printed with the same blue square a hundred times being folded into one square with a tag reading '×100' → the student says what was thrown away in the folding (answer: nothing — the count keeps it all)
- GIF — a GIF of a photograph being lossy-compressed step by step — the file size falling at each step while the picture stays the same to the eye, until the last step pushes too far and blocks appear → the student watches once and points at the step where the trade stopped being worth it
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks compression deletes part of the file at random → lossless deletes nothing; it rewrites repetition shorter and restores the original exactly. Lossy deletes deliberately — detail chosen because the senses barely miss it. Thinks lossy is always better because smaller → smaller is bought with permanent loss; for a program or a data file, one lost bit can ruin the whole file.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
