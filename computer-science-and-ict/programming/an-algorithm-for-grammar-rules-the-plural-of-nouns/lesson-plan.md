# Lesson plan — An Algorithm for Grammar Rules — The Plural of Nouns

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** An Algorithm for Grammar Rules — The Plural of Nouns
**Place in the curriculum:** ICT expansion — Switzerland (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Switzerland's Décodage teacher guides (DEF-DGEO, canton de Vaud, French; CC BY NC SA 4.0), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building. This lesson stands on teacher-guide evidence only (Switzerland), named in its sources, counted nowhere.
**The one thing this lesson teaches:** an algorithm for a grammar rule (trouver le pluriel des noms avec un algorithme): turning ‘how do French nouns make their plural?’ into rules a machine could follow — endings, exceptions and all (Switzerland Grade 7 Décodage, Enquête 1).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Rules with exceptions — the algorithmist's daily bread** — The inquiry asks for the plural **by algorithm**: start with the general rule (add -s), then branch on endings — nouns in **-al** mostly go to **-aux** (cheval → chevaux) with exceptions (bal → bals); **-eau, -eu, -au** take -x; seven famous families in -ou take -x too (bijou, caillou, chou, genou, hibou, joujou, pou) while their cousins take -s. The grammar lesson and the programming lesson are the same lesson: a rule, its cases, its exceptions — a decision structure wearing a French accent.
2. **Building the logigramme of a rule** — The inquiry builds the rule's synthesis tool — the **logigramme**: start with the word, test its ending diamond by diamond, exit with the plural. Building it forces completeness: every ending the class can find must have a path, and every exception its own labelled branch — a flowchart with a hole in it fails exactly the word that falls through. Grammar, drawn this way, stops being taste and becomes engineering: testable, completable, improvable.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Switzerland's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Add -s
2. -aux (cheval → chevaux)
3. Bal → bals
4. -eau, -eu, -au (and seven -ou families)

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Chat → chats. Cheval → chevaux. Bijou → bijoux. Your tongue knows the plurals; a machine knows nothing. Before reading on, write the rule for -al words as an order a robot could obey — and watch an exception walk in. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of rules with exceptions — the algorithmist's daily bread as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of building the logigramme of a rule in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of rules with exceptions — the algorithmist's daily bread → the student studies the picture and names what each part shows
- GIF — a GIF of building the logigramme of a rule in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
