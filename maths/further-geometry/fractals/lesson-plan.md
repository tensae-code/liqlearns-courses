<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Fractals: shapes inside shapes

**Course:** Maths · **Unit:** Unit 9 — Further Geometry · **Lesson:** Fractals: shapes inside shapes
**Place in the curriculum:** Level 79 of 136, in Unit 9 — Further Geometry (maths/CURRICULUM.md).
**The one thing this lesson teaches:** what a fractal is — a shape built by repeating one step forever, so the same pattern appears at every size — met through the two places China's books file it: the Sierpiński and Koch figures in a Grade 9 reading, and the Julia and Mandelbrot sets grown from z → z² + c in a senior extended reading.
**This lesson's own level:** it stands on similarity (same shape, different size) and on a first meeting with complex numbers for the second reading. It needs nothing else. This is a readings lesson: both of its sources are filed as readings/enrichment in their books, and the lesson is built honestly at that size — it teaches what the readings teach, no more.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Self-Similarity and the Sierpiński Figures** — what a fractal is, self-similarity, and the Sierpiński triangle and carpet, counting the survivors at each step. (Was depth Level 1.)
2. **The Koch Snowflake** — the Koch step on a segment, and how the snowflake's perimeter grows by 4/3 at every step. (Was depth Level 2.)
3. **Iteration: Julia and Mandelbrot** — from paper to numbers — iterating z → z² + c, and how that one test grows the Julia and Mandelbrot sets. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Congruence and similarity (same stage) — a fractal is similarity repeated without end — and a first meeting with complex numbers helps for the Julia/Mandelbrot part. Recommended, never forced.
- Squared paper, a ruler and a pencil are needed; a computer or phone that can show the Mandelbrot set helps but is not required.

## What the learner can do when it ends
1. Say what makes a figure a fractal — one step repeated, the same pattern at every scale (self-similarity) — as China's Grade 9 Volume 2 reading presents the fractal figures (printed pp. 45–46).
2. Run the Sierpiński step: from a triangle or a square carpet, remove the middle part and repeat on what remains, and count what each step multiplies (Grade 9 Volume 2 reading, printed pp. 45–46).
3. Run the Koch step: cut each segment into thirds, build a point on the middle third, and say what happens to the snowflake's perimeter at each step (Grade 9 Volume 2 reading, printed pp. 45–46).
4. Iterate z → z² + c by hand for small values and say whether the orbit stays bounded or escapes, the mechanism China's senior B-edition reading uses to grow the Julia and Mandelbrot sets (Compulsory Volume 4, B edition, Chapter 10 extended reading, printed pp. 40–41).

## What you need
Squared paper, a ruler, a pencil. For the iteration work, a calculator is enough — the numbers in this lesson are chosen small.

## The run of the lesson (in order)
1. **Do it first** — the learner draws one Sierpiński step on a squared-paper triangle and counts the triangles before and after, before the word fractal is given (lesson/lesson.md).
2. **The explanation** — self-similarity; the Sierpiński triangle and carpet; the Koch snowflake and its growing perimeter; then the jump from paper to numbers: iteration z → z² + c, bounded or escaping, Julia and Mandelbrot (lesson/lesson.md).
   - ADD GIF at the Sierpiński part: a picture of a triangle hollowing itself out step by step, the middle triangle vanishing at each step while three corner copies shrink — the student counts the surviving triangles aloud at each step: 1, 3, 9, 27.
   - ADD IMAGE at the Koch part: a picture of one straight segment growing its middle point, then all four segments doing the same, building the first two steps of the snowflake → the student counts the segments before and after each step.
   - ADD IMAGE at the Mandelbrot part: a picture of the Mandelbrot set in colour, its edge covered in smaller copies of the whole shape → the student finds one small copy on the boundary and points to its "head" and "body".
3. **Say it to your companion** — explain why repeating one small step makes a shape that looks the same big and small (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the same shape at every size in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the four tasks at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- GIF — a picture of a Sierpiński triangle hollowing out step by step → the student counts the surviving triangles at each step.
- IMAGE — a picture of the first two Koch steps growing on one segment → the student counts segments before and after.
- IMAGE — a picture of the Mandelbrot set in colour → the student finds a small copy of the whole on its edge.
- VIDEO — the video-script filmed (made later) → the student runs one iteration along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Counts the REMOVED triangles instead of the survivors → in the Sierpiński step, always count what is KEPT: each kept triangle becomes 3 smaller kept triangles.
- Thinks the Koch perimeter must settle down → count with them: segments multiply by 4 while each is 1/3 as long, so the total grows by 4/3 every step, forever. A bounded shape with an endless perimeter is the surprise this reading exists to give.
- Loses the iteration arithmetic → write the orbit as a chain with arrows, z₀ → z₁ → z₂ …, squaring first, then adding c, one step per line. Small c values only: 0, 1, −1.
- Asks "where is the rest of the theory?" → there is none in the stock, and that is the honest answer: both sources are readings. This lesson is the reading, taught whole — the learner who wants more has met the doorway, not a dead end.
- This lesson's next door: De Moivre's theorem and the complex-number lessons in the Advanced stage grow directly out of the z → z² + c iteration used here.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (China, Grade 9 Volume 2 reading, printed pp. 45–46; China, Compulsory Volume 4 B edition, Chapter 10 extended reading, printed pp. 40–41). Both sources are readings/enrichment as filed — not main-text teaching — and the lesson and its sources say so wherever they are cited. The lesson is deliberately built at the size the stock supports (23 questions); it is not padded to the size of a main-text lesson. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
