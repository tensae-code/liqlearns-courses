# Continuity — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Continuity
Built from: Kuwait, Grade 12 Term 1 (scientific) — Laos, Grade 10 — Armenia, Algebra and Analysis 11 — Vietnam, Toán 11 Tập Một — Libya, Grade 11 Science — Pakistan, Mathematics Classes 11 and 12 — Yemen, Grade 11 and Grade 12 Science — Indonesia, Matematika Tingkat Lanjut Grade 12 (Edisi Revisi) — Nepal, Grade 10 Optional — Egypt, Pure Mathematics Grade 11 — Cambodia, Grade 12 Basic and the PRIVATE Limits and Continuity booklet (Khem Putthi)

## Do it first
Draw y = x² without lifting your pen: easy, one unbroken curve. Now try to draw the graph of the function that is 0 for x < 1 and 2 for x ≥ 1: at x = 1 your pen must jump. **Continuity** is the mathematics of "no jump, no hole": a function you can draw in one piece. Kuwait's Grade 12 book gives continuity its own run of lessons inside its limits unit (Unit 1, 1-5 to 1-7, pp.48–71).

## Then the explanation
**The three conditions.** A function f is continuous at a point a when all three hold: (1) f(a) exists; (2) lim(x→a) f(x) exists; (3) f(a) = lim(x→a) f(x). Laos's Grade 10 book states the three conditions in exactly this form and works examples of discontinuity against them (Ch.VI L16, pp.166–175). Fail any one condition and the function is discontinuous at a — and naming the failed condition names the break. Yemen's Grade 11 Science book teaches continuity as its own lesson right after limits (Unit 5, 5-2, p.133).

**Removable discontinuities.** If the limit exists but the point is missing or sits at the wrong height, the break is a single point — a hole. It is called removable because one redefinition repairs it: set f(a) equal to the limit, and all three conditions hold. Pakistan's Class 12 book teaches removable discontinuities alongside jump discontinuities (Ch.1, ch-pp.32–35). Nepal's Grade 10 Optional book works the model case: for f(x) = (x² + x − 6)/(x + 3), the limit as x → −3 is −5, but f(−3) is undefined — condition (1) fails, and filling in f(−3) = −5 would remove the break (Lesson 12, pp.275–293).

**Jump discontinuities.** If the left-hand and right-hand limits both exist but are different, the graph jumps, and no single point can repair it — the two sides never meet. Check the sides first, the way Libya's Grade 11 Science book closes its limits chapter with continuity at a point (Ch.5, pp.111–138): equal sides with a missing or misplaced point means removable; different sides means a jump. A third kind appears when a side runs away to infinity — an infinite discontinuity, at a vertical asymptote.

Tip — from us, not from the books. Run the test in order and stop at the first failure: no f(a) → hole or worse; sides disagree → jump; sides agree but f(a) differs → removable. The first failure tells you the kind of break without any more work.

**Continuity on an interval.** A function is continuous on an open interval when it is continuous at every point inside it. On a closed interval [a, b] it must also meet the one-sided conditions at the ends: the right-hand limit at a equals f(a), and the left-hand limit at b equals f(b). Kuwait's book teaches continuity on an interval as its own lesson (1-7, pp.61–71), after the continuity theorems (1-6, pp.54–60): sums, differences, products and quotients (with non-zero denominator) of continuous functions are continuous, so every polynomial is continuous everywhere, and rational functions are continuous wherever they are defined. Indonesia's Revisi book states continuity as a definition inside its limits-and-derivatives chapter (Definisi 2.2, p.96), and Egypt's Pure Grade 11 book closes its limits unit with continuity at a point and on an interval (Unit 3, 3-6, p.119).

**Continuity of the elementary functions.** Armenia's Grade 11 book follows continuity of a function with continuity of the elementary functions — the standard functions are continuous on their domains (Ch.4/5, §§1–2, pp.74–76). Vietnam closes its limits chapter with continuous functions as their own lesson (Bài 17, p.119). Cambodia's PRIVATE Limits and Continuity booklet (Khem Putthi — a private booklet, not a MoEYS book) states the three conditions, the algebra of continuous functions and continuity on open and closed intervals (pp.20–22); Cambodia's Grade 12 Basic book sets continuity exercises, including a piecewise function continuous at x = 1 exactly when a = 2 (Ch.1 §1.2, pp.28–42). Yemen's Grade 12 Science book opens its differentiation unit with limits and continuity of the trigonometric functions — sin and cos are continuous everywhere (Unit 6, 6-1, contents/PDF p.154).

**The Intermediate Value Theorem.** If f is continuous on [a, b], it takes every value between f(a) and f(b). The use the books make of it: if f(a) and f(b) have opposite signs — f(a)·f(b) < 0 — then some c between them has f(c) = 0: the equation f(x) = 0 has a root in the interval. Cambodia's PRIVATE booklet states the theorem in this form (pp.20–22), and Cambodia's Grade 12 Basic book uses it to place a root of f(x) = x − 1 − sin x in (0, π) from f(0)·f(π) < 0 (§1.2, pp.28–42). Continuity is what makes the crossing unavoidable: a graph in one piece cannot get from below the axis to above it without crossing it.

## Say it to your companion
Give your companion a function and a point. They run the three-condition test aloud and name the break if there is one. Trade with the jump function that is 0 for x < 1 and 2 for x ≥ 1, then with Nepal's (x² + x − 6)/(x + 3) at x = −3, and compare: which break can be repaired, and why can the other never be?

## Do It Yourself
1. Test f(x) = x² − 3x at x = 2 with the three conditions.
2. Find the break of g(x) = (x² − 4)/(x − 2) at x = 2: its kind, and the value that repairs it.
3. For the function that is x for x < 3 and 7 for x ≥ 3, find both one-sided limits at 3 and name the break.
4. Find a so that the function that is x + a for x < 1 and 3x for x ≥ 1 is continuous at 1.
5. Show that x³ − x − 1 = 0 has a root between 1 and 2, using the Intermediate Value Theorem.
6. State why every polynomial is continuous at every point.
