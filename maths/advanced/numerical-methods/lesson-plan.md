# Lesson plan — Numerical Methods

**One thing:** solving f(x) = 0 when no formula will do it — estimating between two known points (interpolation and extrapolation), trapping a root where the function changes sign, and then closing in on it with Newton–Raphson or with fixed-point iteration x = g(x), where the rearrangement you choose decides whether the iteration converges at all.

**Stage:** Advanced Mathematics (Stage 12). **Level 147** (Rwanda merge, 2026-11-07).

**Why this lesson exists:** Rwanda's Senior Five Advanced Learner's Book gives numerical methods a full unit — interpolation, sign-change root location, Newton–Raphson, fixed-point iteration — while the read set's other equation lessons solve exactly or not at all. Approximate solving, and above all the comparison of rearrangements of one equation, had no home. Under the everything-goes-in ruling (2026-11-06), it gets its own lesson. S5/S6 books in this set are the Advanced Mathematics stream, and this lesson says so.

## The climb

1. **Linear interpolation and extrapolation** — estimate a value between two known points on the straight line joining them (interpolation), or beyond them (extrapolation, and less safe); the same line, set to zero, estimates a root.
2. **Root location by sign change** — where a continuous function takes opposite signs at two points, a root lies between them; narrow the trap by tabulation (analytically) or by reading the crossing off a graph.
3. **Newton–Raphson** — x next = x − f(x)/f′(x): follow the tangent at the current guess down to the axis, repeat; fast when it works, dangerous near a stationary point or a bad start.
4. **Fixed-point iteration** — rearrange f(x) = 0 as x = g(x) and iterate x, g(x), g(g(x)), …; different rearrangements of the same equation behave completely differently — convergence is a property of the rearrangement (guided by |g′(x)| < 1 near the root), not of the equation.

## Add-on slots

- slot-num-0 (IMAGE): a picture of a curve crossing the axis between two tabulated points stamped with opposite signs, the bracket drawn around the crossing. What the student does: says why a root must lie inside the bracket before any iteration starts.
- slot-num-1 (IMAGE): a picture of a tangent line at a first guess touching a curve and landing nearer the root on the axis, with the Newton–Raphson formula beside it. What the student does: names which part of the step is f(x) and which is f′(x).
- slot-num-2 (GIF, 1–2 s): a strip showing two iteration ladders for the same equation — one rearrangement's rungs closing in on the root, the other's bouncing away. What the student does: watches, then says which rearrangement converges and what decides it.
