# Video script — The Case Instruction in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **case** instruction begins with a **selector** — an expression of ordinal type — and lists **labels**: `case n of 1: writeln('one'); 2: writeln('two'); else writeln('other') end;`. The selector is evaluated **once**; the branch whose label equals its value executes; the optional **else** catches every unlisted value. Labels may be single values, lists (1, 3, 5:) or ranges (1..5:). Without else and with an unlisted value, case does nothing and passes on — a silence the writer must intend.
A chain of if…else if tests **conditions** one by one, each possibly different; case tests **one value** against a set — clearer when the choice is truly by value, and the compiler can even check the labels for duplicates. C++ spells the same idea **switch**, with break ending each branch — forgetting break lets execution **fall through** into the next branch, switch's classic trap, which Pascal's case does not have. Rule: one value choosing among labelled roads — case; unrelated conditions — the if-chain.
