# Video script — Reading and Printing Array Elements

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The pattern is: **for (i = 0; i < n; i++) { cout << prompt; cin >> a[i]; }** — on each pass the counter selects the next element and the typed value lands in it. A friendly prompt per element ("Element 3: ") keeps the user oriented; without prompts the program seems to stare blankly while waiting.
Printing mirrors reading: **for (i = 0; i < n; i++) cout << a[i] << ' ';** walks the row and shows every element, usually with spaces or one per line so values do not fuse into one long digit string. Together the two loops are the standard frame: fill the array, process it (later lessons), show it. The count n must be the same count in every loop of the program.
