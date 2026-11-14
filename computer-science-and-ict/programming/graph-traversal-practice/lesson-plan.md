# Lesson plan — Graph Traversal Practice — Depth and Breadth Together

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Graph Traversal Practice — Depth and Breadth Together
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 12 Chuyên đề Tin học 12 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** graph traversal practice — running depth-first and breadth-first traversal over the same graph, comparing their orders, and choosing the traversal a problem needs (Vietnam Grade 12 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **One graph, two walks — the orders differ** — The specialist book closes its graph strand with a **synthesis practical**: take one graph and traverse it **both ways**. **Depth-first** dives along one path, so its order lists a deep chain first; **breadth-first** spreads ring by ring around the start, so its order lists the near vertices first. Same graph, same start — **two different visit orders**, both complete, both correct. The practical's first skill is mechanical honesty: run each walk with its own memory (stack for depth, queue for breadth) and never let the two orders blur.
2. **Choosing the walk — what the problem asks decides** — The comparison's point is choice. **Breadth-first** answers 'nearest' questions — its rings are distances, so the first time it reaches a vertex is by the **fewest edges**. **Depth-first** answers 'reachable and structured' questions — connectedness, cycles, orderings — and uses memory only along one path. The practical ends with mixed problems: for each, name the walk **before** running it, and give the reason in the problem's own words — the traversal is chosen by the question, never by habit.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Both traversals — depth-first and breadth-first
2. A deep chain first — one path followed to its end
3. Ring by ring — the near vertices first
4. A stack for depth-first; a queue for breadth-first

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — graph traversal practice — running depth-first and breadth-first traversal over the same graph, comparing their orders, and choosing the traversal a problem needs (Vietnam Grade 12 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one graph, two walks — the orders differ as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of choosing the walk — what the problem asks decides in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one graph, two walks — the orders differ → the student studies the picture and names what each part shows
- GIF — a GIF of choosing the walk — what the problem asks decides in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
