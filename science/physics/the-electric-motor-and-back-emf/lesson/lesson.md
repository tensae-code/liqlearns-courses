# The electric motor and back EMF

## Do it first
A small DC motor sits still with its shaft held fast. Connect it: the current meter leaps high and the motor hums and heats. Release the shaft — it spins up, and the current falls to a fraction, though the supply voltage never changed. Something inside the spinning motor is pushing back against the battery. This lesson names it.

## Sub lesson 1 — The motor — a coil in a field turns

Feed current to a coil free to rotate between magnet poles. Each side of the coil is a current-carrying conductor in a field, so each feels a force F = BIL — the two sides are pushed in opposite directions, forming a couple that torques the coil round. When the coil passes the vertical, a split-ring commutator reverses its current, so the torque always drives the same way round: continuous rotation from a steady supply. That is the DC motor — the dynamo run backwards, electricity in, motion out.

The torque is greatest when the coil's plane lies parallel to the field (its sides cutting the field at the full rate of the geometry) and the working strength grows with current, field, turns and coil area. A motor is rated by the mechanical power it delivers, torque × angular speed, against the electrical power it draws.

## Sub lesson 2 — Back EMF — the spinning motor becomes a generator

But the coil is now a loop of wire rotating in a magnetic field — precisely the arrangement of the AC generator. Its flux changes continuously, so an EMF is induced in the coil while it motors. By Lenz's law that EMF opposes the supply driving it: the back EMF, E′. It grows in proportion to the speed of rotation, because a faster spin changes the flux faster.

The current in the motor is therefore not V/R but I = (V − E′)/R, where R is the small resistance of the windings. At running speed E′ rises to just below V, and the current settles to the modest value the load demands. Increase the load and the motor slows a fraction, E′ dips, and the current automatically rises to meet the new load — the back EMF makes the motor self-regulating.

## Sub lesson 3 — Starting current, running current and the starter

At the instant of switch-on the motor is still: no rotation, no back EMF, so the starting current is I_start = V/R — with R a fraction of an ohm, that current can be ten or twenty times the running current, enough to burn the windings or blow the fuse if it lasted. Large motors are started through a starter resistance in series, cut out step by step as the motor gathers speed and builds its own back EMF to take over the limiting.

The same law reads the dangers in reverse: jam the shaft (a stalled drill, a seized pump) and E′ collapses to zero while the supply stays — the current climbs back to V/R and the motor cooks in its own current. Back EMF is thus both governor and witness: its size reports the motor's speed, and its absence is the emergency.

## The key ideas

- The motor: opposite forces on the two sides of a current-carrying coil in a field give a turning couple; the commutator reverses the current each half-turn to keep the torque one-way.
- A spinning motor coil is also a generator: it induces a back EMF E′ opposing the supply, proportional to its speed.
- The motor current is I = (V − E′)/R — at full speed E′ nearly equals V and the current is small; the motor self-regulates its current to its load.
- At start (or stalled) E′ = 0 and the current is V/R, many times the running value — hence starter resistances and stalled-motor burnout.

## Say it to your companion
Tell your companion the whole lesson in order, in your own words — start with the opening activity, then take each sub lesson in turn and finish with what it is used for. If your companion can repeat the main idea back to you, the lesson has landed.

## Do It Yourself
1. A 12 V motor has winding resistance 0.5 Ω. Calculate its starting current, and its running current when spinning with a back EMF of 10.5 V. Comment on the ratio.
2. A motor driving a lift slows slightly as the lift's load increases, yet it does not stall; instead its current rises. Explain the chain, step by step, through the back EMF.
3. Why is a starter resistance only needed during the first seconds of a large motor's run? Describe what replaces it as the limiting agent once the motor is up to speed.
