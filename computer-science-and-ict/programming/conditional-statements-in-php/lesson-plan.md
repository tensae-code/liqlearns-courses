# Lesson plan — Conditional Statements in PHP

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Conditional Statements in PHP
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Runs its block only when its condition is true.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **If in PHP — the page decides** — A PHP page without conditions does the same thing for every request; most real pages must **decide**. The **if statement** runs its block only when its condition is true, **else** offers the other road, and **elseif** chains further choices — the same add-decide pattern this course teaches in every language, now wearing PHP's clothes and standing in a web page. In the dictionary project the decisions are the site's manners: **if** the submitted term is empty, refuse it with a message; **else if** the term already exists, say so; **else** store it and confirm. Each branch is a promise the site makes about one case — and the cases must cover the world the page will actually meet.
2. **Conditions on web data — presence, equality, permission** — Web conditions have their own daily family. **Presence**: was this field sent at all, and is it empty? **Equality and comparison**: does this term already exist in the table; is this number in range? **Permission**: is this visitor the authorised user allowed to add — the condition that separates the Add_Term page's public face from its working face. The faults are the family's too: a condition written `=` where `==` was meant (assigning instead of comparing), branches in the wrong order so the general case swallows the specific one, and the case nobody wrote a branch for arriving on the first day. Egypt teaches conditionals inside the project, at the moment the pages first need to judge, because a conditional is only understood when something real depends on the branch taken.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Runs its block only when its condition is true.
2. Else offers the other road; elseif chains further choices.
3. It separates the page's public face from its working face — only the authorised user may add.
4. Assigning instead of comparing — the condition stops testing and starts setting.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 11 book names this topic in the language of its Arabic twin — transactions and conditional sentences in PHP. It is the project's decision layer: the PHP page that checks before it stores, chooses what to show, and answers differently according to what it finds. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of if in php — the page decides as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of conditions on web data — presence, equality, permission in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of if in php — the page decides → the student studies the picture and names what each part shows
- GIF — a GIF of conditions on web data — presence, equality, permission in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
