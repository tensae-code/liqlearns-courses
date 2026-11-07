# Hands-on — Monte Carlo and Simulation

The lesson manufactured chance on paper. Now run the factory yourself.

## The wheel by hand
Run Pakistan's generator with pencil only: seed 5, a = 13, b = 0, m = 16. Write each step's multiplication before its remainder: 5 → 65 → 1; 1 → 13; 13 → 169 → 9; 9 → 117 → 5. Stop when the seed returns and count the cycle's length (4). Then change only the seed to 3 and run again — same wheel, new starting point.

## Table tosses
Take any page of random digits (a book's table, or digits you generate with the wheel above, two at a time). Fix the rule first, in writing: even = heads, odd = tails, read left to right in pairs for two-coin tosses. Simulate 50 two-coin tosses and tally HH, HT, TH, TT. The mixed pairs together should land near the two pure pairs combined — compare with the real two-coin table you built in an earlier lesson.

## A Monte Carlo estimate
Estimate the probability that three coins show at least two heads, without listing outcomes: simulate 100 three-coin experiments from digits, count the successes, and report the frequency with its run length — "about 0.5, from 100 simulated experiments". Then double the run and watch the estimate steady, the Monte Carlo bargain in your own tally.

## The pea check
Shuffle a pack so that you can draw "genes" in pairs: agree that one suit stands for D and another for d, draw pairs with replacement 80 times, and tally DD, Dd, dd. The model (China's reading, pp.259–260) promises roughly 20, 40, 20, and about 60 dominant against 20 recessive — the ≈3:1. Write one sentence on how close your counts came, worded as a check of a model, not as a proof.
