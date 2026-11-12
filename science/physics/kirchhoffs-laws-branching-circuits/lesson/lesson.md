# Kirchhoff's laws — branching circuits

## Do it first
Before you read: two batteries of different sizes feed one branching network of resistors, with wires splitting and rejoining like a river delta. Ohm's law alone cannot price the current in each branch — the branches share junctions and loops. What two conservation rules, one about charge and one about energy, are strong enough? Decide here.

## Sub lesson 1 — The junction rule — charge is conserved

At any junction, current cannot pile up or vanish: the sum of currents entering equals the sum leaving. If 3 A and 2 A flow into a junction and one branch carries 4 A out, the remaining branch carries exactly 1 A out. This is Kirchhoff's first law, and it is charge conservation wearing a circuit's clothes. It also fixes directions: assume a direction for every branch current, and a negative answer at the end simply means the current really runs the other way.

## Sub lesson 2 — The loop rule — energy is conserved

Walk round any closed loop and the books must balance: rises across sources (from − to + inside a source, +E) and drops across resistors (in the current's direction, −IR) sum to zero. This is Kirchhoff's second law — energy conservation per coulomb. The EMF strand it stands on — a source's EMF, its internal resistance and its terminal voltage — is stocked in the lesson EMF, internal resistance and terminal voltage; this lesson takes the loop rule itself as its tool. Sign discipline is the whole craft: pick a walk direction, give every gain and drop its sign by the rule, and never change your mind mid-loop.

## Sub lesson 3 — Solving a branching circuit

The method: label every branch current (junction rule cuts the unknowns down), write one loop equation for each independent loop, solve the simultaneous equations, then check — junction sums at every node, loop sums round a loop you did not use. Worked shape: a 12 V source across two parallel branches of 2 Ω and 4 Ω gives branch currents 6 A and 3 A by the junction-and-loop pair, total 9 A from the source. When a second source enters a loop, its EMF enters with its sign — that is the case series–parallel rules could never touch, and Kirchhoff's laws close it.

## The key ideas

- Junction rule: currents in = currents out at every junction (charge conserved)
- Loop rule: gains and drops round any closed loop sum to zero (energy conserved)
- Method: label branch currents, junction first, one equation per independent loop, then check

## Say it to your companion
Tell your companion: Junction rule: currents in = currents out at every junction (charge conserved); Loop rule: gains and drops round any closed loop sum to zero (energy conserved); Method: label branch currents, junction first, one equation per independent loop, then check. If your companion can work the Do It Yourself tasks without looking back, the lesson has landed.

## Do It Yourself
1. Currents of 5 A and 1.5 A enter a junction; one branch leaves with 4 A. What does the other leaving branch carry?
2. A loop contains a 9 V source (rise) and two resistors dropping 4 V and 5 V. Verify the loop rule, writing the sum out in full.
3. A 12 V source feeds two parallel branches, 3 Ω and 6 Ω. Find each branch current and the total current the source supplies.
