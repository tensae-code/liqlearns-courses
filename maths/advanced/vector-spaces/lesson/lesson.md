# Vector Spaces

## You do it first

Consider the set of all vectors (x, y, z) in R³ with x + y + z = 0 — a plane through the origin. Add two of its vectors: do you stay in the set? Multiply one by 7: still in? Now do the same for the plane x + y + z = 1, which misses the origin.

That one difference — staying closed, or escaping — is the seed of this whole lesson, built from Rwanda's Senior Five and Senior Six **Advanced** books together: Senior Five builds the theory, Senior Six works it harder. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 180–196; Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 6, printed pp. 331–344.)

## Sub lesson 1 — Subspaces

## R³ as a vector space, and the subspace test

R³, with ordinary vector addition and scalar multiplication, is a **vector space**. A non-empty subset W of it is a **subspace** if it is itself closed under the two operations:

- for all u, v in W, u + v is in W;
- for all u in W and every scalar k, ku is in W.

Closure forces the zero vector into W (take k = 0), so a set missing the origin — like the plane x + y + z = 1 above — fails at once. The plane x + y + z = 0 passes: sums and scalar multiples of its vectors keep the coordinate sum at 0. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 180–186.)

## Intersections of subspaces

The **intersection** W₁ ∩ W₂ of two subspaces is always a subspace: any two of its vectors lie in both W₁ and W₂, so their sum and scalar multiples lie in both, hence in the intersection. Senior Six's working method is concrete: a vector is in the intersection exactly when it satisfies **both** sets of conditions, so solve them as one system. For F: x + y + z = 0 and G: x − y = 0, the system gives y = x and z = −2x, so

    F ∩ G = {(t, t, −2t) : t real} — a line through the origin, of dimension 1.

Reading the **dimension of the intersection** off the solution set — one free parameter, dimension 1 — is Senior Six's next step. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 186–188; Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 6, printed pp. 331–339.)

## A warning about unions — from the teacher's guides

The union behaves oppositely. W₁ ∪ W₂ is a subspace **if and only if one contains the other**: W₁ ⊆ W₂ or W₂ ⊆ W₁. Take two different lines through the origin: a vector from each line adds to a vector on neither line, so the union is not closed and not a subspace. This criterion is stated in both teacher's guides' Unit 6 summaries and in neither Learner's Book — guide evidence, taught here as the guides state it. (Rwanda, Advanced Mathematics, Teacher's Guide, Senior Five, Unit 6, printed p. 97; Rwanda, Advanced Mathematics, Teacher's Guide, Senior Six, Unit 6, printed p. 292.)

## Sub lesson 2 — Sums and Dimensions

## Sums of subspaces, and the Grassmann formula

The **sum** F + G is the set of all u + v with u in F and v in G — and it is the **smallest subspace containing both** F and G: it is a subspace, it contains each of them (take the other summand as 0), and any subspace containing both must contain every such sum. Its size is counted by the **Grassmann formula**:

    dim(F + G) = dim F + dim G − dim(F ∩ G)

For the F and G above: dim(F + G) = 2 + 2 − 1 = 3, so F + G is all of R³. The intersection term is the correction for double-counting what the two spaces share. Senior Six states the same formula after its deeper work on intersections. (One of Senior Six's worked intersection examples is taught corrected in this lesson's sources: the book solves a different system from the one it sets; the stated set's correct solution is used wherever the example's shape appears here.) (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 188–190; Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 6, printed pp. 339–343.)

## Direct sums and complementary subspaces

If F ∩ G = {0}, the sum is called a **direct sum**, written F ⊕ G, and its defining gift is uniqueness: every vector of F ⊕ G is written as u + v with u in F, v in G in **exactly one way** (two writings would differ by a non-zero vector in the intersection). Subspaces F and G are **complementary (supplementary)** when the whole space is their direct sum, E = F ⊕ G — equivalently dim F + dim G = dim E with F ∩ G = {0}. Every subspace has complements, though rarely just one. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 188–190; Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 6, printed pp. 343–344.)

## Sub lesson 3 — Basis and Coordinates

## Linear combinations and span

A **linear combination** of vectors u₁, …, uₙ is anything of the form a₁u₁ + … + aₙuₙ with scalar coefficients. The set of *all* such combinations is the **span** of the set — always a subspace, and the smallest subspace containing all the uᵢ. Asking "is w in the span?" is asking "can w be built as a combination?" — a system of equations in the coefficients. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 190–192.)

## Independence and dependence

Vectors are **linearly independent** if the only combination giving 0 is the trivial one with every coefficient 0 — equivalently, no vector in the set is a combination of the others. Otherwise they are **dependent**. In R³, three vectors are independent exactly when their determinant is non-zero. Example (taught corrected — the book's printed determinant for these vectors is −10; recomputed, it is −8, and the conclusion is unchanged): u = (1, 2, 0), v = (0, −1, 3), w = (−1, 0, 2) have determinant −8 ≠ 0, so they are independent. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 192–194.)

## Basis, dimension and coordinate vectors

A **basis** of a space is a set that is both independent and spanning. Every basis of a given space has the same number of vectors; that number is the space's **dimension** — R³ has dimension 3, a plane through the origin 2, a line through the origin 1, {0} alone 0. Relative to a basis B = {e₁, e₂, e₃}, every vector u is one unique combination u = a₁e₁ + a₂e₂ + a₃e₃, and (a₁, a₂, a₃) is u's **coordinate vector** relative to B — uniqueness is exactly what makes coordinates usable as a name for the vector. (Rwanda, Advanced Mathematics, Learner's Book, Senior Five, Unit 6, printed pp. 194–196.)

> **Tip — from us, not from the books:** when a problem hands you two subspaces, compute the intersection first, every time. Its dimension feeds Grassmann, its being {0} or not settles directness, and solving its system is the one piece of honest algebra everything else hangs on.

## Say it to your companion

Explain to your companion why an intersection of subspaces is always a subspace but a union almost never is — with the two-lines picture. Then have them explain what Grassmann's formula subtracts, and why exactly once.

## Do It Yourself

1. Test for a subspace: (a) {(x, y, z) : z = 0} (b) {(x, y, z) : x ≥ 0} (c) {(x, y, z) : x = y = z}.
2. Let F: z = 0 and G: x + y + z = 0 in R³. Find F ∩ G, its dimension, and dim(F + G). Is the sum direct?
3. Are (1, 0, 1), (1, 1, 0) and (0, 1, 1) independent in R³? Then write (1, 2, 1) as a combination of them.
