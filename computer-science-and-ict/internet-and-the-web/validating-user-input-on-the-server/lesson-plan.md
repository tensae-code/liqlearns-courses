# Lesson plan — Validating User Input on the Server

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Validating User Input on the Server
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How data validation is done on the server — checking what users send (present, of the right kind, in range, in format) before it is stored or trusted (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What validation checks** — **Validation** (pengesahsahihan data) checks a sent value against its rules before the program uses or stores it. The standing checks are: **presence** — the field was not left empty; **type** — a number where a number is required; **range** — a mark between 0 and 100, an age a human could have; **format** — an email shaped like an email, a date that exists; and **length** — a password long enough, a name not absurdly long. Each failed check is reported **to the user, by field**, so the sending can be corrected — a bare 'invalid' teaches nothing and protects by luck.
2. **Why the server must check — even if the page already did** — Pages can check too (JavaScript validation, for comfort and speed), but the **server's check is the one that counts**: the page's code runs in the visitor's own browser, where it can be skipped, altered or bypassed entirely — a sender need never load your page at all. Data that reaches storage has passed the server or it has passed nothing. Malaysia's architecture is therefore **both**: the client checks for the user's sake, the server checks for the **data's** sake — and the stored text files of this unit hold only what the server's gate let through.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Checking a sent value against its rules before the program uses or stores it
2. Presence, type, range, format, length
3. Range — a mark must lie between 0 and 100
4. It teaches nothing and protects by luck

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Users send everything: blanks, letters in number fields, dates that do not exist. Malaysia's PHP unit checks the sending on the server before believing it. In this lesson you validate — the gate every value passes before it is stored. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of what validation checks as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of why the server must check — even if the page already did in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of what validation checks → the student studies the picture and names what each part shows
- GIF — a GIF of why the server must check — even if the page already did in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
