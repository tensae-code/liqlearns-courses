# Lesson plan — Building a User Interface

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Building a User Interface
**Place in the curriculum:** ICT expansion — Mongolia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Mongolia's student books (Ministry of Education, Culture and Science(s) of Mongolia, Ulaanbaatar), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Designing the user interface in Small Basic — the road from the TextWindow console to a graphical interface: the Controls object (AddButton, AddTextBox, AddMultiLineTextBox), events and event handlers, crowned by a quadratic-equation solver built as a windowed program
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The Controls object — buttons and boxes** — A **graphical interface** is built from **controls** — the window's working furniture — placed by the **Controls object**. **AddButton** puts a labelled button the user can click; **AddTextBox** takes a line of typed input; **AddMultiLineTextBox** takes whole paragraphs. Each control is placed by coordinates, sized, and filled with its text — the GraphicsWindow's grid, furnished. The program's centre of gravity moves: in the console the program asked the questions; in the window the user chooses what happens, and the program must be ready for every choice at once.
2. **Events and handlers — the program that waits** — A windowed program runs on **events**: the user's acts — a click, a key — arrive in no promised order, and each event is met by its **event handler**, the subprogram written for that event alone. The book's crown builds the whole doctrine into one artefact: a **quadratic-equation solver as a windowed program** — coefficients in text boxes, the solving behind a button, the answer appearing in the window. Mongolia's contrast is the chapter's lesson: the console program is a road; the windowed program is a room with staff — and designing the interface means deciding what the room offers and training the staff, handler by handler.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Mongolia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Controls — the window's working furniture
2. The Controls object
3. AddButton, AddTextBox and AddMultiLineTextBox
4. By coordinates, sized, and filled with its text

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Every Small Basic program so far spoke through the console. Mongolia's Grade 12 chapter gives programs a face: buttons and boxes in a window, and the new way of working — the program that waits for its user — that a face demands. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the controls object — buttons and boxes as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of events and handlers — the program that waits in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the controls object — buttons and boxes → the student studies the picture and names what each part shows
- GIF — a GIF of events and handlers — the program that waits in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
