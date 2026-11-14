# The Case Instruction in Pascal

## Do it first

Some choices are not two-way. A mark is 1, 2, 3, 4 or 5; a month has twelve names. Grade 8 and Grade 10 teach the instruction built for choice-by-value: case.

## Sub lesson 1 — Selector and labels — one value, one branch

The **case** instruction begins with a **selector** — an expression of ordinal type — and lists **labels**: `case n of 1: writeln('one'); 2: writeln('two'); else writeln('other') end;`. The selector is evaluated **once**; the branch whose label equals its value executes; the optional **else** catches every unlisted value. Labels may be single values, lists (1, 3, 5:) or ranges (1..5:). Without else and with an unlisted value, case does nothing and passes on — a silence the writer must intend.

[Picture — Selector and labels — one value, one branch]

## Sub lesson 2 — case against if-chains — choosing the chooser

A chain of if…else if tests **conditions** one by one, each possibly different; case tests **one value** against a set — clearer when the choice is truly by value, and the compiler can even check the labels for duplicates. C++ spells the same idea **switch**, with break ending each branch — forgetting break lets execution **fall through** into the next branch, switch's classic trap, which Pascal's case does not have. Rule: one value choosing among labelled roads — case; unrelated conditions — the if-chain.

[Picture — case against if-chains — choosing the chooser]

## Say it to your companion

Tell your companion, in your own words: The **case** instruction begins with a **selector** — an expression of ordinal type — and lists **labels**: `case n of 1: writeln('one'); 2: writeln('two'); else writeln('other') end;`. The selector is evaluated **once**; the branch whose label equals its value executes; the optional **else** catches every unlisted value. Labels may be single values, lists (1, 3, 5:) or ranges (1..5:). Without else and with an unlisted value, case does nothing and passes on — a silence the writer must intend. A chain of if…else if tests **conditions** one by one, each possibly different; case tests **one value** against a set — clearer when the choice is truly by value, and the compiler can even check the labels for duplicates. C++ spells the same idea **switch**, with break ending each branch — forgetting break lets execution **fall through** into the next branch, switch's classic trap, which Pascal's case does not have. Rule: one value choosing among labelled roads — case; unrelated conditions — the if-chain. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A selector — an expression of ordinal type. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Once. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It catches every unlisted value. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Single values, lists (1, 3, 5:) and ranges (1..5:). Do this with a real example of your own and write or say how you know it is right.
