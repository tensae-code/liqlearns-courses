# Lesson plan — Fuzzy Logic

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Fuzzy Logic
**Place in the curriculum:** ICT expansion — Laos (2026-11-14) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from Laos's student books (Ministry of Education / Research Institute of Educational Sciences), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Fuzzy logic — computing with degrees of truth instead of only true and false (Laos Grade 10, Ch.4 §6.5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **From true/false to degrees** — Ordinary (crisp) logic sorts every statement as **true or false**, every thing as in the set or out — a person of 179 cm is simply 'not tall' if tall begins at 180. **Fuzzy logic** replaces the hard edge with a **degree of membership**: a value between **0 and 1** saying how much a thing belongs — 179 cm is tall to degree 0.9, warm water is warm to degree 0.7. The computer can then reason the way people speak: *rather* hot, *quite* far, *almost* full — judgements the two-answer logic cannot even write down.
2. **Fuzzy logic at work — control that feels human** — Fuzzy logic's home is **control**: a fuzzy controller takes readings stated in degrees (the room is *rather* warm; the load is *quite* heavy) and rules stated as people state them (**if** the room is rather warm **then** cool it gently) and produces a **graded action** — the air conditioner's fan easing instead of snapping on and off, the washing machine choosing its wash by how dirty, the camera steadying its focus. Laos places Fuzzy Logic among the branches of AI — beside neural networks and intelligent agents — because it is intelligence of a particular kind: not learning, but **judgement in degrees**, the machine handling the world's vagueness without pretending it is precise.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in New Technologies on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Laos's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. True or false — in the set or out
2. A degree of membership between 0 and 1
3. The thing belongs to 'tall' almost fully, but not completely
4. Rather hot, quite far, almost full — judgements in degrees

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Is the water warm? Not yes, not no — warm-ish. Ordinary computer logic knows only two answers, but the world speaks in degrees. Laos's Grade 10 AI chapter gives the in-between logic its own branch: Fuzzy Logic. This lesson thinks in degrees. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of from true/false to degrees as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of fuzzy logic at work — control that feels human in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of from true/false to degrees → the student studies the picture and names what each part shows
- GIF — a GIF of fuzzy logic at work — control that feels human in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
