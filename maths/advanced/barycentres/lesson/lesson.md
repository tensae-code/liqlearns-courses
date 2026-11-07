# Barycentres — the lesson

Course: Maths · Stage: Stage 12 — Advanced Mathematics · Lesson: Barycentres
Built from: Mauritania, Mathématiques 5AS série mathématiques (5AS-M), 5AS série D (5AS-D), 6AS séries M (6AS-M) and 6AS série C (6AS-C) — Laos, Grade 11 student book

## Do it first
Balance a ruler across one finger. It balances at its middle. Now tape a coin near one end and balance it again: your finger must move towards the coin. Two ends, one balance point — and the balance point answers to the weights. That answering point is this lesson's subject. Two school systems build a whole chapter on it: Mauritania gives the barycentre a chapter in four of its senior streams (5AS-M Ch.6, printed p.57; 5AS-D Ch.6, printed p.47; 6AS-M Ch.4, printed p.51; 6AS-C Ch.4, printed p.51), and Laos's Grade 11 book closes its geometry with a barycentres chapter (Ch.9, L33–L34, printed pp.249, 254).

## Then the explanation
**Two weighted points.** Give point A a weight α and point B a weight β (ordinary positive weights). Their **barycentre** is the point G on the line AB that balances them, defined by the vector condition

α·GA + β·GB = 0  (vectors GA and GB).

Laos's book teaches the barycentre of two points as its own lesson (Grade 11, Ch.9, L33, printed p.249). Read the condition as a tug of war: GA and GB point in opposite directions from G, and the weights make the two pulls cancel. Because the pulls must cancel, the heavier point gets the shorter arm: if β is the bigger weight, G sits closer to B, with GA/GB = β/α. With equal weights the condition gives GA = −GB: G is the **midpoint** of AB.

**Coordinates of the two-point barycentre.** From the vector condition, G divides AB in the ratio of the opposite weights, and in coordinates the formula is a weighted average:

G = (αA + βB)/(α + β),  coordinate by coordinate.

Example: A(0, 0) with weight 2, B(6, 0) with weight 1. Then G = ((2·0 + 1·6)/3, 0) = (2, 0) — two units from the heavier point A, four from B, and indeed 2 × GA = 2 × 2 = 4 = 1 × GB = 1 × 4. The weights enter BEFORE the averaging; a plain average of the coordinates is only correct when the weights are equal.

**A system of points.** Laos's second barycentre lesson extends the build to a system of points (Ch.9, L34, printed p.254): points A, B, C with weights α, β, γ have the barycentre G defined by

α·GA + β·GB + γ·GC = 0  (vectors) —

the formula printed on the Grade 11 book's own cover — with coordinates

x_G = (αx_A + βx_B + γx_C)/(α + β + γ),  and the same for y_G.

The pattern continues to any number of points: weight each position, add, divide by the total weight. Mauritania's 6AS-M book names its chapter exactly for this general case: "Barycentre d'un système de points pondérés" — barycentre of a system of weighted points (6AS-M, Ch.4, printed p.51).

**Grouping: associativity.** A system can be balanced in stages. Replace any two points by their own barycentre, carrying their combined weight, and the barycentre of the whole system does not change. So a three-point problem becomes two two-point problems: merge A and B into a point of weight α + β, then merge that point with C. The hands-on activity checks both routes to the same G — directly by the formula, and by grouping — the way the books' exercises drill it (Laos, Grade 11, L34, printed p.254).

**The centroid: equal weights.** Give a triangle's three vertices equal weights. Their barycentre is the triangle's **centroid**: the average of the three vertices, ((x_A + x_B + x_C)/3, (y_A + y_B + y_C)/3), which is the point where the three medians meet — each median joins a vertex to the midpoint of the opposite side, and the midpoint is itself the two-point barycentre with equal weights, so the centroid is grouping applied to a triangle. For A(0, 0), B(6, 0), C(0, 6) the centroid is (2, 2). It is also the physical balance point: a flat cardboard triangle balances flat on a fingertip placed at its centroid. In physics language the barycentre of weighted points is their **centre of mass**, with the weights as masses — the same point your ruler found in Do it first.

Tip — from us, not from the books. Whenever a barycentre answer looks wrong, check the direction first: G must sit nearer the heavier points. If your computed G drifts towards a light point, the weights have been swapped — the most common error in this whole lesson.

## Say it to your companion
State the two-point condition α·GA + β·GB = 0 and explain, from it, why G divides AB in the ratio GA/GB = β/α — the opposite weight. Then your companion gives you three points with weights; compute their barycentre by the formula, then again by grouping, and show both routes land on the same point.

## Do It Yourself
1. Find the barycentre of A(1, 2) with weight 3 and B(7, 8) with weight 1, and check it lies nearer A (Laos, Grade 11, L33, printed p.249).
2. Weights 1 and 4 sit at 0 and 10 on a number line. Find the barycentre and verify α·GA + β·GB = 0 in lengths.
3. Find the barycentre of A(0, 0) weight 1, B(4, 0) weight 2, C(0, 4) weight 1 by the coordinate formula, then by grouping A with B first (Laos, Grade 11, L34, printed p.254).
4. Find the centroid of the triangle (0, 0), (9, 0), (0, 3), and the midpoint of the side joining (9, 0) and (0, 3); check the centroid lies on the median from (0, 0).
5. Name the four Mauritania streams that give the barycentre its own chapter, with their chapter pages.
