# EMF, internal resistance and terminal voltage of a source

## Do it first
Before you read: take a cell that has run a torch for a long time. A voltmeter across it, alone, reads nearly its full voltage — it looks healthy. Connect it to the torch lamp and the lamp glows weakly, and the same voltmeter now reads much less. The cell seemed to promise volts it could not deliver. Where did the missing volts go? Keep that question; this lesson answers it.

## Sub lesson 1 — EMF — the source's whole push

A source — a cell, a battery, a power supply — is a machine for giving energy to charge. Its **EMF** (electromotive force, written E) is the energy it gives to **each coulomb** of charge that passes through it:

**E = W ÷ Q** — energy given (joules) ÷ charge carried (coulombs), so EMF is measured in volts, joules per coulomb. A 1.5 V cell gives 1.5 joules to every coulomb it pushes round the circuit.

The name is a trap: EMF is not a force. It is an energy-per-charge — the source's whole push, counted in volts.

Here is how you measure it. Connect a voltmeter across the source with **no current being drawn**. The meter reads the EMF itself. Why? Because when no charge is flowing, nothing is being spent anywhere — the full push of the source stands across its terminals, waiting. Remember this open-circuit reading; the next parts explain why it is the only honest one.

## Sub lesson 2 — Internal resistance — the source's own resistance

No real source is a perfect push. The chemicals, plates and connections inside a cell resist the charge moving through them, just as a wire does. This resistance inside the source is its **internal resistance**, written r.

So the source's EMF is spent in **two places**, every time charge flows:

- **Inside the source**, pushing charge through r: the 'lost volts', **Ir**, wasted as heat inside the cell.
- **Outside the source**, pushing charge through the circuit's resistance R: **IR**, the useful part.

Energy bookkeeping gives the master equation: **E = IR + Ir**, and so the current everywhere in the loop is

**I = E ÷ (R + r)**

Work it once. A cell of EMF 1.5 V and internal resistance 0.5 Ω drives a lamp of resistance 2.5 Ω. Total resistance = 3.0 Ω, so I = 1.5 ÷ 3.0 = **0.5 A**. Lost inside: Ir = 0.5 × 0.5 = 0.25 V. Used outside: IR = 0.5 × 2.5 = 1.25 V. Check: 1.25 + 0.25 = 1.5 V — the whole EMF, accounted for.

This also explains old batteries. A battery 'goes flat' largely by its internal resistance **growing** with age and use: its EMF may still read well on a meter, but under load nearly all of it is lost inside, and the lamp starves. It explains danger too: short a source (R ≈ 0) and the current I = E ÷ r is limited only by that small r — large, hot and destructive.

## Sub lesson 3 — Terminal voltage — what the outside circuit actually gets

The voltage across the source's terminals **while it is working** is called the **terminal voltage**, V. It is the outside circuit's share of the EMF:

**V = E − Ir**

The harder you draw current, the bigger the lost volts, the lower the terminal voltage sags. At I = 0 it climbs back to the full EMF — the two facts you saw in Do it first, now explained.

This gives the classic school experiment for measuring E and r together. Vary the outside resistor, record pairs of terminal voltage V and current I, and plot V against I. Since V = E − Ir, the graph is a straight line falling with slope −r: the **intercept on the V axis is the EMF E**, and the **size of the slope is the internal resistance r**. One graph, both hidden numbers of the source.

Sources combine by the same rules. In **series** (positive to negative, aiding), EMFs add — two 1.5 V cells give 3.0 V — but so do internal resistances, so the whole battery has r = r₁ + r₂. In **parallel**, identical sources give the EMF of one but share the current, so each works less hard and the combination's effective internal resistance falls — the way to draw big currents without sagging.

## The key ideas

- **EMF** E is the energy a source gives each coulomb, E = W/Q, in volts; it is the voltmeter reading across the source when no current flows.
- Every real source has **internal resistance** r; the 'lost volts' Ir are spent inside the source and never reach the circuit.
- The loop obeys E = IR + Ir, so the current is **I = E/(R + r)**.
- **Terminal voltage** V = E − Ir sags as current rises; on a V–I graph the intercept is E and the slope's size is r.
- Series sources add EMFs and internal resistances; parallel identical sources share the load and sag less.

## Say it to your companion
Explain to your companion why the voltmeter lied about the old torch cell: where the EMF is spent when the lamp is on, what 'lost volts' means, and how one graph can measure both the EMF and the internal resistance. If your companion can work the 1.5 V example aloud, the lesson has landed.

## Do It Yourself
1. Measure a cell's EMF with a voltmeter alone, then read the terminal voltage with a lamp connected. Compute the lost volts and say where they went.
2. Do the V–I experiment with five different loads, plot your graph, extend the line to zero current, and report the cell's EMF and internal resistance from your own graph.
3. Predict, then test: two identical cells in series driving the same lamp — what happens to the current, and what happens to each cell's lost volts? Explain both from E = IR + Ir.
