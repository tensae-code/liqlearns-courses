# Video script — The Concept of an Action in a Program

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **action** is one **elementary operation performed by the executor** while a program runs: taking a value, computing, storing, showing, choosing. Actions differ from the program's *text*: the text stands still on the page, while actions **happen in time, one after another**, changing the program's state — the values in memory — as they go. To understand any program is to follow its actions: what happens first, what changes, what happens next. A program whose actions you cannot trace is a program you do not yet understand.
Some actions are **elementary** for their executor — one command, done at once, like adding two numbers in a register. Others are **composed**: named blocks (an instruction, a procedure) that unfold into many elementary actions when executed. The same deed can be elementary on one level and composed on another: 'print the table' is one action to the caller, a hundred to the machine. Programming is largely the art of **composing**: building big actions from small ones until the program reads as a few clear deeds.
