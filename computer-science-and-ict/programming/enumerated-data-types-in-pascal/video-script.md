# Video script — Enumerated Data Types in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **enumerated type** is defined by **listing its values in brackets**: `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);` — the type has exactly those values and no others. A variable of the type holds one of them: `var d: TDay; d := Wed;`. The values are **names, not texts**: they are not strings in apostrophes, and the compiler checks them — assigning `d := Holiday` is an error the moment it is written, protection no number code (1=Mon, 2=Tue…) can give.
The list's order is not decoration: it gives the values an **order**. The functions **succ** and **pred** give the next and previous value (succ(Wed) = Thu), and **ord** gives a value's position counted from 0 (ord(Mon) = 0). So enumerated values can be compared (Sat > Fri is true), stepped through in loops, and counted — the manners of numbers, with the meanings of names. Enumerations suit closed lists of the world: months, suits, directions, school grades — sets that do not grow.
