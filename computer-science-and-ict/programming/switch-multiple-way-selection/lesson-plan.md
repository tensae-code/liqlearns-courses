# Lesson plan — switch — Multiple-Way Selection

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** switch — Multiple-Way Selection
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** switch selects among many ways by matching one value: the tested value is compared with each case label, the matching case's statements run, and break leaves the switch — without break execution falls through into the next case — while default catches every value no case matched.
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Cases that match a value** — **switch (n) { case 1: … }** compares **n** once against each **case** constant. On a match, that case's statements run. switch suits selections driven by **one value with many named possibilities** — menu choices, day numbers, grade letters — where an if-elif chain would repeat the same test clumsily.
2. **break and default — the two guards** — Without **break**, execution **falls through**: the matched case runs, then the **next** case runs too, and so on — occasionally wanted, usually a bug. **default** is the case for **everything else**, the switch's else, catching values the writer did not name. The book adds a full **exercises** section (§3.26) after the structure (§3.25): trace each exercise by naming the matched case and every statement that runs before a break stops it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. One tested value against each case label.
2. One value with many named possibilities — menus, day numbers, grade letters.
3. Leaves the switch.
4. The case for every unmatched value — the switch's else.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A chain of ifs asking 'is it 1? is it 2? is it 3?' deserves a cleaner tool. switch is that tool — this lesson uses it, and respects its one sharp edge. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of cases that match a value as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of break and default — the two guards in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of cases that match a value → the student studies the picture and names what each part shows
- GIF — a GIF of break and default — the two guards in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
