# Hands-on — Linear Transformations

## Activity 1 — Shear the square (10 minutes)

Draw a unit square on squared paper with corners (0, 0), (1, 0), (1, 1), (0, 1). Apply the book's shear T(x, y) = (x + 2y, y) (printed p. 147) to each corner: you get (0, 0), (1, 0), (3, 1), (2, 1). Join them in order and shade the parallelogram. Which corners did not move, and why must (0, 0) be one of them for any linear map? Then test the addition law by hand: T((1, 0) + (0, 1)) against T(1, 0) + T(0, 1).

## Activity 2 — Linear or not? (15 minutes)

For each map, vote linear or not, then prove your vote with the book's two laws (printed p. 144) or with the T(0) = 0 test: (a) T(x, y) = (x + 1, y); (b) T(x, y) = (2x, 3y); (c) T(x) = x² on the reals; (d) D(p) = p′, differentiation, on polynomials — the book proves this one in full (printed pp. 144–145). (Answers: (a) not linear — it moves the origin; (b) linear — it is a matrix map; (c) not linear — T(1 + 1) = 4 but T(1) + T(1) = 2; (d) linear — sums and scalar multiples pass through the derivative.)

## Activity 3 — Crush and keep (15 minutes)

Take the book's rank–nullity example (printed pp. 153–154): T(x, y) = (x + y, x + y). Find the kernel by solving x + y = 0 — the line {(x, −x)}, dimension 1. Find the image: every output is a multiple of (1, 1), so the image is the diagonal line, dimension 1. Now count: 1 + 1 = 2 = dim ℝ², Sylvester's theorem checked by hand. Finish with the trap the lesson teaches corrected: the images of the basis (1, 0) and (0, 1) under this T are both (1, 1) — they span the image, but they are not a basis of it. Say in one sentence why not.
