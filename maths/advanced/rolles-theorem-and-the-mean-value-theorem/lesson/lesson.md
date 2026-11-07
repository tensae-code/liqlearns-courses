# Rolle's theorem and the Mean Value Theorem — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Rolle's theorem and the Mean Value Theorem
Built from: Greece, Grade 12 Analysis (W12) — Cambodia, the PRIVATE Derivatives booklet (Khem Putthi) — Yemen, Grade 12 Science

## Do it first
Draw a smooth hill that begins and ends at the same height. Somewhere between the ends the path must level out — at the top it is flat for an instant. Now think of a car that covers 120 km in 2 hours: its average speed is 60 km/h, and at some moment its speedometer must have read exactly 60. Two everyday certainties — and they are the two theorems of this lesson, taught together in Yemen's Grade 12 Science book as one lesson (Unit 6, 6-7, contents/PDF p.183) and in Greece's Grade 12 Analysis book inside its differential calculus chapter (W12, Ch.2, pp.91–184).

## Then the explanation
**Rolle's theorem.** If a function f is (1) continuous on the closed interval [a, b], (2) differentiable on the open interval (a, b), and (3) has equal endpoint values, f(a) = f(b), then there is at least one point c strictly inside (a, b) with f′(c) = 0 — a flat tangent. The picture is the hill: equal heights at the ends, a smooth unbroken path, so a highest or lowest point inside has a horizontal tangent. Example: f(x) = x² − 4x + 3 on [1, 3]. f(1) = 0 and f(3) = 0, the polynomial is continuous and differentiable everywhere, and f′(x) = 2x − 4 = 0 gives c = 2, inside the interval, as promised.

**The Mean Value Theorem.** Drop the third condition. If f is continuous on [a, b] and differentiable on (a, b), then there is at least one c inside with f′(c) = (f(b) − f(a))/(b − a): some point's instantaneous rate equals the whole interval's average rate — the tangent at c is parallel to the chord joining the endpoints. The car is the picture: the chord's slope is the average speed, and some instant matches it. Example: f(x) = x² on [1, 3]: (9 − 1)/(3 − 1) = 4, and f′(x) = 2x = 4 gives c = 2, inside, as promised. Greece's book teaches the Mean Value Theorem in the same differential calculus chapter as its extrema work (W12, Ch.2, pp.91–184), where the theorem does its main job: a positive derivative throughout an interval forces the function to increase there.

**The proofs.** Cambodia's Derivatives booklet (Khem Putthi) — a PRIVATE booklet, not a MoEYS book — states and proves both theorems (pp.50–52). Rolle's theorem is proved from the extreme value fact: a continuous function on [a, b] attains a maximum and a minimum; if both sit at the endpoints the function is constant and every point works, otherwise an interior extreme point has derivative zero. The Mean Value Theorem is then proved from Rolle's theorem by an auxiliary function: subtract from f the chord's own line, g(x) = f(x) − f(a) − ((f(b) − f(a))/(b − a))(x − a), which has g(a) = g(b) = 0, apply Rolle to g, and the point it gives is exactly the c of the Mean Value Theorem. One theorem carrying the other — that chain is the proof the booklet builds, and it is worth learning as a shape: tilt the picture until Rolle applies.

Tip — from us, not from the books. Before solving for c, always recite the conditions and check them one by one. Most wrong uses of these theorems are not wrong algebra — they are a theorem applied where a condition fails, like |x| on [−1, 1], which is continuous with f(−1) = f(1) but has no flat tangent, because it is not differentiable at 0.

**Using the theorems.** The Mean Value Theorem is the bridge between a derivative's sign and a function's behaviour: if f′(x) = 0 at every point of an interval, then for any two points the theorem gives f's change as 0 times the distance — f is constant there. If f′ > 0 throughout, every chord has positive slope, so f increases. It also bounds error: a function whose derivative stays below M in size cannot change faster than M times the distance travelled. Yemen's book places the two theorems inside its full differentiation unit, after implicit differentiation and before the maxima-and-minima lessons that lean on them (Unit 6, 6-7, contents/PDF p.183).

**Closing part: L'Hôpital's rule.** When a limit gives the indeterminate form 0/0 or ∞/∞, and the derivatives behave, the limit of the quotient equals the limit of the quotient of the derivatives: lim f(x)/g(x) = lim f′(x)/g′(x). Greece's book teaches De L'Hospital's rules for evaluating limits in its differential calculus chapter (W12, Ch.2, pp.91–184). Cambodia's PRIVATE Derivatives booklet states the rule for 0/0 and ∞/∞ and proves the 0/0 case from Cauchy's extended Mean Value Theorem — the Mean Value Theorem's own generalisation, so this lesson's closing part grows out of its main theorems — and reduces the other indeterminate forms (0·∞, ∞ − ∞, 1^∞ and their kin) to quotients before applying it (pp.53–54). Cambodia's PRIVATE Limits and Continuity booklet also states and applies the rule to 0/0 and ∞/∞ forms (pp.62–64). First example: lim(x→0) sin x / x = lim(x→0) cos x / 1 = 1, matching Lesson 87's squeezed answer. Second: lim(x→0) (eˣ − 1)/x = lim(x→0) eˣ/1 = 1. Check the form before you differentiate: the rule belongs to 0/0 and ∞/∞ only.

## Say it to your companion
State Rolle's theorem with all three conditions, then state the Mean Value Theorem and say exactly which condition changed. Then explain the tilt trick: how subtracting the chord turns the Mean Value Theorem into Rolle's theorem. Your companion then explains why |x| on [−1, 1] defeats Rolle's theorem even though its endpoint values are equal.

## Do It Yourself
1. Verify Rolle's theorem for f(x) = x² − 4x + 3 on [1, 3] and name c.
2. Verify Rolle's theorem for f(x) = x³ − 3x on [−√3, √3] and name every c.
3. Find c for f(x) = x² on [1, 3] under the Mean Value Theorem.
4. Find c for f(x) = 1/x on [1, 2] under the Mean Value Theorem, and check it lies inside.
5. Say which condition fails for f(x) = |x| on [−1, 1], and what goes wrong.
6. Use L'Hôpital's rule for lim(x→0) (eˣ − 1)/x and for lim(x→∞) (3x + 1)/(x − 2), checking the form first each time.
