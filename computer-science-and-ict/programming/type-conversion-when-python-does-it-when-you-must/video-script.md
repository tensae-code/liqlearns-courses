# Video script - Type conversion - when Python does it, when you must

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.
A short video script for this lesson; its placement names no full-script need.

---

Values can change type. That is type conversion.

Sometimes Python converts by itself.
3 + 2.5 = 5.5.
An int plus a float gives a float.
Why? So nothing is lost.
That is implicit conversion.

Sometimes YOU must convert.
int() - float() - str().
The name is the type you want.

Watch the clash:
"5" + 3 - ERROR.
A string cannot add a number.
Convert first: int("5") + 3...
8. Clean.

Python converts when it is safe. You convert when it is not.
