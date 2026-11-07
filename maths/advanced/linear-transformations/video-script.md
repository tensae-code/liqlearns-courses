# Video script — Linear Transformations

Super-simple voice. The tutor talks; a square on grid paper stays on screen, and it bends, slides and collapses as each map is named.

---

Take a photograph and slide its top edge sideways, like pushing a deck of cards. The bottom stays. The sides tilt. That slide is called a shear — and it is our first linear transformation.

Linear sounds grand. It means two small promises. Promise one: the map respects adding — transform the sum, and you get the sum of the transforms. Promise two: it respects stretching — transform a stretched vector, and you get the stretched transform. A map that keeps both promises is linear. A map that breaks either one is not.

Here is a map that breaks them: shift everything one step right. It moves the origin — and a linear map can never do that. Zero must go to zero; the book proves it from the two promises in two lines. Shifting is affine, a cousin, but it is not linear.

Now the two sets that tell you what a map really does. The kernel: everything the map crushes to zero. The image: everything the map can reach. For the shear, the kernel is just the origin — nothing real is crushed. For the map that sends (x, y) to (x + y, x + y), a whole line is crushed — every point with x + y = 0 — and the image is a single line too, the diagonal.

And here is the beautiful count, Sylvester's theorem: the dimension you start with is the dimension crushed plus the dimension kept. Kernel plus image equals the whole space. In that example: 1 + 1 = 2. Nothing is lost from the count, even when the map collapses the plane onto a line.

One last map: turn the plane around the origin, a rotation. The book derives its formula from the angle-sum identities you already know — and it is linear, like every map a matrix can write.

Two promises. A kernel. An image. And a count that always balances. That is a linear transformation.
