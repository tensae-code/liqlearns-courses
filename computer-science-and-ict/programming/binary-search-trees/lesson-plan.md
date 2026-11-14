# Lesson plan — Binary Search Trees

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Binary Search Trees
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 12 Chuyên đề Tin học 12 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** binary search trees — a binary tree kept under one rule (smaller to the left, larger to the right of every node), so searching, inserting and deleting all walk one path (Vietnam Grade 12 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The rule — smaller left, larger right** — A **binary search tree** (cây tìm kiếm nhị phân) is a binary tree under one discipline: for **every node**, all values in its **left subtree are smaller** than the node's value, and all in its **right subtree are larger**. The rule turns the tree into a searching machine: to find a value, compare it with the root — smaller, go left; larger, go right; equal, found — discarding half the tree at each step, as binary search discards half a list, but in a structure that can also **grow**.
2. **Insert, delete, and the shape's warning** — **Inserting** walks the search path and attaches the new value as a leaf where the path runs out — the rule is never broken. **Deleting** is careful work: a leaf is simply removed; a node with one child is replaced by that child; a node with **two children** is replaced by a value from below (its successor) so the rule survives. The warning the book teaches: the tree's speed depends on its **shape** — insert sorted values and the 'tree' becomes a crooked line, no better than a list.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. At every node, the left subtree holds smaller values and the right subtree larger ones
2. Compare with the node: smaller goes left, larger goes right, equal is found
3. Half the remaining tree
4. Grow — new values are inserted into their place in the structure

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — binary search trees — a binary tree kept under one rule (smaller to the left, larger to the right of every node), so searching, inserting and deleting all walk one path (Vietnam Grade 12 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the rule — smaller left, larger right as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of insert, delete, and the shape's warning in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the rule — smaller left, larger right → the student studies the picture and names what each part shows
- GIF — a GIF of insert, delete, and the shape's warning in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
