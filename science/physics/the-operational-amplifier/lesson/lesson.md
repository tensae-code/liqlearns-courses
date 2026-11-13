# The operational amplifier

## Do it first
If a trainer board or simulator is available, build the inverting amplifier with Rin = 10 kΩ and Rf = 100 kΩ and verify the −10 gain and the inversion on an oscilloscope or meter; then rewire as a comparator with an LDR divider on one input and watch the output snap as you shade the LDR — the night switch, working. — begin with the hands-on opening in hands-on.md before reading on. This lesson is the story of that activity.

## Sub lesson 1 — Two inputs, one enormous gain

The op-amp has inverting (−) and non-inverting (+) inputs and amplifies their difference by an open-loop gain of 10⁵ or more. Alone, that gain is unusable — the output slams to a supply rail for a whisper of difference — which is exactly what the comparator exploits, and why amplifiers use feedback to trade gain for control.

## Sub lesson 2 — Virtual earth and the inverting amplifier

Feed the output back to the − input and the amp drives that input to match the + input: with + earthed, the − input becomes a virtual earth — held at 0 V, drawing no current. An input resistor and feedback resistor then set the gain exactly: gain = −Rf/Rin, the minus sign marking the inversion. The amplifier's precision comes from two resistors, not from the chip's wild gain.

## Sub lesson 3 — Non-inverting amplifier and comparator

Feed the signal to + instead and feedback to −, and the gain is 1 + Rf/Rin, always positive. Remove feedback altogether and the same chip is a comparator: its output snaps high or low as the inputs cross — the night switch in which an LDR divider's crossing turns on a lamp is PTB's named circuit, one chip doing both trades.

## The key ideas

- The op-amp has inverting (−) and non-inverting (+) inputs and amplifies their difference by an open-loop gain of 10⁵ or more.
- Feed the output back to the − input and the amp drives that input to match the + input: with + earthed, the − input becomes a virtual earth — held at 0 V, drawing no current.
- Feed the signal to + instead and feedback to −, and the gain is 1 + Rf/Rin, always positive.

## Say it to your companion
Tell your companion the lesson's one thing in your own words: the operational amplifier is a high-gain difference amplifier on a chip: it amplifies the difference between its two inputs so enormously that, tamed by feedback, it becomes a precision building block — inverting and non-inverting amplifiers, and the comparator that switches at a threshold. If your companion can work the Do It Yourself items without looking back, the lesson has landed.

## Do It Yourself
1. Why is an op-amp's open-loop gain unusable for ordinary amplification?
2. Rin = 4.7 kΩ, Rf = 47 kΩ in an inverting amplifier. Find the gain.
3. A non-inverting amplifier needs a gain of 6. What ratio Rf/Rin is required?
