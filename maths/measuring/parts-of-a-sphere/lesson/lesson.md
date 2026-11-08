# Parts of a Sphere

## You do it first

Slice the top off an orange with one straight cut. You are holding two pieces: the whole ball's little cap, and the rest. Now make a second cut, parallel to the first, lower down. The slice trapped between the two cuts is a third kind of piece. Three pieces, three shapes — do any of them have names? And if I gave you the orange's radius and the height of the cap, could you tell me the cap's volume without filling it with water?

Hold your answer. By the end of this lesson you will have the names, and the formulas, for all three pieces — from the one school book in the library that teaches them.

## Sub lesson 1 — Parts of a Sphere — the Spherical Segment

## The spherical segment

Cut a ball with one plane. The part cut off is a **spherical segment**. Its one measurement, besides the ball's radius R, is its **height** H — the thickness of the slice, from the cutting plane to the top of the ball. Tajikistan's Grade 11 geometry book derives its volume with the integral formula it uses for all solids of revolution, spinning the circle's arc around the axis and adding up the discs:

**V = πH²(R − H/3)** (Tajikistan, *Геометрия* (Grade 11), printed p. 124.)

## Sub lesson 2 — Parts of a Sphere — the Spherical Layer

## The spherical layer

Cut the ball with **two** parallel planes, and keep the part between them: a **spherical layer** (also called a zone solid). Its two flat faces are circles of radii R₁ and R₂, and the distance between the planes is its height H. The book points out that a layer is what is left of one segment when a smaller segment is removed — its volume is a **difference of two segment volumes** — and then states the closed formula without derivation (we keep that honesty: the book says "it can be shown"):

**V = (πH/6)(H² + 3R₁² + 3R₂²)** (Tajikistan, *Геометрия* (Grade 11), printed p. 125.)

## Sub lesson 3 — Parts of a Sphere — the Spherical Sector

## The spherical sector

Now join the segment to the centre. A **spherical sector** is a segment together with the cone whose apex is the ball's centre and whose base is the segment's flat face — added when the segment is smaller than a hemisphere, subtracted when it is larger. Its volume is stated in the book:

**V = (2/3)πR²H** (Tajikistan, *Геометрия* (Grade 11), printed p. 125.)

The book works it once, beautifully: rotate a circular sector of 120° and radius R about the diameter that bisects it. The surface it sweeps is a sphere, and the solid it sweeps is a spherical sector whose cap height is H = R − R cos 60° = R/2. So V = (2/3)πR² · (R/2) = **πR³/3**. (Tajikistan, *Геометрия* (Grade 11), printed p. 125.)

## Sub lesson 4 — Parts of a Sphere — Areas of the Parts

## Areas of the parts

The curved surfaces of the parts have formulas too — all three stated in the book **without derivation**, and we say so rather than dress them up:

- the **cap** (the segment's curved surface): **S = 2πRH**
- the **zone** (the layer's curved surface, not counting its two flat base discs): **S = 2πRH** — the same form; a zone's area depends only on the ball's radius and the layer's height, not on where the layer sits
- the **sector's** surface: **S = πR(2H + r)**, where r is the radius of the segment's base circle

The book's worked problem assembles a whole answer from these: the smaller segment cut from a sphere of radius 5 cm by a plane at distance 3 cm from the centre. The cap height is H = 5 − 3 = 2 cm; the cut's circle has radius r = √(5² − 3²) = 4 cm. Curved cap: 2πRH = 2π · 5 · 2 = 20π cm². Flat base disc: πr² = 16π cm². Total area of the segment: **36π cm²**. (Tajikistan, *Геометрия* (Grade 11), printed p. 129.)

## Do it yourself

1. A ball of radius 5 cm is cut by a plane 3 cm from the centre, as in the book's problem. Find the volume of the smaller segment. (H = 2, so V = πH²(R − H/3) = π · 4 · (5 − 2/3) = 52π/3 cm³.)
2. A spherical sector has radius R = 6 cm and cap height H = 3 cm. Find its volume. (V = (2/3)πR²H = (2/3)π · 36 · 3 = 72π cm³.)
3. Two zones are cut from the same ball, one near the top and one around the middle, and both have height 2 cm. Which has the larger curved surface area? (Neither — a zone's area is 2πRH, depending only on R and H, so they are equal. Both statements are the book's, printed p. 129, stated there without derivation.)
4. Why is a spherical layer's volume a difference of two segment volumes? (The layer is what remains of the bigger segment — the one reaching down to the lower plane — when the smaller segment above the upper plane is taken away; that is how the book introduces its formula, printed p. 125.)
