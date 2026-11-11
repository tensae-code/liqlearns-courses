# Algorithmic Thinking

You do it, we guide you. Keep a short list of numbers beside
you through this whole lesson — a list of seven or eight, in a
messy order — you will be sorting it, searching it, and
growing a second one by chance.

## Sub lesson 1 — Algorithms and Flowcharts

An **algorithm** is a set of steps so exact that anyone — or
anything — following them gets the same answer, every time.
It is not a vague idea ("divide it somehow"). It is a recipe
with no guessing in it: every step says exactly what to do,
and in what order, and when to stop.

Every algorithm has two things stated before the first step:

1. **The input** — what goes in.
2. **The output** — what comes out.

A divisibility test is the perfect first algorithm. "Is this
number divisible by 3?" The input is the number. The output
is a Yes or a No. And the steps are:

1. Add the digits of the number.
2. Is the digit-sum divisible by 3?
3. If Yes — the number is divisible by 3. If No — it is not.

An algorithm is best drawn, not only written. The drawing is
called a **flowchart**, and it uses four shapes, always the
same four:

- The **terminator** (a rounded oval) — Start and End. Every
  chart begins in one and ends in one.
- The **input/output** box (a slanted parallelogram) — what
  goes in, or what comes out. "Enter the number." "Say Yes or
  No."
- The **process** box (a rectangle) — a thing to do. "Add the
  digits."
- The **decision** (a diamond) — a question with two ways out.
  "Is the digit-sum divisible by 3?" The two arrows out are
  labelled **Yes** and **No**, and every arrow must lead
  somewhere — a decision with a missing exit is not a chart,
  it is a dead end.

Now build it. Take the number 342. Input: 342. Process: add
the digits — 3 + 4 + 2 = 9. Decision: is 9 divisible by 3?
Yes. Output: 342 is divisible by 3. Check it by hand: 342 ÷ 3
= 114, exactly. The chart told the truth.

**Debugging** is finding where a chart lies. A chart is never
trusted on the strength of one lucky number — it is traced
with numbers whose answers you already know. Trace "is 345
divisible by 2?" through a chart that only looks at the last
digit and says Yes if the digit is even: last digit 5, odd,
so No — and 345 is indeed odd, so the chart was right there.
Trace "is 340 divisible by 2?" through the same chart: last
digit 0, even, Yes — and 340 ÷ 2 = 170, so right again. Now
trace a chart that says "divisible by 3 if the LAST digit is
3, 6 or 9": 342 ends in 2, so it says No — but 342 IS
divisible by 3. The chart is wrong, and the tracing found it:
the decision looked at the wrong thing. The fix is to change
the decision to the digit-sum, and then trace again — 342:
digit-sum 9, divisible by 3, Yes; 345: digit-sum 12,
divisible by 3, Yes (345 ÷ 3 = 115); 341: digit-sum 8, not
divisible by 3, No (341 ÷ 3 = 113 remainder 2). Three known
answers, three matches — the chart is debugged.

Your turn: draw the "divisible by 2" flowchart for yourself
— Start, input the number, look at the last digit, decision
(even?), Yes and No exits, End — and trace it with 47, 58 and
60.

## Sub lesson 2 — Working with Lists of Data

An algorithm often works on a **list of data** — numbers in
an order, one after another. Three things are done to lists,
and this sub lesson is all three.

**Sorting** means putting the list in order — smallest to
largest, say — without losing or adding a single item. Sort
by comparing and swapping, one pair at a time, until no pair
is the wrong way round:

Take 7, 2, 9, 4. Compare 7 and 2 — wrong way round, swap:
2, 7, 9, 4. Compare 7 and 9 — right way, leave them. Compare
9 and 4 — wrong way, swap: 2, 7, 4, 9. Start again from the
top: 2 and 7 are right, 7 and 4 are wrong, swap: 2, 4, 7, 9.
Start again: 2 and 4 right, 4 and 7 right, 7 and 9 right.
Done — 2, 4, 7, 9. Four items in, the same four items out,
only the order changed.

**Searching** means finding a value in a list, if it is there.
The plain way is a **linear search** — check the items one by
one, in order, until the value is found — or the list runs
out. In the sorted list 2, 4, 7, 9, search for 7: check 2
(no), check 4 (no), check 7 (yes — found at the third place).
Search for 8: check 2, 4, 7, 9 — no match, so 8 is not in
the list. In a SORTED list you can stop early: searching for
8, once you reach 9, you know 8 cannot appear later, because
everything after 9 is bigger than 9. A search is an algorithm
too — input: the list and the value; output: where it is, or
"not in the list".

**Generating lists by simulation** means building a list of
data by imitating chance, instead of waiting for the real
thing to happen. Roll a die twenty times and write down every
result in order: 3, 1, 6, 2, 5, 4, 4, 1, 6, 2, 3, 5, 1, 4, 6,
2, 3, 3, 5, 4. That is a list of twenty results — and it is
data. No one planned the numbers; the die made them. That is
what a simulation is for: the real experiment (a die rolled
by a machine thousands of times, a coin flipped again and
again) is imitated, and the list it makes can be sorted (how
many 6s? how many 1s?) and searched (did a 5 ever come up?),
exactly like any other list of data.

That is the whole lesson: an algorithm is exact steps from a
stated input to a stated output; a flowchart draws those steps
in four shapes; a chart is debugged by tracing it with known
answers; and a list of data is sorted, searched, and built by
simulation — three ways of working it, all of them exact.

## Do It Yourself

1. Draw the flowchart for "is the number divisible by 5?"
   (Input: the number. Decision: does it end in 0 or 5?) Trace
   it with 35, 42 and 90. (35 → ends in 5 → Yes; 42 → ends in
   2 → No; 90 → ends in 0 → Yes.)
2. Sort this list smallest to largest, swapping one wrong
   pair at a time: 6, 1, 8, 3. (6, 1, 8, 3 → 1, 6, 8, 3 → 1, 6,
   3, 8 → 1, 3, 6, 8.)
3. Search the sorted list 1, 3, 6, 8 for the value 6, and say
   how many checks it took. Then search it for 5, and say
   where you could stop early and why. (6 found at the third
   check; 5: 1, 3, then 6 — once you reach 6 you can stop,
   because everything after it is bigger than 5.)
4. Roll a die ten times and write the results in order. Sort
   your list. Did the number 6 appear? Search your sorted
   list for it.
