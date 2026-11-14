# Hiding and Showing Sprites — and the Wait Until Block

## Do it first

A character must not be on stage yet — its scene comes later. And a door must stay shut until the player reaches it. One tool removes and returns characters; the other makes a script stand still and wait for its moment.

## Sub lesson 1 — Hide and show

**Hide** makes a sprite invisible on the stage: it is still in the project, with all its scripts, but nobody sees it and it takes part in nothing visible. **Show** brings it back. Hide at a script's start is how a project keeps its later characters ready but off stage — a character for scene two waits hidden through scene one, then a show block brings it in at its entrance. A hidden sprite that is never shown again is the commonest beginner fault: the sprite has not been deleted, only hidden.

[Picture — a picture of a sprite fading out under a hide block and reappearing under a show block, with its scripts still listed beside it]

## Sub lesson 2 — Wait until — the script stands still

**Wait until** holds a script in place: the script stops at that block and does not move on until the condition inside it becomes true, then it continues. It is a pause with a reason — wait until the player touches the door, wait until a backdrop switches, wait until a key is pressed. Combined with hide and show, it makes entrances exact: a sprite waits hidden, its script waits until its scene's condition is true, and then show brings it on stage at precisely that moment.

[Picture — a picture of a script paused at a wait-until block with a condition diamond, a clock beside it, and the script continuing once the condition turns true]

## Say it to your companion

Tell your companion, in your own words: hide and show take a sprite off and on the stage without deleting it, and wait until pauses a script until its condition becomes true. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: hide a sprite and show it again with blocks. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
2. Show it, don't just say it: say what wait until does to a script. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
3. Show it, don't just say it: combine hide/show with wait until so a sprite appears exactly when a condition becomes true. Do this with a real example from your own work in Scratch or your own school day, and write or say how you know it is right.
