# Lesson plan — Sorting and Searching in JavaScript

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Sorting and Searching in JavaScript
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How sorting and searching are written in JavaScript — bubble sort, selection sort and binary search coded with loops and arrays on the client side (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Sorting in JavaScript — bubble and selection** — A JavaScript **sort** works on an **array** with nested loops. **Bubble sort** in code is the paper method written down: an outer loop for passes, an inner loop comparing array[j] with array[j+1], and a swap through a temporary variable (let t = a[j]; a[j] = a[j+1]; a[j+1] = t;). **Selection sort** searches each pass for the **smallest remaining** value and swaps it into place — the search-inside-sort weaving, in code. JavaScript also has a built-in sort method, but Malaysia codes the methods by hand first: the built-in is trusted only after its hand-written ancestors are understood.
2. **Searching in JavaScript — binary search coded** — **Binary search** in JavaScript tracks low, high and mid over the array's indexes, looping while low <= high, comparing array[mid] with the target and halving the field exactly as the pseudocode did. The code returns the **index** where the target was found, or −1 for not found — the convention JavaScript programs use. The lesson's point closes the strand: pseudocode, flowchart and JavaScript are three writings of one algorithm; Malaysia moves between them to prove the algorithm is the thinking, and the language only its clothing.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An array, with nested loops
2. Through a temporary variable — let t = a[j]; a[j] = a[j+1]; a[j+1] = t;
3. The smallest remaining value, to swap into place
4. low, high and mid over the array's indexes

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Malaysia's final-year web chapter carries the school algorithms into JavaScript: the same bubble, selection and binary ideas, now as code that runs in a page. In this lesson you write the three in JavaScript — and see that the algorithm outlives the language. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of sorting in javascript — bubble and selection as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of searching in javascript — binary search coded in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of sorting in javascript — bubble and selection → the student studies the picture and names what each part shows
- GIF — a GIF of searching in javascript — binary search coded in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
