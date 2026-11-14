# Video script — Ordinal Data Types in General

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A type is **ordinal** when its values can be **counted in a fixed order**: each value (except the last) has a definite **next** one. Integer counts by 1; char by code; boolean is the pair false < true; an enumeration by its list; a subrange inherits its host's order. Real is the great **non-ordinal**: between any two reals there is another, so no 'next real' exists. Ordinality, not size, is the property the languages' rules keep asking about.
Ordinal types share an instrument set. **ord(x)** gives a value's position number; **succ(x)** and **pred(x)** give its neighbours; **for** loops may be steered by any ordinal variable; **case** selectors must be ordinal; and enumerations/subranges in Pascal and their kin obey the family's comparisons. Learn a type's ordinality and its allowed tools follow without memorising lists: the rules of for and case — which puzzled as arbitrary in Grade 8 — stand revealed as one rule: **these constructions count, so their steersman must be countable**.
