# Lesson plan — PageRank — How Search Engines Rank Pages

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** PageRank — How Search Engines Rank Pages
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A search engine ranks a page by the links that point to it: a page is important when important pages link to it, and PageRank turns that idea into a number by imagining a surfer who follows links at random, forever — the score of a page is the share of time the surfer spends on it.
**This lesson's own level:** It stands on the Web as a set of pages joined by links, and on simple fractions and percentages from school mathematics. No programming is needed for the first part; the second part can be done on paper or in a spreadsheet.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The link graph and the score a page passes on** — The Web drawn as a graph: pages are nodes, links are arrows. A page receives importance from every page that links to it — but a page splits what it passes on among all its outgoing links, and a link from an important page counts for more than a link from an unknown one.
2. **The random surfer and working PageRank out by iteration** — The random surfer model: a surfer who clicks links at random, and sometimes jumps to a random page. Running the model round after round — each page's new score is what the others pass to it — the scores settle to the PageRank values; this is how the book approximates them in a spreadsheet and in a simulator.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Internet and the Web lesson on browsers and search engines, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Le Web", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Draw a small set of pages as a link graph and say which page each link votes for.
2. Explain why a page splits what it passes on among all its outgoing links.
3. Run two or three PageRank rounds on a small graph and say when the scores have settled.
4. Explain the random surfer model and what a page's PageRank number means.

## What you need
Paper, a pencil, and a calculator. A spreadsheet helps for the iteration part but is not required.

## The run of the lesson (in order)
1. **Do it first** — Draw four pages joined by arrows for their links and guess which page a search engine would call the most important — before the lesson gives the rule. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of four pages as circles with arrows for links, thick and thin according to the share of importance carried — the student traces each arrow and says which page gains importance from it
   - ADD GIF: a GIF of a dot wandering a small link graph at random, with a counter under each page growing as the dot visits — the student predicts which counter will grow fastest, then watches to check
   - ADD IMAGE: a picture of a spreadsheet table whose score columns change over five rounds and then stay still — the student carries out the next round by hand and checks it matches the settled column
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of four pages as circles with arrows for links, thick and thin according to the share of importance carried → the student traces each arrow and says which page gains importance from it
- GIF — a GIF of a dot wandering a small link graph at random, with a counter under each page growing as the dot visits → the student predicts which counter will grow fastest, then watches to check
- IMAGE — a picture of a spreadsheet table whose score columns change over five rounds and then stay still → the student carries out the next round by hand and checks it matches the settled column
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Adds a page's whole score to every page it links to → the score is split among the outgoing links; nothing is created, the total stays 1. Expects the scores to settle in one round → they settle gradually; run rounds until a round changes nothing that matters. Thinks D's link makes C strong by itself → D passes on only what D has, and D receives nothing, so its vote fades round by round.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France's SNT book teaches PageRank in the Activités of its Web theme — by hand, in a spreadsheet (Calc) and in a simulator, including the 2010 "reasonable surfer" refinement; this lesson follows that order.
