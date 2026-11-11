# Transition Curves: Joining Curves Smoothly

You do it, we guide you. Two pieces of road meet. Your job:
make the meeting place impossible to feel.

## Sub lesson 1 — Meeting Without a Kink

A straight road runs along y = 0. Later it must run along
y = 1 — the same direction, one unit higher. Between x = 0
and x = 2 a joining piece f must climb from the one line to
the other.

Two things must agree where the pieces meet:

- **The values.** At x = 0 the join starts where the straight
  is: f(0) = 0. At x = 2 it arrives where the upper straight
  is: f(2) = 1. If the values disagreed, the road would have
  a **step** — a jump no wheel can cross.
- **The slopes.** The straights are level, so the join must
  start and end level: f′(0) = 0 and f′(2) = 0. If the slopes
  disagreed, the road would have a **kink** — a corner the
  driver feels as a jolt.

Four conditions. A cubic has four coefficients, so try a
cubic. The piece

**f(x) = −¼x³ + ¾x²** (for 0 ≤ x ≤ 2)

meets all four. Check: f(0) = 0; f(2) = −2 + 3 = 1.
f′(x) = −¾x² + (3/2)x, so f′(0) = 0 and f′(2) = −3 + 3 = 0.
Halfway along, f(1) = −¼ + ¾ = ½ — the S-shaped climb passes
exactly through the middle, rising gently, then levelling
off. No step, no kink.

## Sub lesson 2 — Matching the Bending

And yet a driver still feels this join. Why? Watch the
**bending**. On a straight, the graph does not bend at all:
f′′ = 0. On the join,

f′′(x) = −(3/2)x + 3/2, so **f′′(0) = 3/2**.

The moment the car enters the join, the bending jumps from
0 to 3/2. The steering wheel must be turned *suddenly* — that
sudden change of curvature is what road builders call a
**curvature jump** (in German, a Krümmungsruck), and avoiding
it is the whole point of a proper transition curve.

So a join that cannot be felt needs a third agreement at
each meeting point:

- **The second derivatives.** f′′ of the join must equal f′′
  of the piece it meets — here 0 at both ends.

Our cubic cannot do it: all four of its coefficients are
already spent on the value and slope conditions. Conditions
are bought with coefficients — count them before you build.

## Sub lesson 3 — Designing the Join

Now design the full join, on [0, 1] this time, from y = 0 up
to y = 1. The conditions:

- at x = 0: f(0) = 0, f′(0) = 0, f′′(0) = 0
- at x = 1: f(1) = 1, f′(1) = 0, f′′(1) = 0

**Six conditions**, so the piece needs six coefficients:
degree five. The piece that meets them all is

**f(x) = 10x³ − 15x⁴ + 6x⁵.**

Check every condition. f(0) = 0. f(1) = 10 − 15 + 6 = 1.
f′(x) = 30x² − 60x³ + 30x⁴ = 30x²(1 − x)² — zero at x = 0
and at x = 1. f′′(x) = 60x − 180x² + 120x³ = 60x(1 − x)(1 − 2x)
— also zero at x = 0 and at x = 1. Value, slope and curvature
all agree at both ends: no step, no kink, no curvature jump.

This is the design pattern, and it is the lesson: **write
the conditions first; let their number choose the degree
(conditions − 1); solve for the coefficients; then check
every condition on the finished piece.** Germany's Grade 10
book sets exactly this task for road alignments — its name
for the joining pieces is *Trassierungen*, transition
curves.

## Do It Yourself

1. For the cubic join f(x) = −¼x³ + ¾x² on [0, 2], verify
   the join at x = 0 as well: f(0) = 0 and f′(0) = 0, so it
   leaves the lower straight with no step and no kink.
2. Show that the cubic join is steepest halfway along:
   f′(1) = −¾ + 3/2 = ¾, and f′′(1) = 0 — the bending
   changes sign at the middle of the S.
3. A join must meet value and slope conditions at both ends
   but no curvature conditions. How many conditions is that,
   and what is the lowest degree that can meet them?
   (Four conditions; degree three — the cubic of Sub
   lesson 1.)
4. Explain to a friend why matching slopes is not enough
   for a railway or road join. Use the words "curvature"
   and "jump", and the cubic's f′′(0) = 3/2 as your
   evidence.
