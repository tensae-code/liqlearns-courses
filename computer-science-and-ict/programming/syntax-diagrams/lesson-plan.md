# Lesson plan — Syntax Diagrams

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Syntax Diagrams
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Syntax diagrams: the second formal picture of a language's grammar — boxes for terminals, ovals for nonterminals, and arrows whose path through the diagram is exactly the set of legal texts (Moldova Grade 10, Informatică, §1.3).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Reading a diagram — boxes, ovals and the path** — In a **syntax diagram**, each construction has its own named chart. **Terminal symbols** stand in **round-ended boxes** — they are written exactly as shown; **nonterminals** stand in **rectangular boxes** — they send you to their own charts. You read by **following the arrows**: whatever sequence of boxes a complete path collects, in order, is a legal form of the construction. Where arrows **branch**, the grammar offers a choice; where an arrow **loops back**, the part may repeat.
2. **Diagrams and BNF — the same grammar twice** — Diagrams and BNF describe **the same grammar** in two media: every production becomes a chart, every chart reads back into productions. Diagrams show **flow** better (a loop is seen at a glance); BNF is **shorter to write** and easier to print and search. The languages' manuals use both, so the course teaches both: the pupil who can translate a rule between the two truly owns it — as with Pascal and C++, the concept survives its clothing.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Terminal symbols — written exactly as shown
2. Nonterminals — constructions with their own charts
3. By following the arrows — a complete path collects a legal form
4. Branches are choices; a loop back means the part may repeat

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — BNF states the grammar in text; Grade 10's next section draws it. A syntax diagram is a map: enter at the arrow's start, leave at its end, and every route between is a sentence the language accepts. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of reading a diagram — boxes, ovals and the path as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of diagrams and bnf — the same grammar twice in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of reading a diagram — boxes, ovals and the path → the student studies the picture and names what each part shows
- GIF — a GIF of diagrams and bnf — the same grammar twice in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
