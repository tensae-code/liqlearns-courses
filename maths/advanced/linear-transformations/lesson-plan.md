<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Linear Transformations

**One thing:** a linear transformation — a map between vector spaces that keeps the grid straight: T(u + v) = T(u) + T(v) and T(ku) = kT(u) — and the two sets that describe what it does, its kernel and its image, tied together by the rank–nullity theorem.

**Unit:** Advanced Mathematics (Unit 12). **Level 155** (Venezuela merge, 2026-11-07).

**Why this lesson exists:** Venezuela's Grade 11 book (*La Matemática y el Vivir Bien*, Lesson 6, printed pp. 143–155) gives linear transformations a complete chapter of their own: the definition and its verification on the zero map, on the derivation map for polynomials and on every 2 × 2 matrix map; the shear worked on a photograph; the first properties proved; the five kinds of linear map; kernel and image as vector spaces in their own right; Sylvester's rank–nullity theorem worked; and rotations shown to be linear from the angle-sum formulas. The library's linear algebra otherwise covers the spaces themselves (the vector-spaces lesson) and the arithmetic of matrices and determinants — no existing lesson is about the maps, their kernels and images, or rank–nullity. So under the everything-goes-in ruling (2026-11-06) the topic gets its own lesson. It stands alone: vector-spaces and matrices are soft hints before it, never gates.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **The Two Laws** — the two laws that make a map linear, checked on the zero map, a matrix map and the derivative map, and told apart from an affine map. (Was depth Layer 1.)
2. **First Properties** — the first properties, proved from the two laws: T(0) = 0, T(−v) = −T(v), and preservation of linear combinations. (Was depth Layer 2.)
3. **The Five Kinds** — the five kinds: monomorphism, epimorphism, isomorphism, endomorphism and automorphism. (Was depth Layer 3.)
4. **Kernel and Image** — kernel and image: computing N(T) and Im(T), and the image-of-a-basis fact taught corrected. (Was depth Layer 4.)
5. **Rank–Nullity** — rank–nullity: dim V = dim N(T) + dim Im(T), and a rotation about the origin as a linear map. (Was depth Layer 5.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## The climb

1. **What "linear" means** — a photograph's affine change x* = ax + by + r, y* = cx + dy + s; the linear case is r = s = 0, a matrix product. A map T is linear when it preserves addition and scalar multiplication; the zero map passes, and so does differentiation of polynomials, proved in full.
2. **Every matrix map is linear** — T(x, y) = (ax + by, cx + dy) satisfies the two laws, proved from the definition; the shear T(x, y) = (x + 2y, y) slides a square into a parallelogram, with (0, 0) and (1, 0) fixed.
3. **First properties, proved** — T(0) = 0 and T(−v) = −T(v) fall out of the two laws, and linear maps preserve all linear combinations: T(Σ kᵢvᵢ) = Σ kᵢT(vᵢ). The same laws are the test that convicts a non-linear map.
4. **The five kinds** — monomorphism, epimorphism, isomorphism, endomorphism, automorphism, defined for linear maps.
5. **Kernel and image** — Im(T), everything T reaches; N(T), everything T sends to 0; both are vector spaces themselves. The book's claim that a basis maps to a basis of the image is taught corrected: the images of a basis always span Im(T), but they can fail to be independent, so they need not be a basis.
6. **Rank–nullity** — dim V = dim N(T) + dim Im(T): what a map crushes plus what it keeps fills the whole space, worked on the book's example with kernel {(x, −x)}; and rotations about the origin are linear, their formulas derived from the angle-sum identities.

## Add-on slots

- slot-linear-transformations-0 (IMAGE): a unit square on grid paper and, beside it, the same square sheared into a parallelogram by T(x, y) = (x + 2y, y), with the four corner images labelled (0, 0), (1, 0), (3, 1), (2, 1). What the student does: names which corners moved and which stayed, and says why the origin can never move under a linear map.
- slot-linear-transformations-1 (GIF, 1–2 s): a photograph sliding sideways into its shear — vertical lines staying vertical, horizontal lines tilting — freezing on the parallelogram. What the student does: points to a pair of points whose midpoint maps to the midpoint of the images, the addition law made visible.
- slot-linear-transformations-2 (IMAGE): the map T(x, y) = (x + y, x + y) drawn as a funnel: the whole plane collapsing onto the diagonal line y = x, with the kernel line x + y = 0 drawn dashed through the origin. What the student does: reads off dim N(T) = 1 and dim Im(T) = 1 and checks they add to dim ℝ² = 2.
