# Lesson plan — Depth-First Search

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Depth-First Search
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 12 Chuyên đề Tin học 12 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** depth-first search — traversing a graph by plunging down one path as far as it goes, then backtracking and plunging down the next (Vietnam Grade 12 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Down one path to the end — then back** — **Depth-first search** (duyệt theo chiều sâu, DFS) explores a graph the way a determined walker explores a cave: from the start vertex, follow **one path as deep as it goes** — vertex to unvisited neighbour to the next — until no new vertex can be reached; then **backtrack** along the path to the last vertex with an untried edge, and plunge again. Every vertex is **marked visited** when first reached, so none is explored twice. Vietnam's specialist book pairs DFS with its breadth-first twin and drills both, because choosing between them is a working skill.
2. **The stack underneath — and when DFS is the right tool** — DFS's memory is a **stack** — the path's vertices are pushed as the search descends and popped as it retreats (recursion hides the same stack inside the calls). DFS is the right tool when the job is about **reachability and structure**: can this vertex be reached at all, is the graph connected, is there a cycle, can these tasks be ordered so each comes after its dependencies? Its weakness is the mirror of its strength: it may dive deep past a solution that lay near the start — that shallower hunt is breadth-first search's.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Follow one path as deep as it goes, then backtrack and plunge down the next
2. When the current path can reach no new vertex
3. The last vertex with an untried edge
4. So no vertex is explored twice

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — depth-first search — traversing a graph by plunging down one path as far as it goes, then backtracking and plunging down the next (Vietnam Grade 12 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of down one path to the end — then back as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the stack underneath — and when dfs is the right tool in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of down one path to the end — then back → the student studies the picture and names what each part shows
- GIF — a GIF of the stack underneath — and when dfs is the right tool in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
