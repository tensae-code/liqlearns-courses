# Video script — Defining New Data Types in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **type definition** gives a **name** to a type construction, once, for the whole program. Pascal gathers definitions in a **type** section: `type TMark = 1..10; TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — after which TMark and TDay are used exactly like integer or real. C++ spells the same act **typedef** (or the newer **using**): `typedef int TMark;` — weaker than Pascal's (an alias, not a guarded new kind), a difference in protection the pair has met before. Either way: define once, use everywhere.
The reasons compound. **Readability**: `var m: TMark` says more than `var m: integer`. **Protection**: a TMark variable inherits the subrange's guard — a mark of 47 is caught by the type. **Change in one place**: if marks become 1..12, one definition changes and the program follows. And **honesty of design**: the definitions at a program's head are its data's manifesto — read them and you know what world the program models. Types defined well are documentation the compiler checks.
