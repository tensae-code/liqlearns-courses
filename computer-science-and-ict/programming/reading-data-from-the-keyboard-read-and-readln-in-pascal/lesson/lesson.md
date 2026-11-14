# Reading Data from the Keyboard — read and readln in Pascal

## Do it first

Programs that only print are monologues. Grade 8 and Grade 10 teach the listening half in the same place in both books: read and readln, the instructions that let the user answer.

## Sub lesson 1 — read and readln — filling variables from the keyboard

**read** takes the next values typed at the keyboard and stores them into the variables named in its brackets: `read(a, b)` waits, takes two values and places them. **readln** does the same and then **skips to the end of the input line**, discarding whatever else was typed on it — the safer default for line-by-line data. When a read executes, the program **waits**: execution pauses until the user types and presses Enter. C++ reads with `cin >>`.

[Picture — read and readln — filling variables from the keyboard]

## Sub lesson 2 — The conversation — prompt, read, echo

Interactive programs follow a courtesy protocol this section makes explicit: **prompt first** (writeln what you ask for — the user cannot guess), **read second**, **echo or use third** (show what was taken, so mistyping is caught at once). Numbers are typed separated by spaces or Enter; characters read raw, one by one, including spaces — so reading a name with readln into a string differs from reading numbers. Input is a contract: the program states the order and kinds it expects, the user supplies exactly those.

[Picture — The conversation — prompt, read, echo]

## Say it to your companion

Tell your companion, in your own words: **read** takes the next values typed at the keyboard and stores them into the variables named in its brackets: `read(a, b)` waits, takes two values and places them. **readln** does the same and then **skips to the end of the input line**, discarding whatever else was typed on it — the safer default for line-by-line data. When a read executes, the program **waits**: execution pauses until the user types and presses Enter. C++ reads with `cin >>`. Interactive programs follow a courtesy protocol this section makes explicit: **prompt first** (writeln what you ask for — the user cannot guess), **read second**, **echo or use third** (show what was taken, so mistyping is caught at once). Numbers are typed separated by spaces or Enter; characters read raw, one by one, including spaces — so reading a name with readln into a string differs from reading numbers. Input is a contract: the program states the order and kinds it expects, the user supplies exactly those. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It waits for two typed values and stores them into a and b. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: It skips to the end of the input line, discarding the rest of that line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It waits — execution pauses until the user types and presses Enter. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: cin >>. Do this with a real example of your own and write or say how you know it is right.
