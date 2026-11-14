# Lesson plan — Converting Octal to Binary

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Converting Octal to Binary
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How to convert an octal number to binary by writing each octal digit as exactly three binary digits
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Each octal digit — three bits** — An octal digit runs from 0 to 7, and three binary digits also run from 000 to 111 — the same eight values. So **each octal digit converts on its own** into **exactly three binary digits**: 0→000, 1→001, 2→010, 3→011, 4→100, 5→101, 6→110, 7→111. The three-digit group is never shortened — a group of 001 keeps its leading zeros, because the zeros hold the places of the digits beside it.
2. **Groups side by side — the binary answer** — Convert **every** digit of the octal number and write the groups **side by side, in the same order**: 47₈ → 4→100, 7→111 → **100111₂**. Nothing is added and nothing is carried — the work is finished when every digit has its group. Check by value if unsure: 100111₂ = 32+4+2+1 = 39, and 47₈ = 39. Malaysia teaches this direct road because octal exists in computing precisely as binary's short writing.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Exactly three
2. Three bits make the same eight values, 000 to 111, as one octal digit, 0 to 7
3. 101
4. 100111₂ — 4→100, 7→111

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Octal and binary are close relatives: every octal digit is worth exactly three bits. Malaysia's Grade 8 book uses that kinship to convert without passing through decimal. In this lesson you turn each octal digit into its three-bit group. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of each octal digit — three bits as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of groups side by side — the binary answer in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of each octal digit — three bits → the student studies the picture and names what each part shows
- GIF — a GIF of groups side by side — the binary answer in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
