# Lesson plan — Boolean Laws and De Morgan's Theorems

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Boolean Laws and De Morgan's Theorems
**Place in the curriculum:** ICT expansion — Montenegro (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Montenegro's *Digitalna Elektronika*, because no existing lesson covers this thing as its own lesson.
**The one thing this lesson teaches:** Boolean expressions can be rewritten without changing their truth table, using the algebra's laws — commutative, associative, distributive, identity, null, complement, idempotent and absorption laws — and De Morgan's two theorems, which turn a negated OR into an AND of negations and a negated AND into an OR of negations.
**This lesson's own level:** It stands directly on the Boolean operations lesson before it in Montenegro's climb — NOT, AND, OR, XOR and truth tables must already be in the learner's hand, because every law here is proved by a truth table.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The laws of Boolean algebra** — The identities that hold for every value of the variables: commutative (A+B = B+A, A·B = B·A), associative, distributive (A·(B+C) = A·B + A·C, and the second form A + B·C = (A+B)·(A+C)), identity (A+0 = A, A·1 = A), null (A+1 = 1, A·0 = 0), complement (A + Ā = 1, A · Ā = 0), idempotent (A + A = A, A · A = A) and absorption (A + A·B = A). Each law is proved by building both sides' truth tables.
2. **De Morgan's theorems — and simplifying with all the laws together** — De Morgan's first theorem: the negation of an OR is the AND of the negations — (A + B) with a bar over it = Ā · B̄. Second theorem: the negation of an AND is the OR of the negations — bar over (A · B) = Ā + B̄. The memory picture: break the bar, change the operation. Both theorems proved by truth table, then used with the other laws to simplify expressions like the bar over (A · B̄ + C).

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Boolean Algebra and Logic Operations, the lesson before this one in Montenegro's order. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Montenegro's own way is kept: this book reaches computing from the electronics side, so the lesson teaches the binary logic a computer is built from, with circuit-simulation work (TINA, Circuit Wizard) named alongside the theory, as the book's own practicum does.

## What the learner can do when it ends
1. State the commutative, associative, distributive, identity, null, complement, idempotent and absorption laws.
2. Prove a law by building the truth tables of both sides and showing the columns match.
3. State De Morgan's two theorems and apply 'break the bar, change the operation' step by step.
4. Simplify a short Boolean expression using the laws, naming each law used, and verify the result with a truth table.

## What you need
Paper and a pencil — each law is checked with a truth table before it is believed.

## The run of the lesson (in order)
1. **Do it first** — Take the expression A + A·B. It looks like it needs both an AND and an OR to build. But its truth table turns out to be just A's table — the whole second term does nothing. Somebody first had to prove that, so builders could throw the extra part away. This lesson teaches the laws that let you rewrite expressions smaller — and prove the rewrite is safe. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the laws as a toolbox chart — each law's pair of expressions with its one-line saying underneath — the student points at a law and gives an example of it with letters of their own before reading the saying.
   - ADD IMAGE: a picture of a long bar over a bracket breaking into short bars over each letter, the operation inside flipping from + to · — the student draws the same break-the-bar picture for the bar over (A · B) without looking.
   - ADD GIF: a GIF of an expression being simplified in steps — a term greyed out by absorption, a bar breaking by De Morgan — each step labelled with the law used — the student watches, then simplifies the same expression on paper, naming the law at each step aloud.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the laws as a toolbox chart — each law's pair of expressions with its one-line saying underneath → the student points at a law and gives an example of it with letters of their own before reading the saying.
- IMAGE — a picture of a long bar over a bracket breaking into short bars over each letter, the operation inside flipping from + to · → the student draws the same break-the-bar picture for the bar over (A · B) without looking.
- GIF — a GIF of an expression being simplified in steps — a term greyed out by absorption, a bar breaking by De Morgan — each step labelled with the law used → the student watches, then simplifies the same expression on paper, naming the law at each step aloud.
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Applies school-algebra habits without checking → this algebra has an extra distributive law (OR over AND) that school algebra lacks, and no subtraction or division at all; when unsure, the truth table is the judge. Pushes a De Morgan bar through but forgets to change the operation → say the picture aloud: break the bar, change the operation — both halves, every time. Simplifies and trusts it → the final truth-table check is part of the method, not an optional extra.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. The source book pairs its theory with a laboratory practicum and circuit-simulation software (TINA, Circuit Wizard); where a school has them, the hands-on work in this lesson is the place to use them.
