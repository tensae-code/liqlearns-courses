# Lesson plan — Vector Spaces

**One thing:** what makes a set of vectors a vector space or a subspace — the closure test — and the whole working kit built on it: intersections and sums of subspaces, the Grassmann dimension formula, direct sums and complementary subspaces, the union criterion from the teacher's guides, and linear combinations, span, independence, basis, dimension and coordinate vectors.

**Stage:** Advanced Mathematics (Stage 12). **Level 148** (Rwanda merge, 2026-11-07).

**Why this lesson exists:** Rwanda's Senior Five and Senior Six Advanced Learner's Books both build vector spaces as a full unit — Senior Five from R³, the subspace test and span up to basis and dimension, Senior Six returning to intersections and sums and working them by solving systems — with the two teacher's guides adding a union criterion neither Learner's Book states. The vectors lesson in this course works with vectors themselves (products, geometry, applications); the abstract space structure had no home. Under the everything-goes-in ruling (2026-11-06), it gets its own lesson. S5/S6 books in this set are the Advanced Mathematics stream, and this lesson says so throughout.

## The climb

1. **The space R³ and the subspace test** — a non-empty set closed under addition and scalar multiplication is a subspace; the zero vector comes free.
2. **Intersections** — the intersection of two subspaces is always a subspace, found in practice (Senior Six) by solving the two sets of conditions as one system; its dimension comes from the solution set.
3. **The union criterion (guide evidence)** — a union of two subspaces is a subspace only in the nested case: W₁ ⊆ W₂ or W₂ ⊆ W₁ (Senior Five guide p. 97; Senior Six guide p. 292).
4. **Sums, Grassmann, direct sums** — F + G is the smallest subspace containing both; dim(F + G) = dim F + dim G − dim(F ∩ G); the sum is direct when the intersection is {0}, and then every vector in it splits uniquely; complementary subspaces fill the whole space with a direct sum.
5. **Combinations, span, independence** — linear combinations; the span as all of them; independence as "no vector is a combination of the others", tested by the determinant in R³.
6. **Basis, dimension, coordinates** — a basis is an independent spanning set; its size is the dimension; every vector has exactly one coordinate vector relative to a basis.

## Add-on slots

- slot-vecspace-0 (IMAGE): a picture of two planes through the origin in R³ meeting in a line through the origin, the line labelled "intersection — always a subspace". What the student does: says why the meeting set must contain the zero vector and be closed.
- slot-vecspace-1 (IMAGE): a picture of two lines through the origin in a plane, their union drawn as a cross, with a sum of one vector from each line landing outside the cross. What the student does: explains from the picture why the union fails the closure test.
- slot-vecspace-2 (GIF, 1–2 s): a strip showing the Grassmann count — two overlapping discs labelled dim F and dim G, the overlap dim(F ∩ G) shaded twice then corrected once. What the student does: watches, then states why the overlap is subtracted exactly once.
