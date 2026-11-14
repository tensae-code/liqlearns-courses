# Lesson plan — Detecting Errors in Transmitted Data — The Parity Bit

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Detecting Errors in Transmitted Data — The Parity Bit
**Place in the curriculum:** ICT expansion — Switzerland (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Switzerland's Décodage teacher guides (DEF-DGEO, canton de Vaud, French; CC BY NC SA 4.0), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building. This lesson stands on teacher-guide evidence only (Switzerland), named in its sources, counted nowhere.
**The one thing this lesson teaches:** detecting errors in transmitted data with the parity bit (le bit de parité): one extra bit that makes the count of 1s even (or odd), so a single flipped bit betrays itself (Switzerland Grade 8 Décodage, Enquête 5).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **One extra bit that watches the others** — The **parity bit (bit de parité)** is one extra bit sent with each group of data bits, chosen so the total count of 1s is **even** (even parity) — or odd, if the two sides agreed odd. The receiver counts again: if the parity is wrong, something flipped on the journey. The inquiry's experiment is the whole idea in miniature: send, flip one bit in secret, and watch the count expose it.
2. **What parity can and cannot do** — Parity **detects** a single flipped bit — it cannot say which bit flipped, so it cannot correct the error, only declare the group suspect. Two flips restore the parity and slip past unseen: parity is a cheap alarm, not a guard. Real systems stack stronger checks on the same idea — more check bits, cleverer counts — but every error-detecting code is parity's descendant: spare a little data to watch the rest.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Switzerland's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. One extra bit sent with each group of data bits
2. Even
3. It counts again — wrong parity means something flipped
4. Even or odd parity

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A message crosses a noisy wire and one bit flips on the way. The receiver gets a wrong letter — and no alarm rings. Before reading on: what cheap trick could make the wrongness visible at the other end? (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one extra bit that watches the others as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of what parity can and cannot do in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one extra bit that watches the others → the student studies the picture and names what each part shows
- GIF — a GIF of what parity can and cannot do in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
