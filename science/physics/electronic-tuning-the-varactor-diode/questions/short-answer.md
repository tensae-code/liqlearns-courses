# Electronic tuning — the varactor diode — short answer

Answer in a sentence or two.

**1.** (Sub lesson 1) Explain why a junction's capacitance falls as reverse bias rises, using the plate-capacitor picture.
**Answer: Reverse bias pulls mobile carriers away from the junction, widening the depletion layer. In the plate picture C ≈ (constant × area)/separation: the conducting p and n regions are the plates and the depletion width is their separation — wider separation means smaller capacitance, so C falls smoothly as the bias rises.**

**2.** (Sub lesson 2) A varactor-tuned circuit must receive a lower frequency. State the change to make at the tuning voltage and the chain that follows.
**Answer: Reduce the reverse bias. The depletion layer narrows, so the varactor's capacitance rises, and f = 1/(2π√(LC)) falls as C grows — the circuit's resonance moves down to the wanted station. Every link is electronic; nothing mechanical moves.**

**3.** (Sub lesson 3) Why is the varactor's standing bias kept larger than the RF signal swing across it?
**Answer: The tuning action needs the junction reverse-biased at every instant. If a signal peak exceeded the bias, the junction would swing into forward bias on peaks, conduct, and clip the signal while the capacitance lurched — detuning and distorting the stage. Bias headroom keeps the device a pure capacitor throughout.**

**4.** (Sub lesson 3) Name two advantages electronic tuning has over a mechanically ganged variable capacitor, and the mechanism behind each.
**Answer: (Any two:) remote/preset control — tuning is a voltage, which buttons, memories and processors can supply; AFC self-correction — a feedback circuit can steer the voltage continuously; no wear or misalignment — nothing moves; perfect ganging — one voltage drives all stages' varactors together, replacing a shared mechanical shaft.**
