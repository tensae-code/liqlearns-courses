# Function Families: Graphs with a Parameter

You do it, we guide you. One formula is about to become a
whole crowd of graphs — and then the crowd will line up on
one curve.

## Sub lesson 1 — One Formula, Many Graphs

Look at this formula:

**f_t(x) = x² − 2tx + 1.**

There are two letters, and they have different jobs. x is the
variable — it runs along the graph. t is a **parameter**: for
any one graph, t is a single fixed number; change t and you
get a different graph. The formula together with its
parameter is called a **family of functions** (in German, a
Funktionenschar), and each choice of t gives one **member**
of the family.

Write out a few members:

- t = 0: f_0(x) = x² + 1
- t = 1: f_1(x) = x² − 2x + 1 = (x − 1)²
- t = −1: f_−1(x) = x² + 2x + 1 = (x + 1)²
- t = 2: f_2(x) = x² − 4x + 1

Every member is a parabola opening upwards. Complete the
square once, for the whole family at once:

f_t(x) = (x − t)² + 1 − t².

So every member is the same parabola shape, with its vertex
at **(t, 1 − t²)**. Turning t slides the vertex right and
left — and, notice, up and down as well. Hold that thought;
Sub lesson 3 collects all those vertices onto one curve.

## Sub lesson 2 — Investigating a Family

To investigate a family means doing the usual investigation
— zeros, extreme points — **in terms of t**, so the answer
comes out as a statement about the whole family, usually
with cases.

**Zeros.** f_t(x) = 0 is x² − 2tx + 1 = 0, with discriminant

(−2t)² − 4 = 4t² − 4.

- **|t| > 1:** the discriminant is positive — two zeros.
- **t = 1 or t = −1:** it is zero — one (double) zero; the
  parabola touches the axis at its vertex.
- **|t| < 1:** it is negative — no zeros; the whole parabola
  floats above the axis.

**Extreme point.** f_t′(x) = 2x − 2t = 0 gives x = t: the
minimum of every member sits at its vertex (t, 1 − t²), and
the minimum **value** 1 − t² is itself part of the answer —
positive (no zeros) exactly when |t| < 1, which agrees with
the zero cases above. A family investigation answers like
this: not one number, but a rule with cases.

## Sub lesson 3 — Locus Curves

Now collect the vertices. As t runs through all real
numbers, the vertex (t, 1 − t²) moves. On what curve?

Write the vertex's coordinates with capital letters:

X = t,  Y = 1 − t².

Eliminate the parameter: t = X, so **Y = 1 − X²**. Every
vertex of the family lies on the fixed parabola

**y = 1 − x²,**

and every point of it is reached (at t = X). This curve is
called the **locus curve** of the vertices (in German, the
Ortskurve). The method is always the same three steps: find
the special point's coordinates in terms of t; write X and Y
as functions of t; eliminate t.

A second family shows the method is not tied to one example.
h_t(x) = (x − t)² + t has vertex (t, t): X = t, Y = t, so
the locus is the line **y = x**.

And the method reaches beyond vertices. For the cubic family
f_t(x) = x³ − 3tx with t > 0, the extreme points sit at
x = ±√t, with values 2t√t (maximum) and −2t√t (minimum).
Setting X = ±√t gives t = X², and both branches land on one
curve: **y = −2x³**. Maxima and minima of the whole family,
gathered onto a single cubic.

That is the whole lesson: a parameter turns one formula into
a family; the investigation is done in terms of the
parameter, cases and all; and the special points of the
family trace a locus curve, found by eliminating the
parameter.

## Do It Yourself

1. Write out the members of f_t(x) = x² − 2tx + 1 for
   t = 3 and t = −2, and give each one's vertex.
   (x² − 6x + 1, vertex (3, −8); x² + 4x + 1, vertex
   (−2, −3).)
2. For which t does a member of f_t have exactly one zero,
   and where does that member touch the axis? (t = 1,
   touching at (1, 0); t = −1, touching at (−1, 0).)
3. Find the locus of the vertices of the family
   k_t(x) = (x − t)² − 2t. (Vertex (t, −2t); X = t,
   Y = −2t, so the locus is the line y = −2x.)
4. Explain to a friend the difference between the variable
   and the parameter in f_t(x), using the sentence: "Fix t
   and the graph is one parabola; let t run and the vertices
   draw the locus."
