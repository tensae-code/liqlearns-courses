# Lesson plan — Records in Pascal and C++

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Records in Pascal and C++
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The record type: values of different types gathered under field names into one datum — a pupil's name, marks and attendance — Pascal's record, C++'s struct, and field access by the dot (Moldova Grade 11, Informatică, §1.4).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Fields — different types under one datum** — A **record** is a structured type whose parts — its **fields** — may be of **different types**, each with its own **name**: Pascal's `type TPupil = record name: string; mark: integer; paid: boolean; end;`, C++'s `struct`. A field is reached through the record variable with a **dot**: `p.mark := 9;` — the dot reads 's: the mark of p. The whole record can also be **assigned at once** to another of the same type, copying every field — the structure acting simple for one act.
2. **Records at work — tables of honest data** — Records earn their keep where the world is tabular: a **class of pupils** is an array of records; a **library** is a file of them. The working patterns assemble the chapter's structures: loop the array, test a field, gather by another field — 'print the names of pupils with mark ≥ 9 and paid = true'. A record also models **one honest thing** — a date (day, month, year as three fields of fitting subranges), a point, a book — which is why the type definition reads like the thing's description: fields are the datum's anatomy, written down.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A structured type whose named fields may be of different types
2. Through the record variable with a dot — p.mark
3. type TPupil = record name: string; mark: integer; paid: boolean; end;
4. struct

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — An array gathers manyness of one kind; real data is manyness of many kinds. A pupil is a name (string), a mark (integer) and a fee paid (boolean) at once. Grade 11's answer is the record. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of fields — different types under one datum as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of records at work — tables of honest data in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of fields — different types under one datum → the student studies the picture and names what each part shows
- GIF — a GIF of records at work — tables of honest data in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
