# Lesson plan — Combining Search and Sort

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Combining Search and Sort
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How search and sort are combined in one algorithm — sort the list, then search it — and when the combination beats searching alone (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Sort first, then search** — The combined algorithm runs in **two stages**: a **sort stage** (any correct sort — bubble or bucket by the data) puts the list in order, then a **search stage** — **binary search** — works the ordered list, halving to the target. The stages are joined by the sort's guarantee: binary search's one demand (order) is exactly what the first stage supplies. In pseudocode the combination is simply the two algorithms written one after the other, the sorted list handed from the first to the second.
2. **When the combination pays** — Sorting is **work done once**; searching is work done **per question**. The combination pays when **many searches** follow — the sort's cost is shared across all of them, and each search then costs halving-work instead of whole-list work. For a **single** search, the combination usually loses: sorting a whole list to answer one question costs more than one linear search. Malaysia's judgement rule: count the questions first — one question, search the list as it stands; a season of questions, sort once and halve every time.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Sort the list, then binary-search it
2. The sort's guarantee — binary search demands order, and the sort supplies it
3. Binary search — the ordered list is what it needs
4. When many searches follow one sort

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The chapter's methods are stronger together than apart. Malaysia combines them: sort first, then search the ordered list with binary search. In this lesson you build that combination — and judge when its extra work pays. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of sort first, then search as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of when the combination pays in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of sort first, then search → the student studies the picture and names what each part shows
- GIF — a GIF of when the combination pays in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
