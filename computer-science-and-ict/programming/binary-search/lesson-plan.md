# Lesson plan — Binary Search

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Binary Search
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How binary search works — halving the field each time by checking the middle, on a list that must already be in order, in pseudocode and flowchart (Malaysia, Tingkatan 3)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Halving the field** — **Binary search** works only on an **ordered list**. Check the **middle** item: if it is the target, the hunt ends. If the target is **smaller**, it can only live in the **left half** — the right half is discarded whole. If **larger**, the left half is discarded. The surviving half is searched the same way — new middle, new halving — until the target is found or the field shrinks to **nothing**, which answers 'not found'. Each check halves the field: 1,000 items need at most about 10 checks, against linear search's 1,000.
2. **Binary search in pseudocode and flowchart** — The pseudocode tracks **low** and **high** — the ends of the surviving field — and repeats while low ≤ high: middle = (low + high) ÷ 2 (whole number); if the middle item is the target, report it and stop; if the target is smaller, set high = middle − 1; else set low = middle + 1. The flowchart's shape is a loop with a **three-way decision** at its heart. Malaysia's warning is drawn with it: run binary search on an **unordered** list and it will throw away the half that holds the target — the method's speed is bought entirely by the order it demands.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. It must already be in order
2. The middle item
3. The right half — whole
4. low and high — the ends of the surviving field

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Search a sorted list of a thousand names by checking the middle one first, and the hunt collapses: each check throws half the list away. Malaysia's second search is binary search. In this lesson you work it — and respect its one demand: the list must be in order. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of halving the field as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of binary search in pseudocode and flowchart in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of halving the field → the student studies the picture and names what each part shows
- GIF — a GIF of binary search in pseudocode and flowchart in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
