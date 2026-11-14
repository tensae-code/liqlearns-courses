# Programming the Maze — Start, and Mouse Following

## Do it first

Press the green flag twice on a half-built game: once the character starts where it finished last time, somewhere mid-maze. A real game must begin identically every single run. And once it begins, the player — holding only a mouse — must be able to steer without ever touching a wall.

## Sub lesson 1 — The start situation — always the same beginning

Under the green flag, the game puts everything where the game begins. Two moves make the **start situation**: send the character to its **start position** (its exact x and y at Maze 1's entrance), and **switch the backdrop to Maze 1**. Those two, run on every flag click, mean a game can be replayed cleanly any number of times: wherever the last game ended, the new game resets to the same first moment. Resetting on the flag is part of the finished game's promises, not an extra.

[Picture — a picture of a maze game at the flag click: the character jumping back to Maze 1's entrance and the backdrop switching to Maze 1, with a circular reset arrow over the scene]

## Sub lesson 2 — Follow the pointer — walls end, goal advances

Play itself is pointer play. The character first **waits for the mouse** — stands at the start until the player brings the pointer to it — then **follows the pointer** through the passages, so the player's hand, moving carefully, steers it. Two touching tests watch constantly while it follows. **Touching a wall ends the game**: the wall colour test fires, and play stops — the maze's danger is real because a shaky hand is a lost game. **Touching the goal changes the level**: the backdrop switches to the next maze and the character goes to that level's start. Wall and goal are the whole ruleset of the maze: follow, do not touch the walls, reach the goal.

[Picture — a picture of a small character following a mouse pointer through maze passages, a wall glowing where a touch would end the game, and the goal at the end switching the stage to the next maze]

## Say it to your companion

Tell your companion, in your own words: the flag resets the character and the Maze 1 backdrop every run; after that the character waits for the pointer, follows it, loses on a wall touch, and changes level on a goal touch. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: program the start situation: character to its start position, stage to Maze 1, on the green flag. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
2. Show it, don't just say it: make the character wait for the mouse pointer, then follow it. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
3. Show it, don't just say it: end the game when the character touches a wall. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
4. Show it, don't just say it: change the level when the character touches the goal. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
