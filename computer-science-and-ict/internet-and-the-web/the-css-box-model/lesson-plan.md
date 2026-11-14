# Lesson plan — The CSS Box Model

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** The CSS Box Model
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 12 Tin học 12 Tin học ứng dụng, Vietnam Grade 12 Tin học 12 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** the CSS box model — every element is a box of content wrapped in padding, a border and a margin, and its true size is the sum of the layers (Vietnam Grade 12).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Four layers — content, padding, border, margin** — CSS treats **every element as a box** of four layers. At the centre, the **content** — the text or image, sized by width and height. Around it, **padding** — clear space inside the box, between content and edge. Around that, the **border** — the box's visible line, with its width, style and colour. Outside everything, the **margin** — clear space between this box and its neighbours. Vietnam's Grade 12 book teaches the model as a picture first, because every layout surprise later is one of these layers being forgotten.
2. **True size — the sum of the layers** — The model's hard lesson is arithmetic: an element's **true width** is width + left and right padding + left and right border + left and right margin. Two boxes that 'should' fit side by side overflow when their paddings and borders are forgotten. The working habits: set padding and border **deliberately**, expect margins between neighbours to sit **between** the boxes (adjoining vertical margins even collapse into one), and when a layout breaks, **draw the boxes** — the picture finds the forgotten layer.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Content, padding, border, margin
2. Inside the box — clear space between the content and the edge
3. Its width, its style and its colour
4. Outside the box — clear space between this box and its neighbours

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — the CSS box model — every element is a box of content wrapped in padding, a border and a margin, and its true size is the sum of the layers (Vietnam Grade 12) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of four layers — content, padding, border, margin as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of true size — the sum of the layers in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of four layers — content, padding, border, margin → the student studies the picture and names what each part shows
- GIF — a GIF of true size — the sum of the layers in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
