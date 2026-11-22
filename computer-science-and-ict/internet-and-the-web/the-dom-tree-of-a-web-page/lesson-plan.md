# Lesson plan — The DOM — the Tree of a Web Page

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** The DOM — the Tree of a Web Page
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** When a browser loads a page, it turns the HTML into a living tree of nodes — the Document Object Model: the document at the root, elements as branches, text as leaves — and programs, especially JavaScript, work on the page by walking this tree, finding nodes and changing them.
**This lesson's own level:** It stands on the HTML lesson: tags and elements, and how they nest. A learner who has written nested HTML can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The page as a tree of nodes** — The DOM defined: the document node at the root; element nodes for every tag; text nodes for the words; parent, child and sibling relations read straight off the nesting of the HTML — the tree is the HTML, seen as a structure instead of a text.
2. **Using the DOM — finding and changing nodes** — Why the tree exists: scripts find nodes (for example by their id), read or change their text and attributes, and the page on screen changes at once — this is the bridge between the HTML lesson and the JavaScript lesson.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Internet and the Web lesson on HTML tags and elements, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Le Web", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Draw the DOM tree of a small HTML fragment, with element and text nodes in the right places.
2. Use the words parent, child and sibling correctly about the nodes of a tree you drew.
3. Explain why the browser builds the DOM instead of keeping the page as plain text.
4. Say how a script finds one node by its id and what happens on screen when it changes that node.

## What you need
Paper and a pencil. A browser with its developer tools helps for the hands-on work but is not required.

## The run of the lesson (in order)
1. **Do it first** — Take a tiny nested HTML fragment and draw it as a family tree before the lesson names the model. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a small HTML fragment on the left and its DOM tree on the right, arrows joining each tag to its node — the student matches two more tags to their nodes without the arrows
   - ADD GIF: a GIF of a script changing one node's text while the rendered page beside the tree changes at the same moment — the student points at the node being changed before the page updates
   - ADD IMAGE: a picture of one highlighted node in a tree with its parent, children and siblings labelled in different colours — the student names the family relation of three nodes the teacher points at
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a small HTML fragment on the left and its DOM tree on the right, arrows joining each tag to its node → the student matches two more tags to their nodes without the arrows
- GIF — a GIF of a script changing one node's text while the rendered page beside the tree changes at the same moment → the student points at the node being changed before the page updates
- IMAGE — a picture of one highlighted node in a tree with its parent, children and siblings labelled in different colours → the student names the family relation of three nodes the teacher points at
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Draws the tree in the order of the text instead of by nesting → the tree is built by containment: ask "what is inside what?" for every pair. Forgets the text nodes → the words are nodes too, always the leaves; a tree without them has lost the page's content. Thinks JavaScript edits the HTML file → it edits the living tree; reloading the page rebuilds the tree from the file and the changes vanish.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France's SNT book teaches the DOM in the Cours of its Web theme, right after HTML and CSS — this lesson keeps that place, as the bridge to the JavaScript lesson.
