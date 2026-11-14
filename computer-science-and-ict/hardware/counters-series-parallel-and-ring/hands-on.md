# Hands-on — Counters — Series, Parallel and Ring

The lesson with your hands and your feet, not only your eyes.

## Count on paper
Write the complete state table of a 4-bit series counter, pulses 0 to 17, as four-bit rows. Mark the pulse where it wraps to 0000. Then circle every state where more than one bit changes between one pulse and the next — those are the states a ripple counter passes through 'wrongly' for an instant, and your circles show why.

## Ring it
Draw a 5-stage ring counter as five boxes in a circle holding 10000. Write the next five states, one per pulse. Now answer as the machine: an action must run on the third pulse — which single output wire does it watch? Say in one line why no decoder is needed.

## In the simulator
In TINA or Circuit Wizard, build or select a 3-bit ripple counter and pulse it slowly sixteen times, recording the states. Then run it fast (if the tool allows) and note the ripple in the display. Locate a synchronous counter in the library and repeat: same sequence — the difference is only in how the stages change together.
