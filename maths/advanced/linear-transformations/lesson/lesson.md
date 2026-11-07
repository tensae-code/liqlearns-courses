# Linear Transformations

## You do it first

A photo app lets you drag the top edge of a picture sideways while the bottom edge stays put. The picture slants; nothing tears; straight lines stay straight, and the grid lines that were parallel stay parallel.

That slant is a **linear transformation** doing its work. This lesson is about the maps behind it: which maps count as linear, what they are allowed to do, and the two sets — kernel and image — that expose exactly what a map crushes and what it keeps.

## What "linear" means

Venezuela's Grade 11 book starts from the photograph. A general change of the picture is affine: x* = ax + by + r, y* = cx + dy + s. When the shifts vanish — r = s = 0 — the map is **linear**, and it is exactly a matrix product. A map T between vector spaces is a **linear transformation** when it keeps both promises:

- **T(u + v) = T(u) + T(v)** — transforming a sum gives the sum of the transforms;
- **T(ku) = kT(u)** — transforming a stretched vector gives the stretched transform.

The zero map, T(v) = 0 for every v, passes both tests. So does a map from a different world: differentiation of polynomials, D(p) = p′, which the book proves linear in full, for sums and for scalar multiples. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 143–145.)

## Every matrix map is linear — and the shear

Take any 2 × 2 matrix map, T(x, y) = (ax + by, cx + dy). The book proves from the definition that it satisfies both promises — every matrix map is linear. Its running example is the **horizontal shear** T(x, y) = (x + 2y, y), applied to the square of a photograph: the corners (0, 0), (1, 0), (1, 1), (0, 1) go to (0, 0), (1, 0), (3, 1), (2, 1), and (0, 0) and (1, 0) are fixed points — they do not move at all. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 145–147.)

## First properties — proved, not quoted

Two facts fall straight out of the promises:

- **T(0) = 0.** Because T(0) = T(0 + 0) = T(0) + T(0), and the only vector equal to its own double is 0.
- **T(−v) = −T(v).** Because 0 = T(0) = T(v + (−v)) = T(v) + T(−v).

And the promises extend to every combination at once: **T(Σ kᵢvᵢ) = Σ kᵢT(vᵢ)** — a linear map preserves all linear combinations. These are also the detective's tools: a map that moves the origin, like the shift (x, y) → (x + 1, y), is convicted at once — it is affine, not linear. The book also disproves linearity by reading graphs: if |u| = ½|v| but |T(u)| = ⅔|T(v)|, the scaling promise T(u) = ½T(v) has failed. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 147–150.)

## The five kinds

Linear maps are sorted by how they behave: a **monomorphism** loses nothing (distinct inputs keep distinct outputs), an **epimorphism** reaches everything, an **isomorphism** does both, an **endomorphism** maps a space into itself, and an **automorphism** is an isomorphism of a space with itself. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 149.)

## Kernel and image

Two sets describe any linear map completely:

- the **image** Im(T): every vector T actually reaches;
- the **kernel** N(T): every vector T sends to 0, found by solving a linear system.

The kernel of the shear is {(0, 0)} — it crushes nothing real. The kernel of the zero map is the whole space V. And both sets are **vector spaces in their own right** — kernel and image are subspaces, never arbitrary sets. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed p. 152.)

One claim in the book must be taught corrected. The book says T sends a basis of V to a basis of Im(T). That is too strong: the images of a basis always **span** Im(T) — the book's own argument proves that much — but they can fail to be independent. Counterexample: under T(x, y) = (x + y, x + y), the basis vectors (1, 0) and (0, 1) both map to (1, 1); the pair {(1, 1), (1, 1)} spans the image but is no basis of it. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 150–152 — claim taught corrected.)

## Rank–nullity: the count that balances

**Sylvester's theorem (rank–nullity): dim V = dim N(T) + dim Im(T).** What a map crushes, plus what it keeps, is everything it was given. The book works it on a map whose kernel is the line {(x, −x)}: kernel dimension 1, image dimension 1, and 1 + 1 = 2 = dim ℝ². (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 153–154.)

The chapter closes by bringing an old friend into the family: a **rotation about the origin** is linear, with T(x₁, y₁) = (x₁ cos θ − y₁ sen θ, x₁ sen θ + y₁ cos θ), derived from the angle-sum formulas for sine and cosine. (Venezuela, *La Matemática y el Vivir Bien* (Grade 11), printed pp. 154–155.)

## Do it yourself

1. Prove T(0) = 0 from the two promises, in at most three lines.
2. Apply the shear T(x, y) = (x + 2y, y) to all four corners of the unit square and sketch what the square becomes.
3. Decide, with a reason each time, whether these are linear: (a) T(x, y) = (x + 1, y); (b) T(x, y) = (2x, 3y); (c) T(x) = x².
4. For T(x, y) = (x + y, x + y): find the kernel, find the image, and verify rank–nullity by counting dimensions.
5. The book claims a basis maps to a basis of the image. Use question 4's map to explain — in your own words — what is wrong with the claim and what the true statement is.
