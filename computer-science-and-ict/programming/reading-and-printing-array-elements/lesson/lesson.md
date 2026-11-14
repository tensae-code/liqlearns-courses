# Reading and Printing Array Elements

## Do it first

Typing five separate read statements for five elements does not scale to five hundred. This lesson is the pair of loops every array program starts with.

## Sub lesson 1 — Reading in — the input loop

The pattern is: **for (i = 0; i < n; i++) { cout << prompt; cin >> a[i]; }** — on each pass the counter selects the next element and the typed value lands in it. A friendly prompt per element ("Element 3: ") keeps the user oriented; without prompts the program seems to stare blankly while waiting.

[Picture — reading in — the input loop]

## Sub lesson 2 — Printing out — the output loop

Printing mirrors reading: **for (i = 0; i < n; i++) cout << a[i] << ' ';** walks the row and shows every element, usually with spaces or one per line so values do not fuse into one long digit string. Together the two loops are the standard frame: fill the array, process it (later lessons), show it. The count n must be the same count in every loop of the program.

[Picture — printing out — the output loop]

## Say it to your companion

Tell your companion, in your own words: Arrays are filled and emptied by loops: one loop reads a value into each element in turn (cin into a[i]), another prints each element in turn (cout of a[i]) — the loop counter is the index, so the same two loop shapes serve any array of any size. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The loop counter, used as the index. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: So the user knows what the program waits for. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Every element, in turn. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The standard frame: fill the array, then show it. Do this with a real example of your own and write or say how you know it is right.
