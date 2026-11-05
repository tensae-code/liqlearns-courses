# Differential Equations — the lesson

Course: Maths · Stage 12 — Advanced Mathematics · Lesson 52 of 52
Built from: Jordan, Grade 12 Term 2 — Greece, Grade 12 Analysis — Mauritania, 7AS-C and 7AS-D.

This is the thinnest lesson in the advanced stage, and the lesson says so plainly: three countries teach first-order differential equations, each in one lesson or one short section, and the lesson is built from exactly that much — no more. What the books teach is the separable first-order equation, solved by integrating both sides. Nothing beyond it is claimed.

## Do it first
You are told a rate, and asked for the thing itself. A population grows by 10% a year: that is a rate of change, a derivative. What is the population after some years? You know the derivative; you must find the function. That backwards step — from a rate to the thing itself — is what a differential equation asks for.

## Then the explanation
**What a differential equation is.** A **differential equation** is an equation that holds a derivative in it: dy/dx, or y', standing beside x and y. Jordan's Grade 12 book teaches first differential equations as the last lesson of its integration unit — the natural end of the course, because solving them means integrating. Greece's Grade 12 book teaches differential equations as the short introductory section inside its integral-calculus chapter, in the elementary, separable, first-order form. Mauritania's C-stream book teaches equations differentielles as its own chapter, and its D-stream book teaches them as its seventh chapter. The **order** of a differential equation is the order of the highest derivative in it: dy/dx is first order, d²y/dx² is second order. This lesson teaches first-order equations only, because that is what the books teach.

**Separating the variables.** A first-order equation is **separable** when it can be written with all the y's on one side and all the x's on the other. The books' form is dy/dx = f(x)·g(y), and the move is to divide and multiply until it reads (1/g(y)) dy = f(x) dx — the y-terms gathered with dy on one side, the x-terms gathered with dx on the other. Greece's book teaches the equations in this elementary, separable form, and Jordan's book sets them as the last lesson after integration by substitution, partial fractions and parts — the methods the separating step needs.

**Solving by integrating.** Once separated, integrate both sides: ∫(1/g(y)) dy = ∫f(x) dx. The left side integrates to something with y in it, the right side to something with x, and the two are joined by the constant of integration. The answer is the **general solution**: a family of curves, one for each value of the constant. The simplest example the books' shape gives: dy/dx = 2x separates at once (dy = 2x dx) and integrates to y = x² + C. And dy/dx = y separates as dy/y = dx and integrates to ln y = x + C, so y = Aeˣ — the growth equation, whose solutions are exponentials.

**Initial conditions.** One extra fact — a point the curve passes through — picks one curve out of the family. If y = x² + C must pass through (0, 3), then C = 3, and the **particular solution** is y = x² + 3. Jordan's book teaches the initial condition in its integration unit before the differential-equations lesson, and the same idea carries over: the constant is found from the point.

**Checking a solution.** A claimed solution is checked by differentiating it and putting it back in the equation. For y = x² + 3, dy/dx = 2x, and the equation dy/dx = 2x is satisfied — the answer is right. If it does not fit, the answer is wrong, and the check says so. The books' worked examples are checked this way, and this lesson teaches the check as part of the method, not as an afterthought.

> **Tip — from us, not from the books:** if you cannot see how to separate an equation, try the test the books imply: can you write it as "something with y times dy equals something with x times dx"? If yes, it separates. If a term holds both x and y stuck together with no way to split them, this lesson's method does not apply — and the books do not pretend otherwise.

## Say it to your companion
Give your companion a differential equation — say dy/dx = 3x². Ask them for the general solution (y = x³ + C), and then for the one through (0, 1) (y = x³ + 1). Then swap: they give you dy/dx = y, and you answer (y = Aeˣ; through (0, 2), y = 2eˣ). Check each other's answers by differentiating them back.

## Do It Yourself
1. Solve dy/dx = 2x. (Answer: y = x² + C.) Find the solution through (0, 3). (Answer: y = x² + 3.)
2. Solve dy/dx = 3x². (Answer: y = x³ + C.) Find the solution through (0, 1). (Answer: y = x³ + 1.)
3. Solve dy/dx = y. (Answer: y = Aeˣ.) Find the solution through (0, 2). (Answer: y = 2eˣ.)
4. Check your answer to 1 by differentiating y = x² + 3 and putting it back in dy/dx = 2x.
