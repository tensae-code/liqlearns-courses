# Parametric Equations — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Parametric Equations
Built from: Cambodia, Grade 12 Advanced student book and its teacher guide — Mauritania, Mathématiques 7ème AS série C (7AS-C)

## Do it first
Take x = t and y = t². For t = −2, −1, 0, 1, 2 the points are (−2, 4), (−1, 1), (0, 0), (1, 1), (2, 4). Plot them: a parabola, drawn not by an equation linking x and y directly, but by a third quantity — t — driving both coordinates at once. Cambodia's Grade 12 Advanced book opens its parametric chapter with exactly this example (Ch.9, printed p.235), and Mauritania's final-year C-stream book gives parametric curves a chapter of their own, "Courbes paramétrées" (7AS-C, Ch.13, printed p.159). That driving third quantity is the subject of this lesson.

## Then the explanation
**What a parameter is.** A curve given **parametrically** is a set of points (x, y) = (f(t), g(t)) as t runs over an interval I: two equations, x = f(t) and y = g(t), one point for each value of the **parameter** t. Cambodia's teacher guide for the chapter states the objectives plainly: define parametric equations of a curve, and convert parametric equations to Cartesian equations (guide, printed pp.227–236). The parameter is often time, and that is the point: a parametric description tells you not only the path but where the traveller is at each moment, and which way it is moving — information a plain y = f(x) equation throws away.

**Plotting from a table.** The working method is a table: choose t-values, compute (f(t), g(t)) for each, plot the points, join them in t-order. The chapter's opening example, x = t, y = t², plots to the parabola you drew in Do it first (Cambodia, Grade 12 Advanced, Ch.9, printed p.235). The t-interval is part of the description: the same two formulas with t ≥ 0 give only the right half of the parabola.

**Eliminating the parameter.** To get the **Cartesian equation** — one equation in x and y alone — solve one parametric equation for t and substitute into the other. From x = t, substitution into y = t² gives y = x² at once (Ch.9, printed p.235). Elimination shows the path's shape; the parametric form remains the fuller description, because it keeps the journey: the interval travelled, the direction, and the position at each t.

**Circles and ellipses.** Cambodia's guide works the standard circular forms for this chapter: a circle as x = h + a sin θ, y = k + b cos θ for 0 ≤ θ ≤ 2π, with the ellipse (x − h)²/a² + (y − k)²/b² = 1 as its Cartesian partner (guide, printed pp.227–236). Read the parameters off: the centre is (h, k), a and b are the two radii, and squaring and adding the parametric pair returns the Cartesian ellipse — with a = b it is a circle. One parameter, θ, walks the whole closed curve, something no single y = f(x) can do, since a circle is not a function of x.

**The slope of a parametric curve.** Since both coordinates move with t, the slope comes through t: dy/dx = (dy/dt) / (dx/dt), wherever dx/dt ≠ 0. For x = t, y = t²: dy/dt = 2t and dx/dt = 1, so dy/dx = 2t = 2x — the slope of y = x², recovered through the parameter. Where dx/dt = 0 the tangent is vertical; where both derivatives vanish, the curve may stop or turn back on itself — behaviour only the parametric form can show.

**Projectile motion — Cambodia's worked flight.** The chapter's full application is a projectile fired at 45° (Ch.9 §9.1, printed p.236). The student book's numbers are: initial speed **v₀ = 48 cm/s** and g = 32 cm/s² (the example works in cm/s throughout — a toy scale, but internally consistent, as filed). At 45°, the two components of the velocity are both 48/√2 = 24√2, so the flight is

x = 24√2 t,   y = −16t² + 24√2 t.

At t = 0 the projectile is at (0, 0); at t = 1 it is at (24√2, 24√2 − 16) ≈ (33.9, 17.9). Eliminating t — t = x/(24√2) — gives the path

y = −x²/72 + x,

a downward parabola. It lands when y = 0 again: x = 72 cm, at t = 3√2/2 ≈ 2.12 s. One correction, taught corrected and never as fact: the teacher guide prints this example's v₀ as **45 cm/s** (guide, printed p.227). That is a guide slip — the equation y = −x²/72 + x follows from v₀ = 48 with g = 32, and not from 45 — so this lesson teaches **v₀ = 48 cm/s** throughout, the student book's value. The same chapter goes on to polar coordinates in its second half (the guide cites the student book's printed pp.241 and 243 for that material); polar coordinates themselves are taught in this course's polar-coordinates lesson.

Tip — from us, not from the books. Keep both descriptions of every curve you meet: the parametric form is the journey (where, when, which way), the Cartesian form is the map (the shape alone). If a question asks when or how fast, stay parametric; if it asks what shape, eliminate.

## Say it to your companion
Give your companion the pair x = t, y = t² and ask: what is the point at t = 3, which direction is it travelling, and what is the Cartesian equation? Then swap over the projectile: your companion states v₀, the two parametric equations and the landing point — with v₀ = 48 cm/s, not 45 — and you check each answer against §9.1 (printed p.236).

## Do It Yourself
1. Tabulate x = 2t, y = t² − 1 for t = −2, −1, 0, 1, 2, plot the points in t-order, and eliminate t to get the Cartesian equation.
2. A circle is given by x = 1 + 4 sin θ, y = 2 + 4 cos θ, 0 ≤ θ ≤ 2π. Write its centre, its radius and its Cartesian equation (guide form, printed pp.227–236).
3. For x = t³, y = t², find dy/dx in terms of t, and its value at t = 2.
4. Work Cambodia's projectile: with x = 24√2 t, y = −16t² + 24√2 t, find the position at t = 0.5, verify the path y = −x²/72 + x by elimination, and find the landing time and range (Ch.9 §9.1, printed p.236).
5. Say, in two sentences, what is lost when the parameter is eliminated from a projectile's equations.
