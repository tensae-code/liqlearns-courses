# Electronic tuning — the varactor diode

## Do it first
Old radios tuned with a knob that physically turned interlocking metal plates — a variable capacitor you could see. A modern set tunes from a remote control across the room, silently, with nothing moving at all. The component that vanished the knob is a diode used backwards, as a capacitor steered by voltage. This lesson builds it from the junction up.

## Sub lesson 1 — A diode whose capacitance you can dial

Recall the p–n junction: at the join, mobile carriers clear out, leaving a depletion layer — a thin insulating region of uncovered fixed charges, with conducting p and n material on its two sides. Conductors separated by an insulator are a capacitor, so every junction has a capacitance set by that layer's width: C behaves as area ÷ width, exactly like a parallel-plate capacitor whose plate spacing is the depletion width.

Reverse-bias the junction and the applied voltage drags carriers further from the join: the depletion layer widens, the 'plates' move apart, and the capacitance falls — smoothly and predictably as the reverse voltage rises. Forward bias does the opposite (and soon conducts), so the device is used in reverse only. A diode manufactured to make this capacitance large, clean and well-controlled is a varactor (varicap) diode: a voltage-controlled capacitor in a two-legged package.

## Sub lesson 2 — Tuning an LC circuit by voltage

The tuned circuit of the resonance lesson answers at f = 1/(2π√(LC)). Put a varactor in place of the variable capacitor and C — and therefore f — follows the tuning voltage: raise the reverse bias, the depletion layer widens, C falls, and the resonant frequency climbs; lower the bias and the circuit tunes down the band. One DC voltage, set by a knob, a button or a processor, now does the travelling that meshing metal plates used to do.

The RF signal itself rides across the varactor too, so the varactor must stay reverse-biased through the whole signal swing — the standing bias is kept larger than the signal, or the junction would conduct on peaks and wreck the tuning. With that care, several varactors on one control voltage tune a receiver's several LC stages together, tracking in step — the electronic replacement for the old ganged capacitor's shared shaft.

## Sub lesson 3 — Electronic tuning at work — no moving parts

The gains are everything mechanical tuning could not do: no plates to bend, corrode or drift out of alignment; tuning by a voltage that a remote control, a preset button or an automatic frequency control (AFC) circuit can supply — the AFC senses a station drifting off-tune and nudges the varactor voltage to pull it back, a self-correcting loop impossible with a hand-turned knob. Channel presets are simply stored voltages; a scanning tuner sweeps a voltage ramp and stops where a station answers.

The same device serves beyond receivers: in voltage-controlled oscillators it sets the frequency of transmitters and synthesisers, and in parametric circuits its controlled capacitance does further tricks. The varactor is the junction's quiet second career — the diode that conducts nothing and tunes everything.

## The key ideas

- A reverse-biased p–n junction's depletion layer is an insulator between conducting regions — a capacitor whose plate spacing (and so capacitance) the reverse voltage controls: wider layer, smaller C.
- The varactor diode is built to exploit exactly this: a clean, sizeable voltage-variable capacitance, used in reverse bias only.
- In an LC circuit, varactor C makes the resonant frequency f = 1/(2π√(LC)) voltage-controlled: higher reverse voltage → smaller C → higher f.
- Electronic tuning enables remote control, stored preset voltages and AFC self-correction, with no moving parts — and stages gang together on one control voltage.

## Say it to your companion
Tell your companion the whole lesson in order, in your own words — start with the opening activity, then take each sub lesson in turn and finish with what it is used for. If your companion can repeat the main idea back to you, the lesson has landed.

## Do It Yourself
1. A varactor's reverse bias is increased. State what happens to (a) the depletion layer width, (b) the capacitance, (c) the resonant frequency of the LC circuit it tunes.
2. A receiver's tuning voltage is swept from 2 V to 9 V and the received frequency rises. Explain the whole chain from voltage to frequency, naming each link.
3. Why must the DC bias on a varactor exceed the peak of the RF signal across it? What fault appears on signal peaks if it does not?
