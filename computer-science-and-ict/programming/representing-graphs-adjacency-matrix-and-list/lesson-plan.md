# Lesson plan — Representing Graphs — Adjacency Matrix and List

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Representing Graphs — Adjacency Matrix and List
**Place in the curriculum:** ICT expansion — Vietnam (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Vietnam's Tin học books (Vietnam Grade 12 Chuyên đề Tin học 12 Khoa học máy tính), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** representing graphs in a program — the adjacency matrix (a table of 1s and 0s) and the adjacency list (each vertex with its neighbours), and what each costs and buys (Vietnam Grade 12 specialist, CS).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The matrix — the graph as a table** — The **adjacency matrix** (ma trận kề) stores a graph of n vertices as an **n × n table**: the cell in row u, column v holds **1 if an edge joins u and v**, else 0. It answers 'are these two joined?' in one look, and a vertex's neighbours are its row's 1s. Its cost is fixed: **n² cells** whether the graph has many edges or few — a graph of a thousand vertices and a thousand edges still pays a million cells. Vietnam's specialist book sets this cost beside the list's, because representation is a choice with a price.
2. **The list — each vertex with its neighbours** — The **adjacency list** (danh sách kề) stores, for each vertex, a **list of its neighbours** — nothing more. Its cost follows the edges: memory about **n + 2E** entries for an undirected graph, so **sparse** graphs (few edges) are held cheaply, where the matrix would be mostly zeros. Its weakness is the matrix's strength: 'are u and v joined?' must **search u's list**, and listing all edges means walking every list. The practical's rule: many edges or edge-questions — matrix; few edges or neighbour-walks — list.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Vietnam's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. An n × n table — 1 where an edge joins the row and column vertices, else 0
2. One look — a single cell
3. They are the 1s in its row
4. n² cells, however few edges the graph has

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — representing graphs in a program — the adjacency matrix (a table of 1s and 0s) and the adjacency list (each vertex with its neighbours), and what each costs and buys (Vietnam Grade 12 specialist, CS) (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the matrix — the graph as a table as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the list — each vertex with its neighbours in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the matrix — the graph as a table → the student studies the picture and names what each part shows
- GIF — a GIF of the list — each vertex with its neighbours in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
