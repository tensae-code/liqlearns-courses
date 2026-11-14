# switch — Multiple-Way Selection

## Do it first

A chain of ifs asking 'is it 1? is it 2? is it 3?' deserves a cleaner tool. switch is that tool — this lesson uses it, and respects its one sharp edge.

## Sub lesson 1 — Cases that match a value

**switch (n) { case 1: … }** compares **n** once against each **case** constant. On a match, that case's statements run. switch suits selections driven by **one value with many named possibilities** — menu choices, day numbers, grade letters — where an if-elif chain would repeat the same test clumsily.

[Picture — cases that match a value]

## Sub lesson 2 — break and default — the two guards

Without **break**, execution **falls through**: the matched case runs, then the **next** case runs too, and so on — occasionally wanted, usually a bug. **default** is the case for **everything else**, the switch's else, catching values the writer did not name. The book adds a full **exercises** section (§3.26) after the structure (§3.25): trace each exercise by naming the matched case and every statement that runs before a break stops it.

[Picture — break and default — the two guards]

## Say it to your companion

Tell your companion, in your own words: switch selects among many ways by matching one value: the tested value is compared with each case label, the matching case's statements run, and break leaves the switch — without break execution falls through into the next case — while default catches every value no case matched. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One tested value against each case label. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: One value with many named possibilities — menus, day numbers, grade letters. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Leaves the switch. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The case for every unmatched value — the switch's else. Do this with a real example of your own and write or say how you know it is right.
