# Lesson plan — Variance and Standard Deviation

**Course:** Computer Science and ICT · **Title:** Spreadsheets · **Lesson:** Variance and Standard Deviation
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Spreadsheets on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** How far values scatter around their centre.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Variance — the average squared distance from the mean** — Two classes can share the same average mark and be nothing alike — one tightly bunched, one split between top and bottom. **Variance** measures that scatter: for each value, take its **distance from the mean**, **square** it (so negatives cannot cancel positives, and big distances count heavily), and **average** the squares. In the spreadsheet this is **VAR.P** over the range — the book's population form, used when the data in hand is the whole group being described. A variance of zero means every value equals the mean; the larger the variance, the wider the scatter.
2. **Standard deviation — spread in the data's own units** — Variance's flaw is its unit: squared marks are marks², which nobody can picture. **Standard deviation** fixes it by taking the **square root of the variance**, returning the spread to the data's own units — marks, centimetres, seconds. Read it as the **typical distance** of a value from the mean: most values lie within about one standard deviation of the centre. Egypt's analysis sequence uses it to compare groups fairly — two classes, two years, two products — because a difference in averages means one thing when the spread is small and quite another when the spread is wide.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Spreadsheets on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. How far values scatter around their centre.
2. The average of the squared distances of the values from the mean.
3. The square root of the variance.
4. To return the spread to the data's own units — marks, not marks squared.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 10 data-analysis run climbs from organising data and averages into spread: how far values scatter around their centre. Variance and standard deviation are the two measures that answer it, computed in the spreadsheet with VAR.P and its square root. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of variance — the average squared distance from the mean as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of standard deviation — spread in the data's own units in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of variance — the average squared distance from the mean → the student studies the picture and names what each part shows
- GIF — a GIF of standard deviation — spread in the data's own units in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
