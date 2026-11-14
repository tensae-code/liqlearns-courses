# Video script — Converting Octal to Binary

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An octal digit runs from 0 to 7, and three binary digits also run from 000 to 111 — the same eight values. So **each octal digit converts on its own** into **exactly three binary digits**: 0→000, 1→001, 2→010, 3→011, 4→100, 5→101, 6→110, 7→111. The three-digit group is never shortened — a group of 001 keeps its leading zeros, because the zeros hold the places of the digits beside it.
Convert **every** digit of the octal number and write the groups **side by side, in the same order**: 47₈ → 4→100, 7→111 → **100111₂**. Nothing is added and nothing is carried — the work is finished when every digit has its group. Check by value if unsure: 100111₂ = 32+4+2+1 = 39, and 47₈ = 39. Malaysia teaches this direct road because octal exists in computing precisely as binary's short writing.
