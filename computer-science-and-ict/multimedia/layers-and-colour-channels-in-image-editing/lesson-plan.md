# Lesson plan — Layers and Colour Channels in Image Editing

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Layers and Colour Channels in Image Editing
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The two structures underneath raster editing: layers — transparent sheets stacked into one image — and colour channels — the image kept separately in its colour components, red, green and blue (Moldova Grade 8, Informatică, §4.7).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Layers — the stack of transparent sheets** — A digital image in an editor is a **stack of layers**: transparent sheets, each holding part of the picture — background on the bottom sheet, objects above, text near the top. The visible image is the stack **seen through**, top to bottom. Layers can be **shown or hidden, reordered, made partly transparent (opacity), edited or deleted** — each without harming the others. That separateness is the editor's safety: a mistake lives on one layer and dies with it, not with the whole picture.
2. **Colour channels — the image in its components** — A colour image is also kept **by channels**: in the RGB model, three **grayscale channels** hold how much **red, green and blue** each pixel carries, and the colour picture is their sum. Looking at one channel shows that colour's map of the image — the red channel is bright where the picture is reddish. Editors let you **view and even edit channels separately**, the road to fine colour correction and effects. Layers divide the image by **place**; channels divide it by **colour** — the two cuts every raster editor is built from.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Multimedia on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A transparent sheet holding part of the picture, in a stack
2. The stack seen through, top to bottom
3. Shown or hidden, reordered, made partly transparent (also: edited, deleted)
4. A layer's partial transparency — how much of what is below shows through

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Before Grade 8 opens GIMP, it teaches what GIMP is made of. Two ideas carry the whole of raster editing: the image is a stack, and its colour is a set of channels. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of layers — the stack of transparent sheets as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of colour channels — the image in its components in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of layers — the stack of transparent sheets → the student studies the picture and names what each part shows
- GIF — a GIF of colour channels — the image in its components in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
