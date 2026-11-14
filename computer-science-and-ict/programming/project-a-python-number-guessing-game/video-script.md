# Video script — Project — a Python Number-Guessing Game

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The design names the game's working before any code: the computer **chooses a secret** in a stated range (the random module earns its place), the player **guesses**, the program **answers** — higher, lower, or correct — and the loop **repeats until correct**, counting attempts. The design also fixes the courtesies that make it a game and not a trap: the range is told, invalid guesses are answered kindly, and the final score (attempts) is reported. Jordan's unit projects are designed on paper first, in the book's own order: the flowchart from the first lesson carries the whole game.
The build assembles the unit: **variables** hold the secret and the count, **input and conversion** take the guess, a **while loop** repeats it, **conditions** compare and answer, and the **random** choice starts each new game. The **puzzle game** companion spends the same kit differently — a shuffled word or a slid tile — proving the kit is general. The project's closing craft is testing as a player, not as the builder: play unfairly (guess outside the range, type letters) and repair what the player finds, because the player is the program's true examiner.
