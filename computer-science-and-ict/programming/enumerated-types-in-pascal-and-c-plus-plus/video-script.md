# Video script — Enumerated Types in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **enumerated type** defines a value set by **naming its members**: Pascal writes `type TDay = (Mon, Tue, Wed, Thu, Fri, Sat, Sun);`; C++ writes `enum TDay {Mon, Tue, Wed, Thu, Fri, Sat, Sun};`. Underneath, the members **are numbered from 0 in order** in both languages — the names are the programmer's reading of stored integers. Variables of the type hold one member, members compare by their hidden numbers, and the set stays closed: no value outside the list can enter.
Pascal keeps the type **strict**: a TDay variable takes only TDay members, and its ord/succ/pred behave as Grade 7 taught. Classic C++ **enum** is **looser**: members leak into the surrounding scope as plain integers, mix freely with int arithmetic, and two enums' same-named members collide — freedoms the newer `enum class` was invented to withdraw. The section's lesson is the pair's in miniature: **the concept is shared; the protection is a language choice**, and knowing both tells you what your compiler will and will not catch.
