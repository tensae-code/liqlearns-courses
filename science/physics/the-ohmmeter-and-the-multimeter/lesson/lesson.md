# The ohmmeter and the multimeter

## Do it first
A resistor lies on the bench with its colour bands faded. The voltmeter-ammeter method works but needs a circuit, a supply and a calculation. The meter in the drawer does it in two seconds: touch the probes, read the scale. This lesson opens that meter up — why its ohms scale runs backwards, why it must be re-zeroed on every range, and how it grows into the multimeter.

## Sub lesson 1 — Measuring resistance directly — the ohmmeter

An ohmmeter is a moving-coil meter movement, its own internal battery, a variable zero-adjust resistor and the unknown resistance, all in series. Connected across the unknown resistor, the battery drives a current I = E/(R_internal + R_unknown) through the coil: the bigger the unknown resistance, the smaller the current and the smaller the deflection. The pointer's position therefore prices the resistance directly — no separate supply, no calculation.

That series arrangement dictates the scale's strange character. With the probes shorted (R_unknown = 0) the current is greatest and the pointer swings to full deflection — so zero ohms sits at the RIGHT-hand end, where a normal meter reads maximum. With the probes apart (R_unknown = ∞) no current flows and the pointer rests at the left: infinity at the left. The ohms scale runs backwards compared with the current and voltage scales printed on the same dial.

## Sub lesson 2 — Zero adjustment and the crowded scale

Between those ends the scale is badly non-linear: equal steps of resistance crowd together toward the high end, because deflection follows 1/(R_internal + R_unknown), not R_unknown itself. Readings are trustworthy only near the centre of the scale, so the ohmmeter offers ranges (×1, ×10, ×100, ×1k) that swap the internal resistance and move the unknown's value toward mid-scale.

Every range change — and every ageing of the internal battery — shifts the full-deflection point, so the ritual is compulsory: short the probes, turn the zero-ohms adjuster until the pointer sits exactly on 0 Ω, then measure. Two further rules protect both meter and truth: never connect an ohmmeter to a live circuit (its battery and movement are not built for outside voltages), and never trust a reading taken on a component still wired into a circuit, where parallel paths join the unknown and falsify the value.

## Sub lesson 3 — The multimeter — one instrument, many jobs

The multimeter (avometer) packages the three instruments of the electricity course in one case: a voltmeter (high resistance, in parallel), an ammeter (low resistance, in series) and the ohmmeter, in AC and DC versions of the ranges, selected by one rotary switch. The same meter movement serves them all — shunts make the current ranges, multipliers make the voltage ranges, the internal battery powers the ohms ranges.

Its digital descendant replaces the movement with electronics: it samples the quantity and shows digits, chooses or offers ranges the same way, and keeps the same working rules — right function, right range (start high when unsure), ohmmeter only on dead, disconnected components. One box, every measurement of the course: that is why the multimeter, not any single instrument, is the bench standard.

## The key ideas

- The ohmmeter puts its own battery in series with the meter movement and the unknown resistor: deflection falls as resistance rises.
- Its scale is reversed (0 Ω at full deflection, right; ∞ at rest, left) and non-linear — accurate only near mid-scale, so ranges are chosen to put the reading there.
- Short the probes and re-zero with the zero-ohms adjuster on every range and as the battery ages; never measure a live circuit or a component still wired in.
- The multimeter unites voltmeter, ammeter and ohmmeter (AC and DC) behind one selector switch, analogue or digital.

## Say it to your companion
Tell your companion the whole lesson in order, in your own words — start with the opening activity, then take each sub lesson in turn and finish with what it is used for. If your companion can repeat the main idea back to you, the lesson has landed.

## Do It Yourself
1. An ohmmeter's probes are shorted and the pointer will not reach 0 Ω even with the adjuster at its limit. What has happened inside the instrument, and what is the remedy?
2. A 470 Ω resistor reads near the crowded left end of the ×1 range's scale but near mid-scale on the ×10 range. Explain which reading to trust and why the scale crowds there.
3. A student measures a resistor inside a switched-off circuit and gets 100 Ω; removed from the circuit it measures 220 Ω. Explain the discrepancy and state the rule it teaches.
