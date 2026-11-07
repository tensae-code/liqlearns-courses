# Step and Piecewise Functions — the lesson

Course: Maths · Stage: Stage 10 — Functions, Graphs and Sequences · Lesson: Step and Piecewise Functions
Built from: Iran, Grade 11 (three branch books) — Nicaragua, Grade 10 student book and module — Kazakhstan, Algebra 9 — Laos, Grade 10 — Kuwait, Grade 10 Term 1

## Do it first
A postage table says: up to 1 kg costs 5; over 1 kg and up to
2 kg costs 8; over 2 kg and up to 3 kg costs 11. Price three
parcels: 0.6 kg, 1 kg exactly, and 2.3 kg. (You should get 5,
5 and 11.) Notice what the price did NOT do: it never slid
smoothly upward. It stayed flat, then jumped. This lesson is
about functions like that — functions that stay flat and jump,
or that change their rule at a break.

## Then the explanation
**The floor function [x].** Iran's Grade 11 books teach the
greatest-integer function as a named function: [x] is the
greatest integer that is not bigger than x (Mathematics and
Statistics (2), Humanities branch, printed pp.34–44, the floor
function at p.37; Hesaban (1), Mathematical Sciences branch,
printed pp.44–53; Mathematics (2), Experimental Sciences
branch, printed pp.48–56). So [2.7] = 2, [5] = 5, [0.3] = 0 —
and on the negative side the drop is bigger than learners
expect: [−1.2] = −2, because −1 is BIGGER than −1.2 and the
floor must not pass x. Nicaragua's Grade 10 book teaches the
same function, written f(x) = [x], and draws its graph
(printed pp.269–271): flat steps, each step running from a
whole number (filled dot, the step's own value) to just before
the next whole number (open dot), then a jump. A staircase
that never slides.

**The fractional part {x}.** Kazakhstan's Algebra 9 sets the
pair side by side (Abylkasymova et al., Part 2, §21, printed
p.24): every number splits as x = [x] + {x}, so the fractional
part is {x} = x − [x]. Because [x] is the whole number just
below (or equal to) x, the leftover always satisfies
0 ≤ {x} < 1 — even for negatives: {−1.2} = −1.2 − (−2) = 0.8.
Its graph is a sawtooth: a ramp climbing from 0 to just under
1, then dropping back to 0 at the next whole number, forever.
Kazakhstan's book graphs [x] and {x} together as its examples
of periodic behaviour — the same tooth repeats every 1.

**The sign function sgn.** Laos's Grade 10 book teaches the
sign function beside the floor function (Lesson 10, printed
p.83): sgn(x) is 1 when x is positive, 0 when x is zero, and
−1 when x is negative. Its graph is three flat pieces — a step
up at 0 from −1 to 0, and another from 0 to 1. It answers one
question only: which side of zero are you on?

**Step functions in real charges.** Iran's Humanities book
opens this ground with applications (printed p.34): tariffs
and postage charged in steps — the price holds flat across a
band, then jumps at the band's edge, exactly like your
Do-it-first table. A step function is any function whose graph
is a staircase of flat pieces; the floor function is the
pure staircase, and a tariff table is the same shape wearing
prices.

**Piecewise functions — one function, several rules.**
Nicaragua's Grade 10 self-learning module presents the
greatest-integer function itself as a piecewise function
(module, printed p.86): [x] can be written rule by rule —
… −1 for −1 ≤ x < 0, 0 for 0 ≤ x < 1, 1 for 1 ≤ x < 2 … — one
rule per step. That is the general shape Iran's Hesaban (1)
and Mathematics (2) books teach under piecewise definitions
(printed pp.44–53 and pp.48–56): a function written with
different rules on different parts of its domain. To evaluate
one, find which part the input falls in, and run only that
part's rule. The books' everyday picture is the taxi: one rule
for the first part of the ride, another after — one function,
chosen by where x stands.

**The absolute-value function and its graph.** Per this
course's plan, the absolute-value function lives in this
lesson. Kuwait's Grade 10 Term 1 book teaches it in full
(Unit 1, printed pp.16–32): f(x) = |ax + b| + c folds the line
at the point where the inside is zero, so the graph is a V
with its vertex at that point, its axis of symmetry the
vertical line through the vertex, and its range starting at
the vertex height c-part and going up. Kuwait teaches two
ways to draw it: redefine it piecewise — |x + 1| + 2 is
−(x + 1) + 2 on the left of −1 and (x + 1) + 2 on the right —
or transform the parent V of |x| by shifts and stretches.
Laos's Grade 10 book likewise counts the absolute-value
function among its named function families (Lessons 8–15,
printed pp.63–165). One correction travels with Kuwait's
book: on printed p.30 the caption for the reflection of
|x + 1| + 2 in the x-axis mislabels the drawn curve; reflecting
gives −|x + 1| − 2, with vertex (−1, −2), and that corrected
form is what this lesson teaches.

> **Tip — from us, not from the books.** For [x] with a
> negative number, walk down the number line in your head and
> stop at the first whole number you reach going DOWN: −1.2
> walks down to −2. "Round towards zero" is the trap; the
> floor only ever walks down.

## Say it to your companion
Call numbers fast — 3.9, −0.4, 7, −5.1, 0 — and your companion
answers each with its three values: "[x] is 3, {x} is 0.9,
sgn is 1." Five numbers each, then swap. The last round is
piecewise: you name a rule pair and an input; they say which
rule ran, and why.

## Do It Yourself
1. Work out [4.8], [−4.8], {4.8} and {−4.8}. (Answers:
   [4.8] = 4; [−4.8] = −5; {4.8} = 0.8; {−4.8} = 0.2 — the
   floor drops to −5, so the leftover is −4.8 − (−5) = 0.2.)
2. Work out sgn(−17), sgn(0) and sgn(2/3). (Answers: −1, 0, 1.)
3. A tariff charges 4 for the first hour or part of it, then
   4 more for each extra hour or part of it. What does a
   2.2-hour stay cost, as a step function? (Answer: 12 — the
   stay touches three hour-steps: hours 0–1, 1–2 and the part
   hour 2–2.2, at 4 each.)
4. f(x) = x + 3 for x < 0, and f(x) = x² for x ≥ 0. Find
   f(−2), f(0) and f(3). (Answers: f(−2) = 1 by the first
   rule; f(0) = 0 by the second rule — 0 belongs to the
   x ≥ 0 side; f(3) = 9.)
5. Name the vertex, the axis of symmetry and the range of
   f(x) = |x − 2| + 1. (Answers: vertex (2, 1); axis x = 2;
   range f(x) ≥ 1.)
